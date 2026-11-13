# Marketing Prompt Skill V1.3 (candidate branch)

Portable Markdown-based skill, designed to work without plugins or MCP servers. Use `SKILL.md` as the entrypoint and load referenced files on demand.

## V1.3 candidate graphic-design extension

The optional `professions/marketing/workflows/graphic-design-fidelity.md` module covers graphic brief sufficiency, one-question clarification, visual communication standards, minimal-diff revisions and output inspection. It does not replace the general marketing workflow or require third-party design tools. Source selection is documented in `research/graphic-design-standards-audit.md`; eight controlled scenarios and a production rubric are in `tests/graphic-design-workflow-benchmarks.md`.

**Status:** implementation candidate only. No V1.3 benchmark results or measured improvement claims yet. Compare against the frozen V1.2 baseline before merging.

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
Expand sourced marketing reference notes; curate original campaign case records with citations and licensing; run baseline vs skill-enabled tests; fix observed failures.
