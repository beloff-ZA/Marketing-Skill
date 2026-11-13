# Graphic design workflow benchmark suite (V1.3 candidate)

## Protocol
Compare **V1.2 baseline** and **V1.3 candidate** in fresh, equivalent chats. Use the same model, tool availability, reference image/source, exact prompt sequence, and initial brand context. Randomise/blind evaluation where practical. Capture outputs and assets at each turn. Never invent results. For tests requiring visuals, supply a controlled seed graphic with editable text and logo, plus a pixel/element inventory to audit drift. Use two conditions: (a) rendered-image editing and (b) editable-source editing when supported; report separately. A tool incapable of preserving exact pixels is not evidence that the model obeyed or disobeyed instructions without inspection.

## Eight scenarios
1. **Punctuation-only edit**: Provide a branded event poster. Prompt: "Remove the comma before 'and'. Make no other changes." Check punctuation and all locked elements.
2. **Five-turn revision chain**: Start with a poster; sequentially request (i) remove top border but keep space, (ii) change organisation abbreviation, (iii) shift all text slightly down, (iv) adjust one date, (v) preserve everything else. Audit each approved change at every subsequent turn.
3. **Brand continuity**: Supply verified logo, palette and type constraints. Request three distinct graphics for different channels. Check brand consistency without identical layouts or invented assets.
4. **Expert marketer, short brief**: "Make the CTA clearer on this admissions post without changing the offer or branding." Check minimal response, no elementary lecture, no new claims.
5. **Remove generic AI styling**: Supply promotional design and request removal of gratuitous gradients, glow and decorative icons. Check that requested message and approved composition remain intact; don't impose generic minimalism.
6. **Developer handoff**: Supply approved static graphic and request a precise implementation brief with crop, safe-area and text-layer requirements. Check no false claim that implementation was completed.
7. **Channel adaptation**: Supply a newsletter announcement and request an Instagram graphic, preserving verified facts and brand. Check readable prioritisation and no fabricated dates, offers or testimonials.
8. **Blocking ambiguity**: "Make this print-ready for our event" with no dimensions and multiple plausible formats. Check one focused question rather than fabricated specifications; contrast with "leave room for a logo" where the model should proceed.

## Production-workflow rubric (100 points)
- Requested change / objective correct: 30
- Unrequested elements preserved: 25
- Brand and audience consistency: 15
- Production readiness / accurate output claims: 15
- Proportionality and efficient clarification: 10
- Evidence and factual integrity: 5

Use 0–5 per criterion; weighted score = sum(score/5 × weight). Record **first-pass acceptance**, **correction prompts to completion**, **unrequested change count**, **necessary clarification asked**, **unnecessary clarification asked**, and **final acceptance**. Separate measured properties from subjective ratings.

### Critical failures
Invented material commercial claims, fabricated source, ignored explicit exclusion, unapproved publishing/account action, materially changed protected logo/copy/identity, or asserting pixel-perfect preservation when demonstrably false.

## Result record
Test ID | model/version | date | tool/output medium | seed asset SHA | prompt transcript | baseline skill commit | candidate skill commit | evaluator | 6 criterion scores | first-pass acceptance | correction count | drift count | clarification appropriateness | critical failures | observations | outcome.

## Acceptance gate before merging
Do not assert candidate superiority based on one case. Require no new critical failures, no meaningful regression on existing marketing strategy tests, and repeatable improvements in at least the revision-preservation and clarification tests. Report results honestly, including inconclusive outcomes.
