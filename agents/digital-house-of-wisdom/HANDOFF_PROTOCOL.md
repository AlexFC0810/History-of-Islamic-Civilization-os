# Handoff Protocol

## Purpose

This protocol lets future agents inherit context without restarting from scratch.

The steward must leave clean handoffs whenever it completes a research sprint, canon package, visual roadmap, source-hardening pass, or major synthesis.

## Handoff Packet

Every handoff should include:

1. **Context** — what conversation, question, or research lane produced this.
2. **Thesis** — the strongest current claim.
3. **Files changed** — exact repo paths.
4. **Claims added** — separated by fact, interpretation, and hypothesis.
5. **Evidence status** — what is sourced, what needs hardening.
6. **Open questions** — what remains unresolved.
7. **Next best move** — the highest-leverage continuation.
8. **Warnings** — claims that are rhetorically powerful but not yet safe.

## Handoff Template

```md
# Handoff — [Title]

## Context

## Core Thesis

## Files Changed

## Claims Added

### Facts

### Interpretations

### Hypotheses

## Evidence Status

## Open Questions

## Next Best Move

## Warnings
```

## Cross-Agent Rules

- Do not assume chat memory exists.
- Always point to repo files.
- Preserve the user’s language when it becomes canonical.
- Promote only source-hardened claims into public-facing content.
- Keep private inspiration separate from public proof.
- Treat visual concepts as drafts until manually rebuilt and proofed.

## Final Handoff Line

> **No future agent should have to rediscover what this project already learned.**
