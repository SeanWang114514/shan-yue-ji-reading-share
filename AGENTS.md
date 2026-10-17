# Agent Guide: Shan Yue Ji Reading Share

Maintain a 13-page classroom presentation. `CONTENT-SPEC.md` is the slide-by-slide content and design authority. `slides/page-01.svg` through `page-13.svg` are editable page sources; `materials/assets/` contains cropped assets and `materials/raw/` originals. `山月记_读书分享.univer` is the editable Univer document; `《山月记》.pptx` is a presentation deliverable. `SOURCE-NOTES.txt` retains source notes.

## Workflow

1. Read `STATUS.md`, `CONTENT-SPEC.md`, and the target SVG before editing. Cross-check quotations against source notes; do not silently rewrite quotations.
2. Reuse supplied assets. Screenshots are references, never source files.
3. After SVG edits, rebuild/export using the original workspace production scripts or presentation tools, then inspect affected pages. Do not claim the Univer file is synchronized unless it was actually updated and checked.
4. Verify 960x540 page size, clipping, page numbers, text overflow, and cross-slide consistency.
5. Update `STATUS.md` with changed pages, outputs, checks, and unresolved items.

## Contents

- `slides/spec.md`: full slide specification.
- `slides/page-*.svg`: editable page sources.
- `materials/raw/` and `materials/assets/`: original and prepared images.
- `SOURCE-NOTES.txt`: source notes.
- `山月记_读书分享.univer`: editable Univer document.
- `《山月记》.pptx`: presentation output.

Production helpers remain in the original workspace `work/` folder (`dump-slide-text.js`, `make_contact_sheet.py`, `make_groups.py`, `process_images.py`, `make_assets_review.py`, `shrink_assets.py`); page screenshots remain in its `shots/` folder. They were not copied because they are auxiliary outputs, not required to edit slide sources. Retrieve and add a helper if a task needs reproducible generation.

Keep changes in this project. Never overwrite uncommitted work. Verify the PPTX matches the final SVG/spec before publishing.