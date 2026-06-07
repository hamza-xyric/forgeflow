# Reviewer Personas (Audit Team)

Each file is **one reviewer persona = one risk lens** (FRAMEWORK.md Verify (A6)). Personas are audit-only by default: they surface evidence-backed findings, blockers, and recommendations; they do not edit.

The six here are generalized from a UI/UX build. Rename or retarget them to your domain's real risk lenses, but keep this contract in every persona:

- Mission.
- Review focus.
- Evidence required.
- Output format.
- What this role can block.
- What this role cannot decide alone.

| Persona file | The lens | Non-UI analogue |
|--------------|----------|-----------------|
| `strategist.md` | does this make sense / belong here? | product/architecture fit |
| `competitive.md` | is it best-in-class? | prior-art / benchmark |
| `content-trust.md` | clear, honest, safe? | docs clarity / security / privacy |
| `brand-guardian.md` | consistent and on-system? | API/style consistency |
| `interaction-qa.md` | does it work mechanically? | correctness / operability QA |
| `release-readiness.md` | is the build true? | CI/build verification sign-off |

All personas share one finding format: ID, status, severity, finding, evidence/source, owner, blocked work, next action, closure condition.
