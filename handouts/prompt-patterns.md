# Codex Prompt Patterns for Scientific Staff

## 1. Local Analysis

```text
Inspect [file/path]. Summarize the key findings for [audience].
Use [columns/fields] as evidence.
Group or filter by [rules].
Keep the output [aggregate-only/sanitized/internal].
List uncertainties and verification steps.
```

## 2. Snapshot Comparison

```text
Compare [new source] against [baseline source].
Tell me what new evidence we learn, not just what appears in both.
Be specific, but keep the output safe for [audience].
```

## 3. Scientific Software Inventory

```text
Rank scientific software by unique computers.
Collapse related products into families.
Exclude operating systems, office apps, browsers, security tools, management agents, and runtimes.
Use installs and usage signals separately if both exist.
```

## 4. Renewal or Budget Question

```text
Answer from the current model snapshot.
Separate true renewal/order items from one-time adjustments, discontinued items, and non-software costs.
Show the source artifact used and any assumptions.
```

## 5. Identity or Role Lookup

```text
Use the local cache first.
If not found, use the approved authoritative directory if available.
Use public web only as a fallback.
Keep unresolved or ambiguous identities explicit.
Do not overwrite current authoritative roles with historical user-reported notes.
```

## 6. Repo Workflow

```text
Inspect the repo docs and scripts first.
Use the existing workflow if present.
Run the verification steps.
Report exact commands, outputs, and remaining risks.
```

## 7. Handoff

```text
Create a restart note for a new thread.
Include goal, current state, files, commands, validation status, decisions, blockers, and next steps.
Keep it sanitized and operational.
```

## 8. Code Review

```text
Review this change for bugs, behavioral regressions, missing tests, and operational risk.
Lead with findings ordered by severity.
Include file and line references where possible.
```

