# Unit 3: Privacy Boundaries And Safe Outputs

Time: 1 hour

Navigation: [Track home](README.md) | Previous: [Unit 2](unit-02-source-grounded-inventory.md) | Next: [Unit 4](unit-04-reconciliation-renewals.md)

Portfolio section: Unit 3

## Goal

Learn how to separate sensitive source data from safe, shareable outputs.

## Anchored Experience

This unit models the boundary that source files can contain detailed people, device, or operational fields, while generated outputs should usually be aggregate, sanitized, or explicitly restricted.

## Why This Matters

Good Codex work protects trust. This unit helps you feel the difference between what Codex may inspect under an appropriate local boundary and what should appear in a shared output.

## Materials

- [../handouts/privacy-and-verification-checklist.md](../handouts/privacy-and-verification-checklist.md)
- [../curriculum/03-local-data-privacy.md](../curriculum/03-local-data-privacy.md)
- [../data/scientific_software_inventory.csv](../data/scientific_software_inventory.csv)
- [../data/identity_lookup_samples.csv](../data/identity_lookup_samples.csv)

## 60-Minute Plan

| Time | Activity |
| --- | --- |
| 0-10 min | Read the privacy checklist |
| 10-25 min | Inspect the synthetic data fields |
| 25-40 min | Write privacy boundaries for two outputs |
| 40-50 min | Draft a safe-output prompt |
| 50-60 min | Save checklist result |

## Starter Prompt

```text
Inspect the synthetic source file and identify fields that could become sensitive in a real dataset.
Then propose a safe output boundary for a staff-facing summary.
Do not include row-level identifiers in the output.
If row-level evidence would be necessary, explain why and label the output restricted.
```

## Deliverable

A privacy boundary note with:

- Source fields that would be sensitive in real data.
- Output fields that are safe to share.
- Fields to omit or aggregate.
- Verification or review needed before sharing.

## Finish Line

You are done when you can explain, in plain language, what the source may contain, what the final output may show, and what should stay out. That clarity is the safety rail for every later unit.

## Self-Check

- Did you distinguish source data from shareable output?
- Did you avoid row-level details?
- Did you state when restricted review would be needed?
- Did you record the privacy boundary in the portfolio?
