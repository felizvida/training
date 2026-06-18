# Unit 2: Source-Grounded Scientific Inventory

Time: 1 hour

## Goal

Create an aggregate scientific software summary from synthetic inventory data.

## Anchored Experience

This unit models scientific software inventory work: remove common software noise, collapse closely related product families, rank by useful signals, and keep the output aggregate-only.

## Materials

- [../data/scientific_software_inventory.csv](../data/scientific_software_inventory.csv)
- [../exercises/exercise-01-scientific-inventory.md](../exercises/exercise-01-scientific-inventory.md)
- [../assessment/instructor-answer-key.md](../assessment/instructor-answer-key.md)

## 60-Minute Plan

| Time | Activity |
| --- | --- |
| 0-10 min | Inspect the CSV columns |
| 10-20 min | Decide grouping and exclusion rules |
| 20-40 min | Draft or run the summary prompt |
| 40-50 min | Compare against the answer key |
| 50-60 min | Save summary and verification notes |

## Starter Prompt

```text
Inspect data/scientific_software_inventory.csv and create a ranked scientific software summary.
Exclude operating systems, office apps, browsers, security tools, management agents, and routine utilities.
Collapse related products into families.
Rank by unique computers and include total runs plus latest observed use as supporting signals.
Keep the output aggregate-only and list uncertain classifications.
```

## Deliverable

An aggregate table with:

- Software family.
- Included products.
- Unique computer count.
- Total runs.
- Latest observed use.
- Notes or uncertainty.

## Self-Check

- Did the output name the columns used?
- Did it avoid showing computer IDs?
- Did it exclude common noise?
- Did it preserve uncertain classification choices?

