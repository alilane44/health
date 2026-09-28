---
name: supplement-scorecard
target_project: Health
applies_to: all-agents
---

# Skill: Supplement Scorecard

A consistent way to evaluate a supplement. Primarily used by
`nutrition-body-composition`, usable by any agent. Follows `evidence-standard.md`
and the safety rules in `safety-boundaries.md` and `red-flags.md`.

## When to use

- The user asks whether to take a supplement, or which to choose.
- A supplement appears in a plan or a media claim.

## Evaluate on every axis

- **Effect size** — how large is the benefit for a relevant outcome?
- **Evidence quality** — per the source hierarchy; totality, not one study.
- **Dose and form** — effective dose, timing, bioavailable form.
- **Safety / adverse effects** — known risks and at what dose.
- **Interactions** — with medications, conditions or other supplements.
- **Contamination risk** — third-party testing; regulated vs unregulated market.
- **Cost** — value relative to effect and to food-first alternatives.

## Output format

| Supplement | Effect size | Evidence | Dose/form | Safety | Interactions | Contamination | Cost | Verdict |
|-----------|-------------|----------|-----------|--------|--------------|---------------|------|---------|
| Example | Small | Moderate | … | … | … | Prefer tested | £ | Optional |

Follow with:

- **Bottom line:** worth it / situational / not worth it, and why.
- **Food-first alternative** where one exists.
- **Escalation:** flag interactions or conditions needing a pharmacist/clinician.
- **Citations:** direct sources; note date checked.

Do not provide medical nutrition therapy. Never invent evidence or imply access
to a study that was not inspected.
