# Privacy and Verification Checklist

Use this before sharing a Codex-generated output.

## Privacy

- [ ] Did the source data contain names, emails, device IDs, hostnames, ticket IDs, lab membership, or notes?
- [ ] Does the output omit row-level identifiers unless explicitly required?
- [ ] Are examples de-identified or synthetic?
- [ ] Are uncertain people, labs, roles, or ownership records labeled as unresolved or ambiguous?
- [ ] Are historical/user-reported facts separated from current authoritative facts?
- [ ] Are secrets, passwords, tokens, and private notes excluded?

## Source Boundary

- [ ] Did Codex use local files or repo docs first?
- [ ] Did Codex avoid unauthorized websites or live systems?
- [ ] Did Codex state which source files, tables, columns, scripts, or outputs it used?
- [ ] Did Codex distinguish install evidence, observation evidence, and usage evidence?

## Verification

- [ ] Did Codex run the relevant tests, checks, scripts, or manual inspection?
- [ ] Are exact commands recorded?
- [ ] Are output files and important paths recorded?
- [ ] Are failures described as failures, not treated as missing evidence?
- [ ] Does the final answer separate completed work from remaining risk?

## Shareability

- [ ] Is the output understandable without the full raw dataset?
- [ ] Is the artifact concise enough for the intended audience?
- [ ] Could another staff member reproduce the result from the note?
- [ ] Is the answer framed as current only if current evidence was actually checked?

