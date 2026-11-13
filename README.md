# Marketing Prompt Skill V1.3

Portable Markdown-based skill, designed to work without plugins or MCP servers. Use `SKILL.md` as the entrypoint and load referenced files on demand.

## V1.3 graphic-design extension

The optional `professions/marketing/workflows/graphic-design-fidelity.md` module covers graphic brief sufficiency, one-question clarification, visual communication standards, creative direction, official-brand-asset authenticity, professional pre-delivery critique, minimal-diff revisions and output inspection. It does not replace the general marketing workflow or require third-party design tools. Source selection is documented in `research/graphic-design-standards-audit.md`; eight controlled scenarios and a production rubric are in `tests/graphic-design-workflow-benchmarks.md`.

**Status:** V1.3 adopted as an iterative release at user request. The controlled five-turn edit test was reported as a tie, while the Christmas-poster creative comparison exposed weak design quality and unverified official marks in both versions. The three new capabilities are not yet independently validated. Do not claim V1.3 improves results until further tests establish that.

## Contents
- `core/`: scope, adaptive expertise, prompt coaching, integration policy, page-aware documents and proportional spreadsheets.
- `professions/marketing/`: domain rules, workflows and provisional foundations.
- `research/`: candidate source registry and campaign research template.
- `tests/`: 50 marketing benchmark prompts, 15 document/spreadsheet scenarios and scoring rubric.
- `research/uploaded-reference-audit.md`: attributed seven-book research index (no copyrighted PDFs committed).
- `professions/marketing/references/source-informed-principles.md`: selectively applied marketing theory and evidence limits.

## Installation
For an agent supporting folder-based skills, place this folder in its supported skills directory and ensure the entrypoint is discoverable. For manual use, provide `SKILL.md` as instructions and relevant reference files as needed. Exact installation depends on the host platform.

## Document and spreadsheet behaviour
A4 portrait is the default for ordinary print documents when no other size is indicated. Small-format inserts, tabletop displays and packaging may require A5/A6/A7 or custom dimensions. Branding is opt-in when relevant; never invent identity assets. Excel should stay simple unless analytics are requested or clearly necessary.

## Status
V1.2 baseline architecture and initial seven-book source synthesis implemented; source registry is not a legal clearance. Research claims require source-level validation; no live cross-model evaluation completed. Never imply benchmark success before tests are run.

## Next steps
Run the Christmas-poster scenario again with verified brand assets and score first-pass creative quality, logo fidelity and correction count. Continue testing revision preservation and general marketing workflows. Fix observed failures without silently broadening scope.
