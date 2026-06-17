# Module 1: Codex Operating Model

## Purpose

Teach staff to treat Codex as a local collaborator that can inspect files, run commands, edit documents, and verify outputs when given a clear boundary.

## Key Ideas

- Codex should inspect the workspace before changing it.
- The user should name the desired artifact and audience.
- Codex should report what it used as evidence.
- For serious work, verification is part of the task, not an optional extra.
- If a better tool is needed, Codex should install or request permission rather than quietly switching to a weaker method.

## What Codex Is Useful For

- Summarizing local datasets into readable decision tables.
- Comparing old and new data snapshots.
- Turning ad hoc workflows into documented runbooks.
- Building small scripts, checks, dashboards, or reports.
- Cleaning and restructuring documentation.
- Drafting handoffs, lessons learned, and GitHub-safe memos.
- Reviewing code or workflows for risks and missing tests.

## What Staff Must Still Own

- Approving access to sensitive systems.
- Deciding whether row-level data can be used or shared.
- Confirming scientific interpretation and policy implications.
- Providing domain-specific constraints that are not in the files.
- Reviewing final outputs before external distribution.

## Prompt Pattern

```text
You are working in [folder/repo]. First inspect [files/docs/scripts].
Goal: [specific artifact].
Audience: [who will read/use it].
Rules: [privacy, exclusions, formatting, source boundaries].
Verification: [commands/checks/manual review expected].
Afterward, summarize what changed and what you verified.
```

## Demonstration

Use this prompt with Exercise 1:

```text
Create a ranked scientific software summary from data/scientific_software_inventory.csv.
Collapse closely related products into software families, exclude common office/browser/security/runtime tools, and keep the result aggregate-only.
Show the columns used as evidence and list any uncertain classifications.
```

## Instructor Notes

Emphasize that Codex is not magic because it "knows" the answer. It becomes useful because it can inspect the actual local evidence and work through the steps in a way the human can audit.

