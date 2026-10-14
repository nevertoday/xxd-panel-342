---
name: xxd-panel-342
description: "Create XXD Panel 342 raster artwork: a faithful image opened by one repeated die-cut punch shape chosen from the image itself, with the punched-out fragments re-gathered on a quiet solid colour field into a new, open order. Accepts one image or a directory batch and supports top-bottom, left-right, design-only and four-device wallpaper outputs; multiple ratios or exact sizes; text-free by default, with prompt-generated or user-exact typography on request. Use whenever the user invokes xxd-panel-342 or asks for this 艺术打孔 / 打孔余韵 style."
---

# XXD Panel 342

Create finished PNG artwork from the current user-supplied photograph or image directory. Read `references/original-prompt/zh-CN.md` completely immediately before every generation. That Chinese source brief is the sole creative and aesthetic authority; never summarise, translate, blend, or replace it with this file, a README, a sample, or another Panel.

Read `references/soldier-runtime.md` completely immediately before building every generation request. It is the sole family runtime contract for parameters, preference reuse, directory batches, preflight, prompt assembly, bitmap execution, output isolation, and acceptance. This Skill must not write a second art direction or a second runtime.

## Panel-specific overlay

One work uses exactly one punch die. Every hole has the same outline and size; holes may rotate but never deform, never follow an object's edge, and never become an object cut-out. Holes are clean negative shapes inside the reality region that show the same solid ground colour as the design region. Every fragment in the design region carries that same outline and the real pixels taken from a hole above, so the fragment count and content match the holes. Place holes with judged randomness, not a grid or even scatter. The source brief excludes explanatory text, so default to `--text none` unless the user explicitly asks for words. Reject mixed shapes, smudged or blurred "holes", drop shadows, embossing, paper-sculpture depth, sticker borders, tidy specimen grids, and added illustration.

These overlay rules add to `references/soldier-runtime.md`. They never replace the source brief or the family runtime contract.

Write every selected final PNG directly inside one fresh task directory under `~/Desktop/xxd/xxd-panel-342/` (or the explicit `--out` root). Use collision-safe filenames; do not create source, mode, or size subdirectories and do not generate an automatic contact sheet.

## References

- `references/soldier-runtime.md` — family runtime contract used at generation time
- `references/original-prompt/zh-CN.md` — canonical source brief used at runtime
- `references/original-prompt/README.md` — translation index and authority note
- `references/runtime-preferences.md` — safe delivery-preference reuse
- `references/sample-workflow.md` — sample-artwork maintenance only; never a runtime prerequisite
- `references/xxd-panel-342-prompt.zh-CN.md` and `.en.md` — delivery adapter notes matching the family runtime blocks
