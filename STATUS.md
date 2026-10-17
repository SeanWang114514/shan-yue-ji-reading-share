# Project Status

- Scope: 13-slide reading presentation, design specification, source SVG, image assets, editable Univer file and PPTX output.
- Stage: existing files organized for handoff; historical production workflow has not been independently reproduced.
- Specification: `slides/spec.md`; page sources: `slides/page-01.svg` through `page-13.svg`.
- Production scripts and PNG page previews remain in the original workspace `work/` and `shots/` folders; not included here.
- Verification: inventory confirmed 13 SVG pages, assets, PPTX and Univer file. No visual export/check was run during packaging.
- Caveat: verify PPTX/Univer consistency against SVG. Some quoted literary passages should be checked against the book before editing.

## Next

1. Export current Univer/PPTX and verify all 13 pages.
2. Check text, page numbers, imagery and 960x540 canvas against `slides/spec.md`.
3. Add required original-workspace build helpers if reproducible generation is needed.