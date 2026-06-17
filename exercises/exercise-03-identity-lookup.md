# Exercise 3: Identity and Role Resolution

## Scenario

A staff member asks, "Who is responsible for this scientific support function?" The available file is a synthetic local cache with current records, historical notes, and ambiguous names.

Source:

- [../data/identity_lookup_samples.csv](../data/identity_lookup_samples.csv)

## Goal

Produce a careful, human-readable answer that preserves uncertainty.

## Instructions For Participants

Ask Codex to:

1. Check the local cache first.
2. Separate current authoritative fields from historical or user-reported notes.
3. Avoid forcing weak matches.
4. Mark unresolved or ambiguous records clearly.
5. Produce a concise answer suitable for internal staff use.

## Starter Prompt

```text
Inspect data/identity_lookup_samples.csv.
Answer who currently appears responsible for the listed scientific support functions.
Use local authoritative fields first, keep historical notes separate, and mark ambiguous or unresolved records instead of forcing a match.
Do not invent public-web evidence.
```

## Expected Output Shape

| Function | Current responsible party | Evidence | Caveat |
| --- | --- | --- | --- |
| Example function | Example Person | Local current role field | Historical note differs |

## Debrief

- Did Codex separate current and historical facts?
- Did it keep unresolved identities explicit?
- Did it avoid using public-web guesses?
- Did it explain what local field supported the answer?

