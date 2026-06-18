# Codex Memory And Skills Resource

Use this handout when a learner asks, "Where does Codex remember things, and should that become part of training?"

Short answer: teach the concept, not the raw files. Codex memory and skills can help explain how durable context and reusable workflows work, but raw memory files may contain private project paths, session summaries, people references, device details, operational notes, or other context that does not belong in a public training repository.

## What Is Saved Where

Codex stores durable local context under the user's Codex home. In a typical local setup, that is:

| Area | Typical location | What it means |
| --- | --- | --- |
| Memory summary | `$HOME/.codex/memories/memory_summary.md` | Compact routing summary for prior work patterns |
| Memory registry | `$HOME/.codex/memories/MEMORY.md` | Searchable index of durable memory topics |
| Rollout summaries | `$HOME/.codex/memories/rollout_summaries/` | Per-session recaps and evidence snippets |
| Memory-backed skill notes | `$HOME/.codex/memories/skills/` | Learned guidance connected to recurring workflows |
| User skills | `$HOME/.codex/skills/` | Locally installed reusable instructions or workflows |
| System skills | `$HOME/.codex/skills/.system/` | Built-in Codex skills supplied by the environment |
| Plugin skills | `$HOME/.codex/plugins/cache/` | Skills and tools installed through plugins |

Exact paths vary by installation. Use `$HOME` in training materials instead of a personal workstation path.

## Memory Versus Skills

| Concept | Use it for | Do not treat it as |
| --- | --- | --- |
| Memory | Prior project context, preferences, recurring patterns, handoff hints | A current source of truth |
| Skills | Reusable procedures, tool instructions, domain workflows, quality checks | A substitute for user judgment or verification |

Memory helps Codex remember how the user tends to work. Skills help Codex perform a type of work consistently. Both still need current evidence, privacy boundaries, and verification.

## Should This Be A Training Resource?

Yes, but only as a sanitized resource.

Good training use:

- Explain that durable context can make Codex more useful across projects.
- Show how recurring workflows can become reusable skills or checklists.
- Teach learners to ask Codex what it is relying on before accepting an answer.
- Convert one prior workflow into a sanitized training pattern.
- Reinforce that memory is a guide, not evidence.

Avoid:

- Publishing raw memory files.
- Publishing raw skill files that contain private paths, endpoints, credentials, internal systems, or staff-specific procedures.
- Treating remembered facts as current without checking local files, repo docs, databases, workflow runs, or authoritative systems.
- Copying session transcripts into public training materials.

## Shareability Rule

| Material | Public training repo? | Better approach |
| --- | --- | --- |
| Raw memory files | No | Summarize patterns in neutral language |
| Raw rollout summaries | No | Extract only sanitized lessons learned |
| Personal workstation paths | Usually no | Replace with `$HOME` or `[local repo]` |
| Workflow commands | Sometimes | Include only commands safe for the training scenario |
| Private names, emails, hostnames, devices, tickets | No | Replace with synthetic examples |
| Skill concepts | Yes | Turn into checklists or prompt recipes |
| Verification habits | Yes | Include commands, checks, and evidence standards |

## Training Activity: Turn Memory Into A Safe Pattern

Goal: help learners convert prior experience into a reusable Codex task without exposing private context.

Steps:

1. Pick one prior work pattern, such as a renewal answer, inventory summary, workflow status report, identity lookup, or handoff.
2. Write a one-paragraph sanitized description of the pattern.
3. Name the source boundary: local files, repo docs, approved database, workflow logs, or synthetic data.
4. Name the privacy boundary: aggregate-only, sanitized, internal, or restricted.
5. Write a reusable prompt.
6. Add a verification checklist.

Starter prompt:

```text
Turn this prior workflow into a GitHub-safe training pattern.
Keep the useful task shape, but remove private names, emails, hostnames, device IDs, ticket numbers, secrets, unpublished details, and personal workstation paths.
Output a short scenario, a Codex starter prompt, privacy boundary, source boundary, and verification checklist.
Treat memory as background context, not as current evidence.
```

## Starter Prompt For A Skill-Like Checklist

```text
Create a reusable checklist from this sanitized workflow.
The checklist should tell a future Codex session what to inspect, what to avoid assuming, what privacy boundary applies, what output to produce, and how to verify the result.
Do not include raw private context.
```

## Self-Check

- Does the resource teach the workflow without exposing raw memory?
- Are exact personal paths replaced with `$HOME` or neutral tokens?
- Are real people, devices, tickets, and private systems removed?
- Does the prompt tell Codex to inspect current evidence?
- Does the output include a verification method?

## Takeaway

Memory and skills are useful because they turn repeated work into reusable habits. For training, the safest version is a sanitized pattern: what the task is, what evidence to use, what privacy boundary applies, and how to know the result is trustworthy.
