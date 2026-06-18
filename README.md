# Codex Training Package for Scientific Staff

This package trains scientific staff to use Codex as a careful local collaborator for analysis, documentation, troubleshooting, and repo-aware workflows.

It is based on recurring usage patterns from operational scientific work:

- Start from local files, repo docs, and known runbooks before searching elsewhere.
- Ask Codex for source-grounded summaries, not generic restatements.
- Keep privacy boundaries explicit: source files may contain sensitive detail, but shared outputs should usually be aggregate or sanitized.
- Treat workflows as reproducible systems with inputs, commands, checks, outputs, and restart notes.
- Verify claims with commands, tests, scripts, screenshots, or cited artifacts before reporting them as done.
- Preserve uncertainty when identities, roles, ownership, or current status cannot be resolved cleanly.

## Audience

Scientific staff, lab managers, data stewards, analysts, informatics staff, scientific program staff, and research-support teams who work with local files, spreadsheets, scientific software inventories, documentation, or lightweight code repositories.

No programming background is required for the introductory track. The half-day track includes optional command-line and repo exercises.

## Recommended Formats

### 60-minute lunch-and-learn

Use:

- [curriculum/00-facilitator-guide.md](curriculum/00-facilitator-guide.md)
- [curriculum/01-codex-operating-model.md](curriculum/01-codex-operating-model.md)
- [curriculum/06-task-idea-gallery.md](curriculum/06-task-idea-gallery.md)
- [handouts/task-idea-catalog.md](handouts/task-idea-catalog.md)
- [handouts/prompt-patterns.md](handouts/prompt-patterns.md)
- [handouts/privacy-and-verification-checklist.md](handouts/privacy-and-verification-checklist.md)
- [exercises/exercise-01-scientific-inventory.md](exercises/exercise-01-scientific-inventory.md)

### Half-day workshop

Use the full package:

- Operating model
- Source-grounded analysis
- Local data and privacy
- Repo workflows and verification
- Task idea gallery and task triage
- Communication, handoffs, and lessons learned
- Five practical exercises plus a capstone
- Assessment rubric

### 8-hour self-paced tutorial

Use:

- [self_paced/README.md](self_paced/README.md)
- [self_paced/learner-guide.md](self_paced/learner-guide.md)
- [self_paced/portfolio-template.md](self_paced/portfolio-template.md)
- [self_paced/completion-checklist.md](self_paced/completion-checklist.md)

This modality is self-sustained: each of the eight units is designed for one hour and includes goals, materials, pacing, starter prompts, deliverables, and self-checks.

### Train-the-trainer session

Use:

- [curriculum/00-facilitator-guide.md](curriculum/00-facilitator-guide.md)
- [slides/workshop-deck-outline.md](slides/workshop-deck-outline.md)
- [assessment/rubric.md](assessment/rubric.md)
- [templates/verification-log-template.md](templates/verification-log-template.md)

## Package Map

| Path | Purpose |
| --- | --- |
| [curriculum/](curriculum) | Instructor-facing lesson plans |
| [exercises/](exercises) | Hands-on staff activities |
| [handouts/](handouts) | Participant quick references |
| [self_paced/](self_paced) | Complete 8-unit self-paced tutorial |
| [templates/](templates) | Reusable work products |
| [data/](data) | Synthetic practice data |
| [assessment/](assessment) | Evaluation rubric and capstone criteria |
| [slides/](slides) | Slide outline for building a deck |

## Facilitation Principles

Teach Codex as a thinking partner with a paper trail. The best staff workflows sound like:

1. "Here is the local context and what matters."
2. "Inspect the files and tell me what you are using as evidence."
3. "Produce a concise, shareable output with privacy boundaries intact."
4. "Run the repo's verification steps."
5. "Leave a restart note so another person can continue."

The point is not to make staff memorize commands. The point is to help them ask for work in a way that produces inspectable, reproducible, and scientifically useful results.

## Task-Idea Emphasis

Trainees should leave with a concrete sense of what Codex can help with in their own work. Use [handouts/task-idea-catalog.md](handouts/task-idea-catalog.md) and [exercises/exercise-05-task-triage.md](exercises/exercise-05-task-triage.md) to move beyond generic writing prompts into practical workflows anchored on the package owner's experience: scientific software summaries, snapshot comparisons, renewal planning, local data refreshes, workflow status checks, identity-resolution caveats, app and test improvements, restart handoffs, sanitized lessons learned, and the ongoing maintenance of this training repository itself. Brief staff/researcher examples are included for context only.
