# Persona benchmark execution plan

Status: STRUCTURAL PREFLIGHT PASSED; LIVE MODEL EVALUATION NOT RUN.

## Dataset
40 persona scenarios, 10 each:
1. Marketing professional (2-5 years) with minimal AI experience.
2. Marketing assistant (1 year) using AI without prompt-engineering knowledge.
3. Advanced marketer and AI user unfamiliar with reusable skill architecture.
4. Experienced marketer expecting search-engine-like or impossible AI outcomes.

A machine-readable dataset was generated during the 2026-11-13 session. Do not treat the persona descriptions as evidence of any real person's competence.

## Run protocol
1. Use the same model/version, temperature, tools, date and input for baseline and skill-enabled runs.
2. Use independent sessions to prevent answer leakage.
3. Baseline: standard system instructions only. Skill: same system instructions plus the current SKILL.md and relevant lazy-loaded references.
4. Run each prompt once per condition; repeat a representative sample 3 times to measure variability.
5. Store raw outputs, model and configuration metadata, references loaded, timestamps and token costs.
6. Score blind to condition using tests/evaluation-rubric.md; record critical failures separately.
7. Some prompts intentionally omit documents or data. Correct clarification is a PASS, not a failure to produce an artifact.
8. For document/spreadsheet cases, inspect actual artifacts, print dimensions, formula correctness and legibility; prose claims are insufficient.
9. Compare paired results by persona and by criterion, with both improvements and regressions visible.
10. Never report simulated or rule-based checks as live model performance.

## Release gate
Proposed, not yet achieved: >=85/100 mean skill score, >=10 percentage-point lift, >=95% scope adherence, zero critical fabricated evidence, >=90% usable artifacts.

## Current verified preflight
- 40 test cases present
- 10 cases in each of four personas
- Unique test IDs
- Nonempty prompts
- Acceptance criteria supplied
- Critical checks supplied
All six structural checks passed. This does NOT validate skill performance.

## Blocker
No configured model-execution API was available in the testing environment on 2026-11-13. A live baseline-versus-skill comparison requires an authorised model execution route or user-provided API configuration. Never commit API keys to GitHub.
