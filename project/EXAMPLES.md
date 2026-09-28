# Health Project — Worked Examples

Golden transcripts showing how the orchestrator selects specialists, uses shared
files, and returns one coherent answer. Illustrative structure only — verdicts
and citations in real use must come from current sources checked at the time.

---

## Example 1 — "Create a three-day strength plan"

**User:** Use the Health agent team to create a three-day strength plan.

**Orchestrator (routing):**
- Reads `user-profile.md` (male, ~39–40, intermediate, full gym, 3 days/week).
- Selects: `strength-hypertrophy` (lead), `injury-aware-movement` (screen).
- No material claim to investigate → research analyst not needed.

**Injury-aware screen (`red-flags.md`):** No red flags reported; notes prior
left-knee niggle → suggests knee-friendly substitutions.

**Strength & Hypertrophy (`program-design.md`):** Returns a plan with
frequency, duration, intensity (RPE, units per `user-profile.md`), progression
and deload triggers, substitutions, measures, and a review date.

**Orchestrator (synthesis):** One plan, lead recommendation first, assumptions
marked (e.g. inferred protein intake), caveats, stop/escalation criteria.

---

## Example 2 — "I read creatine boosts testosterone. True?"

**User:** Men's Health says creatine boosts testosterone — should I take it?

**Orchestrator (routing):**
- Material media claim → `health-research-analyst` (lead) with `claim-appraisal.md`.
- `nutrition-body-composition` with `supplement-scorecard.md` for the practical call.

**Research analyst (`claim-appraisal.md`):** Frames PICO-T, traces the headline to
the underlying study, appraises totality, assigns a verdict with confidence and
dated citations. Labels unverifiable coverage as **unverified**.

**Nutrition (`supplement-scorecard.md`):** Scores creatine on effect size,
evidence, dose/form, safety, interactions, contamination, cost; gives a
food-first note and a bottom line.

**Orchestrator (synthesis):** Verdict + practical recommendation, confidence,
limitations, and escalation if any interaction applies.

---

## Example 3 — "I'm turning 40 — anything I should be doing?"

**User:** I'm about to turn 40. Anything health-wise I should get on top of?

**Orchestrator (routing):**
- Reads `user-profile.md` and `age-context.md`.
- Surfaces preventive-health **topics to verify** (cardiovascular risk,
  metabolic markers, sleep apnoea if symptomatic, mental health), explicitly
  deferring numbers/screening ages to current national guidance and a clinician.
- May involve `nutrition-body-composition` and `strength-hypertrophy` for the
  modifiable, in-remit actions (protein, resistance training for lean mass).

**Orchestrator (synthesis):** Clear split between "raise with your GP / verify
against current guidance" and "things this team can help you action now." States
it is educational and not a screening schedule.
