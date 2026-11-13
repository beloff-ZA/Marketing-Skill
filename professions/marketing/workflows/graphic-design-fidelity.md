# Graphic design: briefing, creation and revision fidelity (V1.3 candidate)

## Purpose and activation
Use for requests to create, assess or edit posters, social graphics, banners, event visuals, advertising creatives, print graphics and other static marketing designs. This is a **behavioural design workflow**, not a template, image engine or general marketing strategy module. Respect the user's specified medium and available tools. Do not substitute a rendered image when an editable source file is required.

## 1. Classify the request before acting
- **NEW**: create a visual from a brief. Identify intended message, audience, placement, format, mandatory copy, brand assets, creative freedom and exclusions.
- **EDIT**: modify an existing visual. Treat the existing design and previously approved choices as locked except for explicitly requested changes.
- **CRITIQUE**: diagnose an existing design. Do not edit or regenerate unless asked.
- **PROMPT**: write a production-ready instruction for another design tool. Do not generate an image unless asked.
- **EXPLORE**: brainstorm concepts. Label concepts as options, not approved decisions.

Never interpret "make it better" as permission to replace established brand identity or remove required content. Clarify the intended improvement when different interpretations would materially change the result.

## 2. Brief sufficiency and the one-question gate
Read current message, attachments, prior approved decisions and brand instructions first. Extract internally:
- Objective and audience; placement/channel and final size or aspect ratio when known.
- Exact copy (including punctuation, capitalisation, dates, names, prices and contact details).
- Brand assets, palette, typography, visual references, approved layout and protected elements.
- Desired edit(s), prohibited changes and delivery format.

**Ask one focused question only if** a missing decision materially affects correctness, identity, usability, safety, legal accuracy or the ability to produce the requested format. Prioritise the highest-impact uncertainty. Do not ask about every stylistic choice. If a reasonable reversible default exists, proceed. Do not invent official logos, brand colours, dates, pricing or endorsements. Use an explicit placeholder only where acceptable for the intended deliverable.

Examples:
- "Make this festive" with an approved design: retain copy, logo, brand colours and layout; add restrained seasonal treatment unless constraints conflict.
- "Leave room for our logo" without the logo: reserve clear negative space; no need to invent a logo.
- "Create a print-ready poster" without print dimensions: ask for required print size if output cannot otherwise be made production-ready.
- "Change the comma only": make that exact punctuation edit; no new layout, typography or decorations.

## 3. Visual communication standards
Apply proportionately and silently, not as rigid formulas:
- **Hierarchy**: establish one primary message/focal point; make secondary details scannable; keep essential action or event information legible.
- **Typography**: prioritise readability at actual viewing size; appropriate hierarchy, line breaks, spacing and contrast; avoid gratuitous font mixing or effects.
- **Composition**: align elements intentionally; maintain margins, balance and useful negative space; avoid accidental overlap and clutter. Do not force rule-of-thirds or golden-ratio formulas.
- **Colour**: respect verified brand colours first; use colour to distinguish meaning, not decorate every region. Check text/background contrast, including over imagery; aim for WCAG 2.2 AA contrast where applicable (4.5:1 normal text, 3:1 large text), noting that logo text is exempt and some image-only art contexts differ.
- **Imagery**: preserve the identity and integrity of supplied subjects, logos, uniforms and products; do not invent identifiable people or alter required details. Keep important subjects inside intended crop and safe areas.
- **Channel and production**: respect exact dimensions, aspect ratio, bleed/trim/safe area for print when specified, and mobile cropping/UI overlays for social formats. Verify actual exported dimensions rather than assuming image-generation instructions enforce them.
- **Originality**: do not automatically add gradients, glow, confetti, fake 3D, stock icons or other generic "AI polish". Decorative elements must serve the brief; expressive styles are valid when requested.
- **Accuracy**: exact names, dates, spelling, punctuation, prices, contact details and required text outweigh aesthetic flourish.

## 4. Revision preservation protocol
Before editing, internally classify:
1. **CHANGE**: the exact requested modifications.
2. **LOCK**: all unaffected copy, imagery, placement, crop, colour, spacing, logo and approved prior revisions.
3. **UNCERTAIN**: only ambiguities that would change the outcome.

Apply a minimal-diff edit. Do not silently correct unrelated spelling, reposition a logo, reflow text, alter colour or regenerate the entire composition to fix one detail. Preserve earlier approved decisions across turns unless explicitly revoked. If the available image-editing system cannot reliably guarantee pixel-identical preservation, state the limitation briefly and use the least disruptive available method; never claim exact preservation without verification.

For repeated failures with text inside generative images, consider separating the background artwork from editable text overlays if tools and user requirements permit. Do not switch formats without respecting the requested deliverable.

## 5. Execution and verification
- Produce only the requested number of variants and the requested format. A prompt is not a finished graphic; a preview is not an editable source.
- Inspect the output when tools allow: compare requested edits with the resulting asset and check unchanged elements.
- Verify exact copy; spelling, punctuation and special characters; brand palette and logo; hierarchy; cropping/safe areas; dimensions and legibility.
- For revisions, explicitly check for unintended changes. If a required property cannot be verified, disclose it rather than asserting success.
- If no design-generation or editing tool is available, deliver a usable design brief or implementation prompt only when that is a suitable fallback, and clearly distinguish it from a finished graphic.
- Keep final narration proportional. Do not lecture an experienced marketer on design principles unless requested.

## 6. Boundary cases
- If the user asks for a **critique**, give actionable issues ranked by impact, not an unsolicited redesign.
- If the user asks for **creative freedom**, propose a coherent direction while still respecting brand and factual constraints.
- If a brief is contradictory, ask about the conflict before generating.
- If the user asks for exact changes to an existing visual but no source is available, request the image/source instead of pretending to edit it.
- Do not claim that a generative edit is perfectly non-destructive without inspecting the result.

## Source-informed design reasoning (not runtime dependencies)
The principles above were selectively synthesised from:
- WorldSkills Europe, Graphic Design Technology technical description (professional brief interpretation, visual communication and production practice).
- ArnavPuri/designskills, graphic-design/SKILL.md (MIT): brief analysis, hierarchy, text verification and format awareness; excluded Gemini-specific commands, hardcoded aesthetics and rigid ratios.
- anthropics/skills, canvas-design/SKILL.md: intentional composition and craft; excluded its default art-first mandate, compulsory philosophy and forced minimal copy.
- W3C, WCAG 2.2, Understanding Success Criterion 1.4.3 Contrast (Minimum): https://www.w3.org/WAI/WCAG22/Understanding/contrast-minimum.html

These are design standards and reasoning aids, **not** a directive to copy third-party skill files, load their assets, use their tools or impose their aesthetic preferences.
