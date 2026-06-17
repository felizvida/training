# Module 6: Task Idea Gallery

## Purpose

Expose trainees to the range of scientific-staff tasks Codex can assist with. Many people only try generic writing prompts at first; this module helps them recognize local, evidence-based work that is a better fit.

## Teaching Message

Codex can help wherever staff need to inspect evidence, organize messy inputs, create a useful artifact, verify the result, or leave a handoff.

It is not only for coding. It can support analysis, documentation, operations, training, quality checks, and scientific software stewardship.

## Gallery Walk

Use [../handouts/task-idea-catalog.md](../handouts/task-idea-catalog.md) as the participant handout.

Ask participants to mark:

- One task they could try this week.
- One task that would need a privacy boundary.
- One task that would need verification before sharing.
- One task that should become a repeatable workflow.

## Example Categories

| Category | Example |
| --- | --- |
| Data summary | "Rank scientific software families from a local export." |
| Reconciliation | "Compare a new workbook against a baseline system and explain the delta." |
| Renewal planning | "Separate true renewals from one-time adjustments." |
| Directory lookup | "Use the local cache first and mark unresolved identities." |
| Workflow status | "Inspect the actual job state before giving a status report." |
| App improvement | "Make result feedback visible near the user's workflow." |
| Testing | "Add meaningful checks using the repo's existing test stack." |
| Feature discovery | "Cluster desired capabilities before implementing anything." |
| Training repo stewardship | "Use this training repo itself as a Codex-assisted example: update modules, add exercises, verify links, and publish a release." |
| Documentation | "Create a restart note with commands, paths, checks, and caveats." |
| Lessons learned | "Write a short sanitized memo that preserves the durable lesson." |

## Activity: Task Triage

Give participants five minutes to write down three tasks from their own work. For each, ask them to fill in:

| Task | Input | Output | Privacy boundary | Verification |
| --- | --- | --- | --- | --- |
| Example | Local CSV | Aggregate table | No row-level identifiers | Row count and column audit |

Then have them choose one and write a Codex prompt using:

```text
Goal:
Source:
Audience:
Privacy boundary:
Output:
Verification:
What not to assume:
```

## Instructor Notes

Keep the discussion practical. The best examples sound like real staff work:

- "Every month I need to know what changed."
- "I have three exports that disagree."
- "I need to brief a lab manager without exposing names."
- "I need this process to be restartable after I am away."
- "I need to know whether the workflow actually finished."
- "This training package needs to evolve after every workshop."

If someone suggests a task involving live systems, people, or sensitive records, coach them to add source boundaries, authorization requirements, and an explicit privacy review.

Use this repository as a live example when useful: Codex can add a new training module, update cross-links, run package checks, commit the change, tag a patch release, and publish release notes.
