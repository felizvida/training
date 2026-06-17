# Exercise 4: Restart Handoff

## Scenario

A Codex thread has refreshed a local analysis, produced a summary table, and run a validation check. The team wants a note that lets a future staff member or new Codex thread continue.

## Goal

Create a durable, sanitized restart note.

## Instructions For Participants

Ask Codex to write a handoff that includes:

- Goal
- Current state
- Inputs
- Commands run
- Outputs produced
- Verification status
- Privacy notes
- Known limitations
- Next steps

## Starter Prompt

```text
Create a restart handoff for this completed analysis.
Make it durable enough for a new Codex thread to continue.
Include goal, current state, key files, commands already run, outputs, verification status, limitations, and next steps.
Keep it sanitized: no secrets, raw private data, names, emails, hostnames, or row-level identifiers.
```

## Evaluation Questions

- Could a new person reproduce the work?
- Are exact paths and commands present?
- Are privacy boundaries clear?
- Are remaining risks separated from completed work?
- Is the note concise enough to be useful?

