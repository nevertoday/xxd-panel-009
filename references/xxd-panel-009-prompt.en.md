# XXD Panel 009 | Minimal Halftone Spatial Print Production Prompt

## Runtime complete-canvas contract — highest priority

- `TOP_BOTTOM` and `LEFT_RIGHT` default to one complete finished generation using the current source as a high-fidelity edit/reference input. Do not pre-split the job into photographic and design halves.
- Top-bottom keeps the faithful source in approximately the upper 50% and performs this style transformation below; left-right uses the faithful source in approximately the left 50% and the transformation on the right. Unify both regions through colour, light, rhythm, typography, and meaning.
- `DESIGN_ONLY` and `WALLPAPER_PACK` use the complete canvas while the source remains an invisible identity/content reference. Recompose every wallpaper separately for its device.
- `FINAL CANVAS` means the ratio/pixels of the whole finished artwork and must be explicitly resolved before generation; never apply source dimensions silently. `DESIGN FRAME` is used only if a failed complete-canvas retry triggers deterministic composition fallback.
- Retry a failed complete canvas once against the failed constraint only. Scripted composition is allowed only after that retry still fails, when pixel-identical source preservation is explicitly required, when the active route cannot realise the canvas, or for lossless pixel calibration.

Process only the one source photograph explicitly supplied for this current task. Inspect it first and lock the principal subject or inseparable relation, contour, pose, action, direction, distance, boundary, material, and emotion. Preserve at least three source-specific recognition cues. Never borrow a subject, palette, copy, or composition from old outputs, samples, or another input.

## Core translation

Compress the complex photograph into one unique, minimal, instantly recognisable visual anchor. Follow “one subject or relation, one direction, one spatial relation”: choose only the most source-earned structure from horizontal extension, vertical extension, isolated suspension, outward dissipation, or shallow-to-deep recession. Do not combine several composition tricks.

Keep the anchor usually small. Make a vast paper-toned field the principal image and use blank space to express distance, air, pause, time, or isolation. Add only one horizon, boundary, shadow, or halftone band when it materially establishes space. Do not trace the photograph, add rich illustrative detail, or create several focal points.

## Colour and print

Do not directly copy the photograph's overall palette. Derive its composite temperature, value, and emotional weight, then organise two or three spot colours:

- paper base: off-white, warm grey, or natural paper, occupying the largest area;
- main ink: one quiet, weighty composite hue carrying the anchor and primary boundary;
- mist layer: a lighter, greyer same-family hue used only when distance or depth requires it.

Permit one extremely small accent only when it has a clear narrative purpose. Establish hierarchy through colour area, value, and dot density. Reject rainbow palettes, cheap black-red drama, muddy vintage filters, and corporate colour systems.

Every fog bank, distance cue, shadow, fade, dissipation, and spatial transition must be built with visible halftone dots moving naturally from dense to sparse. No digital blur, Gaussian blur, airbrush softness, ordinary gradient, or gradient mesh. Retain paper grain, screenprint ink, slight misregistration, incomplete coverage, and subtly uneven inking without turning the work into an indiscriminate dirty overlay.

## Copy and typography

Obey the already resolved copy mode and target language or locale: automatic copy, exact user copy, or text-free. Preserve exact user copy verbatim—never rewrite, translate, spell-correct, or append. In text-free mode render no text or pseudo-text.

Automatic copy distils one extremely short title from the source's visible or supported subject, emotion, time, action, material, distance, or metaphor, then adds zero to three micro-elements only when useful. A restrained sentence, chapter-like marker, number, year, coordinate-like figure, or archival-style sign is allowed, but factual dates, coordinates, locations, years, numbers, and provenance must be supplied or reliably established; never fabricate them.

Typography must participate in composition: run along the horizon, hug the anchor contour, form a vertical axis, cross a halftone boundary, hide within negative shape, or use controlled overlap, interweaving, interruption, and alignment. Split words, vertical setting, or wide spacing only when natural to the target writing system and still readable. Use a native high-end editorial equivalent for the locale: restrained sans, gentle serif, or minimal condensed type, light weight, strong scale contrast, and asymmetric hierarchy. Type and image belong to the same screenprint or letterpress pass, sharing grain and slight misregistration.

Copy must bind tightly to this photograph. Rewrite it if it survives an unrelated-image swap. Reject commercial advertising language, generic inspiration, a headline that dominates the image, decorative fake foreign text, and unrelated explanation.

## Mode and canvas

Obey the appended `OUTPUT MODE`, `FINAL SIZE`, and `DESIGN FRAME`. The generated design must independently fill its design frame:

- `TOP_BOTTOM`: generate only the lower design half, never the photograph, seam, or upper region;
- `LEFT_RIGHT`: generate only the right design half, never the photograph, seam, or left region;
- `DESIGN_ONLY`: generate the complete transformed design only, with no visible source photograph;
- `WALLPAPER_PACK`: recompose for the named device, keep system-UI zones low-information, and render no clock, icons, dock, controls, or device mockup.

For a linked wallpaper pack, the original photograph locks identity and content while the approved anchor locks only visual DNA: small-anchor grammar, one-direction/one-relation logic, negative-space hierarchy, spot-colour family, halftone transition, physical print evidence, and typography. Recompose every device independently; never crop the anchor or chain one device derivative into the next.

## Hard acceptance gate

- one small unique visual anchor preserving at least three source-specific cues;
- exactly one dominant direction and one spatial relation;
- paper-toned negative space is the largest field and carries meaning;
- only two or three spot colours, with any accent tiny and earned;
- all fog, depth, shadow, fading, and transition use dense-to-sparse halftone only;
- credible screenprint and aged-paper evidence, never digital blur, ordinary gradients, or a cheap vintage filter;
- copy is short, accurate, source-bound, and integrated into the spatial structure;
- no multiple focal points, detailed illustration, commercial template, giant title, 3D, photo fragments, or pseudo-text.

If any hard condition fails, correct the generated asset. Never fake the artwork with programmatic drawing, SVG, HTML, Canvas, or a post-composited type overlay.
