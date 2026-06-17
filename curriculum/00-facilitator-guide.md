# Facilitator Guide

## Training Goal

By the end of the session, participants should be able to use Codex to perform a small scientific-support task end to end: describe the context, inspect local evidence, produce a useful output, verify the result, and document what another person would need to continue.

## Learning Objectives

Participants will practice how to:

- Recognize which scientific-staff tasks are good candidates for Codex assistance.
- Frame a task with enough context for Codex to act safely.
- Ask Codex to inspect local files, repo docs, scripts, and outputs before making claims.
- Convert messy scientific-support data into ranked, readable summaries.
- Separate sensitive source data from sanitized deliverables.
- Keep unresolved findings explicit instead of forcing false certainty.
- Use verification logs and handoff notes to make work reproducible.

## Session Options

### 60 Minutes

| Time | Segment |
| --- | --- |
| 0:00-0:10 | What Codex is good at for scientific staff |
| 0:10-0:20 | Task idea gallery and prompt patterns |
| 0:20-0:45 | Exercise 1: scientific software inventory |
| 0:45-0:55 | Share outputs and critique evidence |
| 0:55-1:00 | Wrap-up checklist |

### Half Day

| Time | Segment |
| --- | --- |
| 0:00-0:20 | Operating model |
| 0:20-0:45 | Task idea gallery |
| 0:45-1:15 | Source-grounded analysis |
| 1:15-1:50 | Exercise 1: scientific software inventory |
| 1:50-2:00 | Break |
| 2:00-2:30 | Privacy and local data boundaries |
| 2:30-3:00 | Exercise 2: renewal snapshot |
| 3:00-3:25 | Repo workflows and verification |
| 3:25-3:45 | Exercise 5: task triage |
| 3:45-4:00 | Capstone review with rubric |

## Instructor Setup

1. Copy this package into a local workspace participants can access.
2. Confirm participants can open Markdown files and CSV files.
3. If participants will use Codex directly, ask them to work in a scratch folder.
4. Do not use live sensitive spreadsheets, production databases, or person-level inventories during training.
5. Use only the synthetic files in [data/](../data) unless the group has formal approval to use real data.

## Core Teaching Message

Codex works best when the request gives it a job, a source boundary, and a standard of proof.

Weak prompt:

```text
Summarize this spreadsheet.
```

Better prompt:

```text
Inspect the CSV in data/scientific_software_inventory.csv. Create a ranked summary of scientific software families by unique computers. Exclude operating systems, office apps, browsers, security tools, and runtimes. Keep the output aggregate-only and explain which columns you used.
```

## Common Coaching Moves

- Ask "What evidence did Codex use?"
- Ask "What did it exclude, and why?"
- Ask "Could this output be shared without exposing private data?"
- Ask "What command, file, or check would let another person reproduce this?"
- Ask "Where should uncertainty be preserved instead of smoothed over?"

## Materials Checklist

- [ ] Slide outline or local deck
- [ ] Task-idea catalog
- [ ] Prompt-pattern handout
- [ ] Privacy and verification checklist
- [ ] Synthetic CSV files
- [ ] Exercise instructions
- [ ] Rubric
- [ ] Verification log template

## Debrief Questions

- What changed when the prompt named the source files and exclusion rules?
- Did Codex produce a useful artifact or just a narrative?
- Was the answer appropriately concise for the audience?
- What would need to be verified before sharing the result?
- What should be documented for a future handoff?
- What is one real task participants can safely try next week?
