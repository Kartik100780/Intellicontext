# CHANGES_PDF.md – PDF-level edits to the attached file (16 Oct 2026)

Input: `RICE2026_Paper287992_IntelliLog_CameraReady.pdf` (attached; 7 pages; Neevia producer).
Output: `287992_IntelliLog_camera_ready_candidate.pdf` (candidate only – NOT PDF eXpress-validated).

## Edit made
| Pages | Object | Before | After | Verification |
|---|---|---|---|---|
| 1–7 | Page content stream, op index 11 on each page (`TJ`, font /R9 Arial 9.96) | Draws the visible "PUBLIC" footer text (6 glyphs, centred, y≈17 pt) | Replaced by an empty `TJ` array (`[]TJ`). Positioning operators unchanged, so no other text moves | `PUBLIC` count in extracted text: 7 → 0. Rendered pixel diff vs original is confined to x 288–323 pt, y bottom footer strip on all 7 pages. Word count 5440 = 5440 |

## Not changed (and why)
- **Copyright placeholder** "XXX-X-XXXX-XXXX-X/XX/$XX.00 ©20XX IEEE": kept. The organisers' notice was not supplied; it must not be invented.
- **Reference [6] and [8] author lists** (publisher records: LogMine, LogZip): NOT changed. The corrected names are longer than the originals, so changing them at PDF level needs new glyphs (not in the subset fonts) and re-flowing the reference entries. Must be done in the Word source, then re-exported.
- **Reference [20] and [21]; body citations "[21]" (Discussion > Future Work) and "[20]" (Methodology > Reproducibility):** NOT changed. Removing them at PDF level would need re-flowing justified lines. Must be done in the Word source (`source/paper.docx`, edits E5–E7).
- **AI disclosure:** not added. Intake says AI used for grammar/language; chat answer said no AI. Unresolved.
- **Figure 2 raster (~327 dpi):** not replaced; vector export needed from authors.
- **Document metadata:** the Creator field still reads "Certified by IEEE PDFExpress at October 16, 2026 13:29:41". That string is inherited from the input and was not verified by me. It is not evidence of validation of this edited file. The file must be validated again.

## Status
Candidate only. Not camera-ready until: (1) references and body citations E3–E7 are applied in Word and the PDF re-exported; (2) organisers' copyright notice is available or confirmed; (3) AI disclosure decided; (4) PDF eXpress validation under Conference ID 71332X passes.
