# Unit 6: Identity, Roles, And Uncertainty

Time: 1 hour

Navigation: [Track home](README.md) | Previous: [Unit 5](unit-05-workflows-status-verification.md) | Next: [Unit 7](unit-07-handoffs-lessons-repo-stewardship.md)

Portfolio section: Unit 6

## Goal

Practice answering identity or role questions without forcing weak matches.

## Anchored Experience

This unit models local-first identity resolution: use local cache evidence first, keep historical notes separate from current fields, and mark unresolved or ambiguous records explicitly.

## Why This Matters

People and roles deserve careful handling. This unit teaches you to resist the tempting but dangerous move of forcing a match when the evidence is weak.

## Materials

- [../data/identity_lookup_samples.csv](../data/identity_lookup_samples.csv)
- [../exercises/exercise-03-identity-lookup.md](../exercises/exercise-03-identity-lookup.md)
- [../assessment/instructor-answer-key.md](../assessment/instructor-answer-key.md)

Use the answer key only after drafting your own role-resolution answer.

## 60-Minute Plan

| Time | Activity |
| --- | --- |
| 0-10 min | Inspect the identity sample columns |
| 10-20 min | Identify current, historical, ambiguous, and unresolved records |
| 20-40 min | Draft or run the role-resolution prompt |
| 40-50 min | Compare to answer key |
| 50-60 min | Save answer and uncertainty notes |

## Starter Prompt

```text
Inspect data/identity_lookup_samples.csv.
Answer who appears responsible for each listed function using local current fields first.
Keep historical notes separate from current roles.
Mark ambiguous or unresolved records explicitly.
Do not invent public-web evidence or force weak matches.
```

## Deliverable

A role-resolution table with:

- Function.
- Current responsible party if supported.
- Evidence field.
- Caveat or unresolved status.

## Finish Line

You are done when your answer is useful without pretending to know more than the source supports. The satisfying result is a table that is both helpful and honest.

## Self-Check

- Did you use local current evidence first?
- Did you keep history separate from current role?
- Did you avoid forcing ambiguous aliases?
- Did you explicitly mark unresolved cases?
