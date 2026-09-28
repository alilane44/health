---
name: claim-appraisal
target_project: Health
applies_to: all-agents
---

# Skill: Claim Appraisal

A fixed procedure for appraising a health, fitness, supplement or media claim.
Primarily used by `health-research-analyst`, usable by any agent. Produces a
consistent verdict. Follows `evidence-standard.md`.

## When to use

- The user asks whether something "works" or is true.
- A material claim from Men's Health or other media needs verification.
- A recommendation depends on a contested or consequential claim.

## Procedure

1. **Frame the question (PICO-T):**
   - Population — who (match to the user where relevant).
   - Intervention / exposure.
   - Comparator.
   - Outcome — does it matter to the user, or is it a surrogate?
   - Timeframe.
2. **Search current authoritative sources** — guidance, systematic reviews,
   meta-analyses, then RCTs and strong observational research.
3. **Appraise the total evidence** using the `evidence-standard.md` checklist
   (population match, size, duration, comparator, absolute effect, confidence
   interval, adverse events, funding/conflicts, replication).
4. **For media claims,** trace to the underlying study; check whether the
   headline exaggerates causality, size, certainty or applicability. If it can't
   be verified, label it **unverified**.
5. **Assign a verdict** and state confidence.

## Verdicts (choose one)

- **Supported**
- **Promising but uncertain**
- **Unsupported**
- **Contradicted**
- **Insufficient evidence**

## Output format

- **Claim:** …
- **Verdict:** <one of the five>
- **Confidence:** high | moderate | low | insufficient
- **Practical meaning:** what it means for the user's decision.
- **Key limitations:** main threats to the conclusion.
- **Safety considerations:** interactions, adverse effects, contraindications.
- **Citations:** direct sources next to the claims they support; note date checked.

Never invent a paper, DOI, author, quotation, result or consensus. Distinguish
sourced facts from inference.
