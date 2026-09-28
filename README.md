# Health Agent Team

An evidence-led team of Markdown agents designed for the ChatGPT Project **Health**.

Focused on accurate, up-to-date, practical health and fitness information, with
framing aimed at men in their late thirties and forties.

## Team

| Agent | Role |
| --- | --- |
| `health-orchestrator.md` | Front door: routes questions and combines advice |
| `strength-hypertrophy.md` | Strength, muscle, programming and progression |
| `cardio-conditioning.md` | Aerobic fitness, intervals and sport conditioning |
| `nutrition-body-composition.md` | Nutrition, fat loss, muscle gain and supplements |
| `sleep-recovery.md` | Sleep, fatigue, stress and readiness |
| `injury-aware-movement.md` | Exercise adaptation and return-to-training support |
| `health-research-analyst.md` | Appraises studies, headlines and health claims |

## Shared context (`shared/`)

| File | Purpose |
| --- | --- |
| `evidence-standard.md` | Source hierarchy, appraisal checklist, recency/citation convention |
| `safety-boundaries.md` | Scope limits and when to seek professional care |
| `red-flags.md` | Consolidated escalation checklist (all agents screen against this) |
| `user-profile.md` | Personal baseline so agents personalise from turn one |
| `age-context.md` | Preventive-health topics relevant for men approaching/in their forties (topics to verify, not fixed numbers) |

## Skills (`skills/`)

| File | Purpose |
| --- | --- |
| `claim-appraisal.md` | PICO-T framing and the five-verdict appraisal procedure |
| `supplement-scorecard.md` | Seven-axis supplement evaluation |
| `program-design.md` | Required contents for any training or activity plan |

## Add to the ChatGPT Project

1. Open or create the ChatGPT Project named **Health**.
2. Add the contents of `project/PROJECT_INSTRUCTIONS.md` to the Project instructions.
3. Upload the Markdown files in `agents/`, `shared/` and `skills/` as Project files.
4. Fill in `shared/user-profile.md` with your baseline before first use.
5. Start requests with the orchestrator, for example: “Use the Health agent team to create a three-day strength plan.”

ChatGPT Projects do not provide a repository-name pointer that Markdown can activate. The files use `target_project: Health` as human-readable metadata; uploading them to the Health Project provides the actual shared context.

## Principles

- Research before rhetoric.
- Practical advice before marginal optimisation.
- Direct citations for consequential claims, with the date checked.
- Men’s Health for accessible framing and ideas, never as the scientific endpoint.
- Clear uncertainty and medical escalation boundaries.
- Defer screening ages, clinical thresholds and doses to current national
  guidance verified at the time of advice — never asserted from memory.

This repository is educational and does not replace personalised medical care.
