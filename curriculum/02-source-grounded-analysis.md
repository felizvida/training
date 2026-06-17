# Module 2: Source-Grounded Analysis

## Purpose

Teach participants to ask for summaries that preserve the link between conclusion and evidence.

## Good Source-Grounded Outputs Include

- The source files or artifacts used.
- The columns, fields, or scripts that mattered.
- The grouping or filtering rules.
- A concise finding table.
- Explicit uncertainty or exclusions.
- A verification note.

## Example Analytical Moves

| Task | Better Codex Instruction |
| --- | --- |
| Software inventory | "Rank by unique computers, collapse product families, exclude usual-suspect tools." |
| Snapshot comparison | "Frame this as new evidence relative to the prior source." |
| Budget renewal | "Separate true renewal/order rows from one-time adjustments and non-software costs." |
| Identity lookup | "Use local cache first, then approved authoritative lookup, then public web only as fallback." |
| Workflow status | "Inspect the actual job state or output commit before reporting status." |

## Exercise Prompt

```text
Inspect the synthetic software inventory and produce a concise summary for a lab manager.
The manager wants to know which scientific software families appear most often.
Rank by unique computer count, include total runs as a secondary signal, and add a short "what changed if this came from a second source" note.
Do not include user names, device IDs, or row-level details.
```

## Quality Bar

The output should be easy to scan, but not vague. A strong answer says something like:

```text
I used Product Name, Component Name, Last Used, Total Runs, and Computer ID. I grouped Fiji and ImageJ together, grouped R and RStudio together, and excluded office, browser, OS, security, and runtime rows.
```

## Failure Modes To Watch

- Restating every row instead of ranking findings.
- Treating source data as aggregate-only when it contains sensitive details.
- Mixing usage evidence with install or observation evidence.
- Hiding uncertain classifications.
- Producing a polished report without saying what was checked.

