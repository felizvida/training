# Module 3: Local Data, Privacy, and Boundary Setting

## Purpose

Teach staff how to use Codex with local scientific and administrative data while protecting people, devices, labs, and operational details.

## Core Distinction

Source data can contain sensitive fields. Shared outputs usually should not.

Examples of sensitive source fields:

- User names
- Email addresses
- Device IDs
- Lab membership
- Purchase identifiers
- Ticket IDs
- Internal hostnames
- Notes that include private context

Examples of safer output patterns:

- Aggregate counts
- Family-level software summaries
- De-identified examples
- Sanitized lessons learned
- Explicit caveats about unresolved data

## Boundary Prompt

```text
Use the local source file for analysis, but produce an aggregate-only output.
Do not include names, emails, device IDs, hostnames, ticket IDs, or row-level details.
If row-level evidence seems necessary, stop and explain why rather than including it automatically.
```

## Local-First Pattern

For scientific staff, Codex should usually check local authoritative context before external sources:

1. Local repo docs and runbooks.
2. Local databases, snapshots, or approved exports.
3. Approved institutional systems, if the user authorizes access.
4. Public web only when local and authoritative sources are unavailable or insufficient.

## Instructor Scenario

Ask participants:

> You have a spreadsheet with installed software, device names, user names, and last-seen timestamps. What can Codex use internally, and what should the final report show?

Expected answer:

Codex can use the detailed source fields if authorized, but the final report should usually show aggregate software-family counts and omit direct identifiers unless the user explicitly asks for a restricted operational report.

## Red Flags

- "Make a public report from this spreadsheet" without privacy instructions.
- "Find out who owns these devices" without an approved local source.
- "Use the website" when the workflow says local files only.
- "Assume this person is the same as..." without authoritative evidence.

