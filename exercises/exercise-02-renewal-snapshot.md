# Exercise 2: Renewal Snapshot

## Scenario

A program staff member asks, "What is left this fiscal year to order for renewals?" The source file is synthetic and contains true renewals, one-time adjustments, discontinued items, and non-software costs.

Source:

- [../data/renewal_projection_snapshot.csv](../data/renewal_projection_snapshot.csv)

## Goal

Answer the renewal question without overstating the work left.

## Instructions For Participants

Ask Codex to:

1. Inspect the snapshot.
2. Separate true renewal/order rows from adjustments, discontinued items, and non-software costs.
3. Calculate the renewal-only remaining amount.
4. Report non-renewal rows separately.
5. Record the source artifact used.

## Starter Prompt

```text
Use data/renewal_projection_snapshot.csv to answer: what is left this fiscal year to order for renewals?
Separate true renewal/order items from one-time adjustments, discontinued items, and non-software costs.
Give a concise table and a short caveat about what is excluded from the renewal-only subtotal.
```

## Expected Output Shape

| Category | Amount | Interpretation |
| --- | ---: | --- |
| Renewal/order remaining | $0.00 | True work left |
| One-time adjustments | $0.00 | Planning item, not a renewal |
| Non-software costs | $0.00 | Excluded |
| Discontinued | $0.00 | Excluded |

## Debrief

- Did Codex answer the actual question rather than repeating the raw total?
- Did it separate renewal rows from other rows?
- Did it name the source artifact?
- Did it state assumptions?

