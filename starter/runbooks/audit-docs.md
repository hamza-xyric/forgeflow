# Forgeflow Runbook: Audit Docs

## Required Context

- Root `AGENTS.md`, `CLAUDE.md`, founding brief, source hierarchy, and active vs archived source list.
- Progress, findings, deferred decisions, accepted improvements, and handoff.
- Current file map from `rg --files`.

## Steps

1. Identify active operational docs and archived/historical docs.
2. Check for contradictions across source hierarchy, active root, current phase, verification commands, lane rules, and next step.
3. Search for stale references to archived sources, old handoff paths, missing evidence, placeholders, generic instructions, and multiple active next steps.
4. Record findings with owner, severity, blocked work, next action, and closure condition.
5. Recommend doc updates only after naming the source of truth that wins.

## Expected Output

- A docs audit report or ledger update that distinguishes stale docs from live truth.

## Quality Bar

- Findings cite exact files and lines or sections.
- The audit does not treat historical prompts as active truth unless explicitly marked active.
- The report separates deterministic failures from recommended improvements.

## Persistence / Closeout

- Append findings and deferred decisions to the correct ledgers.
- Update `plans/next-session-handoff.md` if doc drift changes next-session safety.

## Stop Conditions

- Stop before editing if the source hierarchy cannot decide which doc wins.
- Stop if a doc appears active but contradicts live implementation and no owner can resolve it.
