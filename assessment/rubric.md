# Assessment Rubric

Use this rubric for exercises or a capstone task.

| Criterion | Excellent | Developing | Needs Work |
| --- | --- | --- | --- |
| Task framing | Names source, audience, output, constraints, and verification | Names source and output but misses some constraints | Vague prompt with unclear goal |
| Source grounding | Identifies files, columns, scripts, or outputs used | Mentions source file only | Makes claims without evidence |
| Privacy | Keeps output sanitized or aggregate-only and states boundary | Avoids obvious identifiers but omits boundary | Leaks row-level or sensitive details |
| Analytical judgment | Uses grouping, filtering, and caveats appropriate to the question | Basic summary with limited interpretation | Raw dump or misleading totals |
| Verification | Runs or requests relevant checks and records results | Mentions verification but lacks detail | No verification |
| Uncertainty | Preserves ambiguous or unresolved records | Some uncertainty noted | Forces unsupported certainty |
| Handoff quality | Includes goal, state, paths, commands, outputs, checks, and next steps | Includes summary but misses reproducibility details | Cannot be resumed by another person |

## Capstone Prompt

```text
Use the synthetic data in this package to complete one scientific-support task.
Inspect the source file, produce a concise staff-facing output, keep privacy boundaries intact, verify your work, and write a short restart note.
```

## Passing Standard

A participant passes if another person can understand:

- What was asked.
- What evidence was used.
- What output was produced.
- What privacy boundary was applied.
- What was verified.
- What remains uncertain.

