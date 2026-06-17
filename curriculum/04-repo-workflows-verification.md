# Module 4: Repo Workflows and Verification

## Purpose

Teach staff to ask Codex to follow existing project workflows instead of inventing one-off methods.

## Repo-Aware Pattern

```text
Inspect the repository docs and scripts first.
Use the existing refresh, build, or verification workflow if one exists.
Do not invent a new path unless the repo lacks one.
After running the workflow, report the command, output files, and verification status.
```

## What To Ask Codex To Find

- README files
- AGENTS.md or local instructions
- docs/ plans and runbooks
- scripts/ refresh or import commands
- tests or verification scripts
- output directories
- prior handoff notes

## Verification Examples

| Work Type | Verification |
| --- | --- |
| Data refresh | Import command plus validation script |
| Spreadsheet model | Rebuild command plus key output totals |
| Web app | Local server plus screenshot or Playwright check |
| Python package | Unit tests plus lint or type check if configured |
| Documentation | Link check, table of contents check, or fresh-reader runbook review |
| GitHub workflow | Inspect actual run status, commit, or check output |

## Exercise Prompt

```text
Pretend this folder is a small analysis repo.
Create a verification plan for a recurring monthly data refresh.
The plan must list expected inputs, commands, outputs, checks, failure handling, and what to include in a status report.
```

## Instructor Notes

The habit to build is simple: "What does the repo already say?" This prevents Codex from solving yesterday's problem with a brand-new workflow that nobody else can maintain.

