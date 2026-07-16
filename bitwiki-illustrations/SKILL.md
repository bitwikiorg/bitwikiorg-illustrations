---
name: bitwiki-illustrations
description: Generate precise branded editorial illustrations for BITwiki, BIThub, BITCORE, and related intelligence-factory concepts.
---

# BITwiki Illustrations

Use this skill when a user asks for article illustrations, explanatory diagrams, branded concept art, system plates, workflow visuals, or image sets for the BITwiki ecosystem.

## Required behavior

1. Read the supplied source before designing imagery.
2. Identify the operational concept, not merely the nouns in the text.
3. Use one primary cognitive anchor per image.
4. Preserve the exact BITwiki vocabulary defined in `references/ecosystem-ontology.md`.
5. Choose either the modern technical monochrome style or the Intelligence Codex style from `references/brand-system.md`.
6. Use spectral color only to indicate active cognition, transfer, recursion, state change, or semantic flow.
7. Generate 16:9 landscape images unless another format is explicitly requested.
8. Keep long explanatory text outside the image. Prefer short labels or no labels.
9. Never reproduce external mascots, personal identities, contact information, or author branding.
10. Run `references/qa-checklist.md` before declaring an image complete.

## Multi-image workflow

When the request requires several illustrations:

1. Produce a shot list with 4–8 entries.
2. For each entry specify:
   - placement or use
   - cognitive anchor
   - visual metaphor
   - composition pattern
   - BITwiki elements represented
   - required labels
   - preferred house style
3. Generate each image independently.
4. Save outputs under `assets/<project-slug>/`.
5. Report filenames, intended use, and any residual QA risks.

## Canonical system flow

```text
Task enters BIThub
↓
Topic becomes a workcell
↓
Agents / Constructs / COREs process the task
↓
Useful output becomes an artifact
↓
Stable knowledge moves into BITwiki
↓
Future humans and agents reuse it
```

## Preferred compositions

Use patterns from `references/composition-patterns.md`. Avoid generic dashboards, slide-template layouts, decorative mascots, and unsupported fantasy narrative.

## Prompt construction

Build generation prompts from `references/prompt-template.md`. Include semantic requirements before visual treatment. Treat manuscript aesthetics as rendering language, never as factual content.

## Output standard

A successful illustration is:

- semantically accurate
- recognizably BITwiki
- visually memorable
- technically legible
- compositionally focused
- free of foreign identity or branding
- usable as an article image without requiring a presentation deck
