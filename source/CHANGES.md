# CHANGES.md (D3) - IntelliLog, RICE 2026 Paper #287992

Base: `origin/main` file `RICE2026_Paper287992_IntelliLog_CameraReady.docx` (git blob `ce5d507380f5210f97d29d401b830ea0568d0a9c`, origin/main commit de1431a, fetched 16 Oct 2026).
Scope: minimal-change rule. Only two edits were made. Everything else is FLAGGED, not changed.

## Edits made

| # | File | Location | Before | After | Reason | Rule |
|---|------|----------|--------|-------|--------|------|
| E1 | `word/footer1.xml` ... `word/footer6.xml` | Footers, all sections | Visible text box "PUBLIC" (Microsoft classification text box, 3 per footer part) | Removed. The placeholder line "XXX-X-XXXX-XXXX-X/XX/$XX.00 ©20XX IEEE" was **kept** (see F2) | Author decision (intake answer, "remove PUBLIC") - the label is not part of the official paper | Compliance: no marks not in the official paper (A1, A2) |
| E2 | `word/document.xml` | Contributions bullet 1 | `... production-representative workload (Section V, Table II).` | `... production-representative workload (Section V).` | Table II was cited before Table I (Table I is first cited in Experimental Setup). Table II is still cited in Results (`Table II reports the reduction at each incremental stage...`) | T4 (figures/tables cited in order of appearance) |

Verification of E1/E2 (raw): paragraph diff of `word/document.xml` = exactly 2 paragraphs (the bullet before/after shown above). Footer diff: "PUBLIC" 2 -> 0 in footer2.xml; placeholder retained. All 6 footer parts and document.xml parse as XML. `word/media/image1.png` byte-identical to origin.

## Not changed - flagged for authors (see COMPLIANCE_REPORT.md section 6)

| # | Item | Why not changed |
|---|------|-----------------|
| F1 | Sensitivity label metadata in `docProps/custom.xml`: `ClassificationContentMarkingFooterText = PUBLIC`, `MSIP_Label_..._Enabled = true` | Organisation's data-classification metadata. Removing it is a policy decision. Word may regenerate the visible footer marking from it. |
| F2 | Footer placeholder "XXX-X-XXXX-XXXX-X/XX/$XX.00 ©20XX IEEE" | Organisers' copyright/IEEE notice not supplied (intake B14 "Not provided"). Must be replaced only with the organisers' text. |
| F3 | Reference [6] LogMine author list | Published authors differ (Hamooni, Debnath, Xu, Zhang, Jiang, Al Mueen). Author must verify against the source and approve the correction. |
| F4 | Reference [8] LogZip author list | Published authors differ (Jinyang Liu, Jieming Zhu, Shilin He, Pinjia He, Zibin Zheng, Michael R. Lyu). Author must verify and approve. |
| F5 | Reference [21] (S. Nair, A. Kumar, L. Zhang, CLOUD 2021) | No public record found. Tagged AUTHOR ACTION REQUIRED - UNVERIFIED REFERENCE. Not deleted, not reconstructed. |
| F6 | Reference [20] internal repositories "available on request" | Not verifiable by IEEE readers; may be a self-citation; confidentiality question. Author decision. |
| F7 | Figure 2 raster 965x688 px at ~327 dpi; a line-art bar chart | Needs >=600 dpi or vector. Re-plotting is forbidden without the authors' data/script. |
| F8 | Table II table-note paragraph is styled `figurecaption` and begins "Table II." | Label duplication; style fix is a template decision. |
| F9 | AI-use disclosure absent from Acknowledgment (intake B09: grammar/language use) | Disclosure is a recommendation for grammar-only use; author decides. Tool name missing from intake. |
| F10 | Language / style: 26 em dashes in body | Style observation only. No rewrite. |
