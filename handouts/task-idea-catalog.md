# What Codex Can Help Scientific Staff Do

This catalog gives trainees concrete ideas for tasks Codex can assist with. The examples are adapted from real project patterns, but written generically and safely for training.

## How To Read This

Codex is most useful when a task has:

- Local evidence to inspect.
- A clear audience.
- A concrete output.
- Privacy or source boundaries.
- A way to verify the result.

## Task Ideas By Work Type

| Work type | Codex-assisted task | Typical output | Verification |
| --- | --- | --- | --- |
| Scientific software inventory | Rank specialized scientific tools by install or usage signal, collapse related product families, and remove common software noise | Aggregate table, short report, CSV, PDF | Column audit, grouping rules, row count checks |
| Multi-source reconciliation | Compare a baseline system against a new workbook or snapshot and explain what new evidence appears | Delta summary, exception table, caveats | Source-by-source comparison and sampled records |
| Lab or group reporting | Connect a local roster or lab-resolution source to software, license, or device evidence | Aggregate group report | Local cache query, privacy review |
| Budget and renewal planning | Separate true renewals from adjustments, discontinued items, and non-software costs | Renewal-only subtotal, action list | Snapshot totals and category checks |
| Local data refresh | Follow an existing import, normalization, and verification workflow for a new export | Refreshed database, workbook, audit log | Repo scripts, validation commands |
| Workflow monitoring | Inspect a scheduled job, GitHub Action, or data-refresh run and report actual status | Status report with run ID and next action | Current job state, commit, artifact, or logs |
| Ranking or score changes | Compare dated result snapshots and summarize entrants, exits, and rank movement | Churn summary, ranked table | Commit-based diff or stable output files |
| Identity or role lookup | Resolve people, roles, or responsible parties using local cache first and authoritative systems second | Human-readable answer with caveats | Source order log, unresolved list |
| Documentation cleanup | Turn scattered notes into a durable runbook or user guide | Markdown docs, checklist, index updates | Link checks, fresh-reader review |
| Restart handoff | Record enough context for another staff member or new Codex thread to continue | Handoff document | Exact paths, commands, validation status |
| Lessons learned | Produce a concise, sanitized source memo from operational work | GitHub-safe memo | Secret scan, source caveats |
| Memory and skills stewardship | Convert durable Codex context or reusable instructions into a sanitized training pattern | Scenario, checklist, prompt recipe | Privacy scan, current-evidence reminder |
| Code review | Review a change for bugs, regressions, missing tests, and operational risk | Findings-first review | File/line references, test gaps |
| Test and CI hardening | Add or improve lint, coverage, unit, integration, or browser checks using existing repo patterns | CI config, test files, coverage baseline | Local quality gate and CI status |
| App usability polish | Improve feedback, dirty-state cues, navigation, or result surfacing in an internal tool | UI changes, docs, tests | Browser smoke, Playwright, screenshots |
| Feature discovery | Study a comparator product or user request, cluster desired capabilities, and map them to repo surfaces | Feature map, implementation plan | Source citations, repo surface audit |
| Training material creation | Build exercises, rubrics, synthetic data, and facilitator notes from real workflow patterns | Training package | Link checks, privacy review, instructor answer key |
| Training repo stewardship | Maintain a training repository like this one by adding task examples, updating modules, checking links, tagging releases, and publishing notes | Repo update, release notes, tagged release | Markdown link check, privacy scan, git status, release verification |

## This Repo Is An Example

This training repository itself belongs in the idea gallery. It models a Codex-assisted task where the input is a set of recurring work patterns, the output is a reusable training package, and the verification includes link checks, privacy review, release notes, commits, tags, and GitHub releases.

Example prompt:

```text
Inspect this training repo and update it for a new audience or training need.
Keep the examples synthetic, preserve privacy boundaries, update the relevant modules and handouts, run link and boilerplate checks, then commit, tag, and publish a release note.
```

## Task Ideas By Staff Role

| Role | Good first Codex tasks |
| --- | --- |
| Lab manager | Aggregate software usage, renewal needs, equipment/software ownership caveats, group-level summaries |
| Scientific program staff | Portfolio summaries, comparison memos, status reports, source-grounded briefings |
| Data steward | Refresh workflows, normalization checks, privacy reviews, data dictionaries |
| Informatics staff | Repo runbooks, tests, CI, app polish, bug triage, release notes |
| Training coordinator | Scenario cards, synthetic exercises, answer keys, participant handouts |
| Training repo maintainer | Curriculum updates, idea-gallery expansion, release notes, link checks, versioned releases |
| Operations liaison | Lessons learned, governance memos, handoffs, unresolved-risk registers |

## Anchor Experiences For This Training

This training is anchored on concrete project patterns from the package owner's work. These are the examples facilitators should return to first:

- Scientific software inventory and family-collapsed summaries.
- Multi-source reconciliation and "what new evidence did we learn?" comparisons.
- Local data refreshes with documented import, rebuild, and verification steps.
- Renewal planning that separates true action items from adjustments and non-software costs.
- Workflow status checks grounded in actual run state, commits, or artifacts.
- Local-first identity or role lookup with unresolved cases kept explicit.
- App usability, testing, CI, and documentation improvements.
- Restart handoffs, source memos, sanitized memory/skill patterns, release notes, and this training repo's own maintenance.

## Brief Additional Ideas For Scientific Staff And Researchers

These are for information only. Use them as quick inspiration after the anchored examples above, not as the center of the training.

| Situation | Possible Codex help | Keep in mind |
| --- | --- | --- |
| Research planning | Turn a broad question into a workplan, assumptions list, and data-needs checklist | Human owner decides scientific direction |
| Result review | Summarize local result tables or QC reports and list questions for follow-up | Treat this as triage, not interpretation |
| Reproducible analysis | Document scripts, commands, parameters, inputs, and outputs | Verify against actual files and logs |
| Protocol support | Convert an approved protocol into a checklist or training quiz | Do not invent protocol steps |
| Manuscript support | Draft methods notes, figure legends, or reviewer-response matrices from approved materials | Expert review is required |
| Collaboration handoff | Summarize current state, file locations, open questions, and next decisions | Keep sensitive details out unless authorized |

For research use, Codex should help organize, check, document, and draft. Scientific interpretation, clinical judgment, authorship decisions, and policy decisions still belong to qualified humans.

## The Task Maturity Ladder

1. **Summarize:** "Inspect this local file and summarize what matters."
2. **Structure:** "Turn this into a ranked table with grouping and exclusions."
3. **Compare:** "Tell me what changed relative to this baseline."
4. **Verify:** "Run the existing checks and record the evidence."
5. **Automate:** "Make this repeatable with a script, template, or workflow."
6. **Handoff:** "Document it so someone else can continue."

## Good Starter Prompts

### Discover Possible Codex Help

```text
Here is my current work area: [brief description].
List 10 concrete tasks Codex could assist with.
For each, say the likely input, output, privacy risk, and verification method.
Prioritize tasks that can be grounded in local files or repo workflows.
```

### Turn A Messy Request Into A Codex Task

```text
Help me convert this request into a safe Codex task.
Request: [paste request].
Identify the source files needed, audience, privacy boundary, output format, verification steps, and what Codex should not assume.
```

### Pick The Right Level Of Help

```text
Given this task, classify it as summarize, structure, compare, verify, automate, or handoff.
Then propose a Codex prompt and a validation checklist.
```

## When Codex Should Slow Down

Ask Codex to pause or ask for authorization when the task involves:

- Live systems or websites not already approved for the workflow.
- Sensitive row-level details.
- People, identities, roles, or ownership decisions.
- Financial totals that mix different categories.
- Current status that could have changed.
- Tools or dependencies that are missing.
- Publication, policy, or operational claims that require authoritative evidence.

## What Trainees Should Practice

Each trainee should leave with at least three task ideas from their own work:

1. A low-risk summary task.
2. A recurring workflow or verification task.
3. A durable documentation or handoff task.
