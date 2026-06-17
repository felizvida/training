# Exercise 1: Scientific Software Inventory

## Scenario

A lab manager wants to know which scientific software appears most often on managed computers. The source file is synthetic but includes realistic fields.

Source:

- [../data/scientific_software_inventory.csv](../data/scientific_software_inventory.csv)

## Goal

Create a ranked, aggregate-only summary of scientific software families.

## Instructions For Participants

Ask Codex to:

1. Inspect the CSV.
2. Exclude usual-suspect software such as operating systems, office tools, browsers, security tools, management agents, and runtimes.
3. Collapse related products into families, such as Fiji/ImageJ and R/RStudio.
4. Rank by unique computer count.
5. Include total runs and latest observed use as supporting signals.
6. List uncertain classifications.
7. Keep the final output aggregate-only.

## Starter Prompt

```text
Inspect data/scientific_software_inventory.csv and create a ranked scientific software summary for a lab manager.
Exclude OS, office, browser, security, management, and runtime tools.
Collapse closely related products into software families.
Rank by unique computers, include total runs as a secondary signal, and keep the output aggregate-only.
List the columns used and any uncertain classifications.
```

## Expected Output Shape

| Rank | Software family | Unique computers | Total runs | Latest observed use | Notes |
| --- | --- | ---: | ---: | --- | --- |
| 1 | Example family | 10 | 250 | 2026-06-01 | Grouped related products |

## Debrief

- Did Codex explain the grouping rules?
- Did it avoid exposing computer IDs?
- Did it avoid non-scientific software?
- Did it distinguish counts from usage?
- Were uncertain classifications preserved?

