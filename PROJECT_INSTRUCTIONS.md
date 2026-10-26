# Invitation HTML Editor — Production

## Purpose
Turn supplied invitation images into independent, offline, editable HTML invitation products. Reuse the latest explicitly approved HTML editor as the foundation. Preserve working functionality and change only what each new design requires.

## Required delivery
For N source images, deliver one ZIP with N numbered product folders. Preserve meaningful source names or product IDs in folder names. Each product folder must contain exactly:

1. `Editable_Invitation.html`
2. `Before.jpg` or `Before.png` — the original supplied image, unchanged
3. `After.png` — an actual export from that product's HTML editor, showing changed example details

Do not substitute a combined design-selector editor unless explicitly requested. Repository documentation and QA reports may live outside the product folders.

## Editable content
Make the name, possessive punctuation, date/year, time, venue, address, RSVP contact information, and RSVP deadline editable wherever present. Keep illustrated ages, decorative headings, artwork, and ornaments fixed unless explicitly instructed otherwise.

## Reference handling
Inspect the actual files before starting. Distinguish source images, mockup backgrounds, reference editors, and completed products. Existing or generated files are working references, not automatically approved visual standards. Do not assume files from another chat remain accessible. Verify access to image bytes, not only filenames or metadata. Never upload an LFS pointer or a Base64 text file as a substitute for the original image.

## Visual quality
Remove the entire old lettering and its associated effects without harming unrelated artwork. Avoid rectangular cleanup patches, ghost letters, leftover flourishes, clipped strokes, and damaged decorations. Match letter weight, colors, outlines, highlights, shadows, texture, alignment, spacing, and visual hierarchy as closely as the source assets allow. Use consistent rendering for the initial editable example and subsequent client edits. Do not hide a font mismatch by retaining original image lettering until the first edit. Do not silently compress or shrink long names until the design looks wrong; define supported text lengths where necessary.

## Font accuracy and licensing
Use supplied original fonts and editable sources when available. Embed required fonts for offline operation where licensing permits, retaining license notices. Never claim an exact original-font match without verification. Clearly disclose approximate reconstruction and unresolved differences. Flattened images alone do not establish the identity of an original font.

## HTML functionality
Preserve or provide independent offline operation, embedded artwork and fonts, editable text fields, typography/placement controls, automatic safe fitting, PNG export, PDF export, save/load edits, reset, an original-image comparison, and a responsive preview that does not crop the exported invitation. Preserve native source resolution; adding print-resolution metadata does not create additional detail.

## Per-product quality assurance
1. Test short, medium, and long names, including wide-letter and hyphenated names.
2. Actually change every requested editable field, including longer venues, addresses, and RSVP details.
3. Verify fitting, clipping, required-field validation, and sensible text-size limits.
4. Inspect cleanup areas for old lettering, visible patches, and damaged ornaments.
5. Check unrelated artwork remains unchanged; a zero-outside-region pixel test does not prove quality inside the region.
6. Generate and inspect real PNG/PDF outputs, not only the browser preview.
7. Test save/load, reset, and offline font loading. Record runtime errors.
8. Distinguish automated tests from visual inspection. Never claim an inspection that was not performed.

## Before/after integrity
Before must be the supplied original. After must be exported from the delivered editor using changed name and event details where present. The delivered HTML must open in the same example state shown in After. Do not use a separate rendering process that makes After look better than the client editor.

## Repository and source safety
Preserve original images unchanged. Keep source assets, approved reference editors, working products, and delivery archives clearly separated. Do not delete, overwrite, publish private material, or change repository visibility without explicit approval. Do not invent missing assets, download links, or completed outputs.

## Completion criteria
Verify the ZIP exists, opens successfully, has the correct product-folder count, and contains the three required files in each folder. State which checks passed, which files were inaccessible, and which visual limitations remain. Do not call a result perfect, exact, or client-ready solely because fitting checks passed. Do not imply work continues silently in the background. If blocked, identify the blocker and unfinished work plainly.
