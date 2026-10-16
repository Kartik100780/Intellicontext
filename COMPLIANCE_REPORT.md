# COMPLIANCE_REPORT.md (D4) – RICE 2026, Paper #287992 "IntelliLog"

**Status: PARTIAL. D1 (PDF eXpress-ready PDF) is NOT produced. Validation: NOT done. Do not upload anything from this package yet.**

**Deadline: Friday 16 Oct 2026, 23:59 IST.** Target for PDF eXpress validation: **22:30 IST** (upload by 23:00 IST). Sandbox clock at time of writing: 15:50 UTC = 21:20 IST (time-stamped with `date`, [MEASURED]).

Evidence labels: `[MEASURED]` = tool output (raw output in section 3). `[INFERRED]` = my judgement. `[AUTHOR-CONFIRMED]` = author told me (intake answers, 16 Oct 2026).

---
## 1. Snapshot

| Field | Value | Label |
|---|---|---|
| Paper ID | #287992 (intake B01; author confirmed this paper choice) | [AUTHOR-CONFIRMED] |
| Title (docx title paragraph) | IntelliLog: A Multi-Stage Log Reduction Pipeline for Cost-Optimised Splunk Ingestion | [MEASURED] (identical to intake B02 and PDF metadata) |
| Authors | 1: Kartik Mehta, HSBC Software (I) PVT LTD, Pune, India, kartik.mehta@hsbc.co.in | [MEASURED] from docx author paragraph; [AUTHOR-CONFIRMED] sole author |
| Author count | 1 | [AUTHOR-CONFIRMED] |
| Source format | Word .docx (`RICE2026_Paper287992_IntelliLog_CameraReady.docx`, origin/main). Intake B04 says ".pdf" – superseded by the user's message | [MEASURED] |
| Page size (source) | US Letter 12240 x 15840 twips (8.5 x 11 in) | [MEASURED] `w:pgSz` |
| Page count (source) | **Not measured.** No renderer is available here. Attached reference PDF (different file, see §4) = 7 pages | [MEASURED] for the PDF only; [INFERRED] ~7 for the docx |
| Template | Intake B07: "IEEE Word template". Not verified against the official RICE/IEEE template (`conference-template-letter.docx` in the repo is US Letter but its origin is unknown) | [AUTHOR-CONFIRMED] + [INFERRED] |
| Equations | 16 `oMath` markup occurrences in document.xml (live OMML maths, not images). Equation numbers (1)–(8) appear in body text | [MEASURED] (count of markup tags, not a count of displayed equations) |
| Tables | 2 real Word tables (TABLE I, TABLE II) | [MEASURED] |
| Figures | Fig. 1: native Word vector group drawing (architecture). Fig. 2: embedded PNG 965x688 px, 2.95 x 2.1 in = ~327 dpi | [MEASURED] |
| References | 21, numbered [1]–[21] | [MEASURED] |
| Self-citations (surname match "Mehta") | 0 | [MEASURED] |

---
## 2. Compliance matrix (§E of the brief, fully filled)

| Rule | Requirement | How verified | Result | Notes |
|---|---|---|---|---|
| T1 | Live presentation by registered author; allotted slot; slot change by 3 Nov 2026; no proxy | Intake B13: "Online". Email: slot is emailed after registration closes | **AUTHOR ACTION REQUIRED** | No slot assigned yet. Glitch claims: timestamped screenshot emailed to riceconvenor@gmail.com during the session only. See runbook. |
| T2 | ≤15% overall, ≤2% single source, refs excluded | Local overlap audit only (§5). Intake B11: "No" similarity report | **AUTHOR ACTION REQUIRED** | CrossCheck NOT run. No percentage estimated. Run your own check before upload if the organisers give access. |
| T3 | Citations ⇄ refs bijection; ≤2 self-citations; nothing unrelated | Script §3.3 | **PARTIAL – FLAGGED** | Bijection PASS (21/21), order PASS, self-citations 0. FAILS: [21] unverified; [6], [8] author lists differ from published record; [20] internal, unverifiable. |
| T4 | Editable tables/equations; figures and tables numbered and cited in order | §3.2, §4 | **FIXED (1 item) + AUTHOR ACTION** | Fixed: Table II was cited before Table I (E2). Tables/equations PASS. Fig. 2 is raster at ~327 dpi (line art needs ≥600 dpi) → vector export required (F7). |
| T5 | No undeclared AI paraphrasing, tortured phrases, serious grammar errors, recycled content | Watchlist scan §5; repeated-sentence scan §5 | **PARTIAL** | Watchlist: 0 hits. Repeated ≥12-word sentences: 0. Full grammar sweep NOT completed (time). AI use declared only as grammar/language (intake). |
| T6 | Authors only; correspondence from authors | No artifact sent or submitted; drafts are not needed now | **PASS** | All correspondence must come from the author's own address. |
| T7 | Author list changes discouraged | Docx author list = intake = "Kartik Mehta" alone | **PASS** | No change made. |
| T8 | Deadline 16 Oct 23:59 IST; only PDF eXpress-validated file accepted | No PDF validated here | **AUTHOR ACTION REQUIRED** | See runbook. Validation is outstanding. |
| T9 | KonfHub only; non-refundable; taxes/charges borne by author | Email: early-bird ends today 23:59 IST | **AUTHOR ACTION REQUIRED** | Register on KonfHub today. Runbook note only. No payment action by me. |
| T10 | Fee paid by a named author or their affiliating institution | Payer not stated in intake | **AUTHOR ACTION REQUIRED** | Confirm payer (Kartik Mehta, or HSBC as affiliating institution). Keep receipt. |
| T11 | Withdrawal in writing signed by all authors, before registration | Not requested | **N/A** | No withdrawal draft produced. |
| T12 | Integrity; data/code/logs/ethics/institutional confirmation within 4 days | §6 readiness list | **AUTHOR ACTION REQUIRED** | Internal repos ([20]) not public; ethics approval number not stated; see §6. |
| T13 | Compliance is a condition of publication; TPC decision final | Statement only | **N/A** | See §7 risk register. |
| T14 | riceconvenor@gmail.com only; Paper ID in every message | No message sent; runbook sets the subject line | **PASS** | Use subject "RICE 2026 – Paper ID #287992 – Declaration & Registration". |
| Decl 1 | Authorship; author list identical in paper and eCopyright | D5 block vs docx title page | **AUTHOR ACTION REQUIRED** | Identical in docx; author must confirm sole authorship. |
| Decl 2 | Original; not published or under consideration elsewhere | Not checkable by me | **AUTHOR ACTION REQUIRED** | Author must confirm. |
| Decl 3 | Data, results, figures and code genuine | No data altered by me. Text says "production-representative" and also "synthetic" traffic (Sec. IV-A) | **AUTHOR ACTION REQUIRED** | Author must confirm the wording "production-representative" matches what was run. Raw logs are not in this package. |
| Decl 4 | Every reference read, relevant, cited; no padding; self-citation essential only | §3.3 | **AUTHOR ACTION REQUIRED** | [6], [8], [21] (and [20]) need action; refs [5], [7], [9]–[19] were not verified by me. |
| Decl 5 | Similarity limits met | §5 | **AUTHOR ACTION REQUIRED** | Not measured by a similarity tool. |
| Decl 6 | Generative AI disclosed as IEEE requires; no AI author; authors responsible | Intake B09: grammar/language only. Acknowledgment has no AI sentence | **AUTHOR DECISION** | Recommended, not strictly required (grammar-only). Tool name missing. Sentence in D6 (optional). |
| Decl 7 | Ethics approvals held; funding and COI disclosed | Acknowledgment: no funding, no competing interests. Section VII: no approval reference. Intake B10 absent | **AUTHOR ACTION REQUIRED** | Confirm no ethics approval is needed (or supply it). Do not invent a number. |
| Decl 8 | Registered author presents personally; allotted slot; glitch rules | D6 item 8 | **AUTHOR ACTION REQUIRED** | Presenter must be a registered author. |
| Decl 9 | Verification within 4 days | Readiness list §6 | **AUTHOR ACTION REQUIRED** | |
| Decl 10 | Payment ≠ publication; no refund claim if formalities missed | Runbook | **PASS (acknowledged)** | |
| Decl 11 | Accepts RICE 2026 terms; TPC decision final | D6 item 11 | **AUTHOR ACTION REQUIRED** | Signature by author. |

---
## 3. Pre-flight test log (raw outputs)

### 3.1 Source (docx) checks – `origin/main` file
Commands: `git show origin/main:RICE2026_Paper287992_IntelliLog_CameraReady.docx > /tmp/IntelliLog.docx`, then Python (zipfile/lxml) checks. Key outputs:

```
docProps/core.xml: title = "IntelliLog: A Multi-Stage Log Reduction Pipeline for Cost-Optimised Splunk Ingestion"; subject = "RICE 2026 Paper #287992"; creator = "Kartik Mehta"
pgSz: w=12240 h=15840 (US Letter)
drawings: 2   (group drawing without image = Fig.1 vector; inline PNG = Fig.2)
oMath: 16     (live equation objects)
paragraphs: 231, tables: 2
image extent: 6.9 x 2.86 in (group drawing), 2.95 x 2.1 in (PNG 965x688 px -> 327 dpi)
footers (before edit): "PUBLIC" text boxes x3 in each of footer1–6; placeholder "XXX-X-XXXX-XXXX-X/XX/$XX.00 ©20XX IEEE" in footer2, 4, 5, 6
comments/ins/del: 0 / 0 / 0; hyperlinks: 0; field codes: 0; bookmarks: 1
docProps/custom.xml: ClassificationContentMarkingFooterText = PUBLIC; MSIP_Label_..._Enabled = true; SetDate 2026-10-16T12:22:04Z
```

### 3.2 Edit verification (after E1, E2)
```
changed parts: word/document.xml, word/footer1–6.xml   (media/image1.png identical to origin)
document.xml paragraph diffs: 2 (bullet 1 only)
footer2.xml after: ['XXX-X-XXXX-XXXX-X/XX/$XX.00 ©20XX IEEE']
XML parse failures: none
```

### 3.3 Citation script (docx body vs reference list)
```
body cite first-appearance order: [1..21]   in order: True   distinct: 21   max: 21
listed: [1..21]  count 21
cited but unlisted: []   listed but uncited: []
self-citations (surname "Mehta" in ref authors): 0
```
[INFERRED] [20] "Splunk Optimization Team" may be the authors' own group; the author must decide whether it is a self-citation.

### 3.4 Placeholder and watchlist scan
```
PLACEHOLDER insert: 3 hits – all are the word "insert" in technical text (bulk insert, batch-inserted, insertion). Not placeholders.
no hits for TODO, lorem, [ref], ??, TBD
WATCHLIST (tortured phrases, AI markers): 0 hits for all listed phrases incl. "delve", "pivotal", "it is worth noting", "leverage", "notably,", "in today", "crucial", "robust", "seamless", "tapestry"
em dashes in body: 26   en dashes: 1
```

### 3.5 Repetition scan
```
repeated >=12-word sentences: 0
```

### 3.6 Reference web checks (publisher/index records)
- [6] LogMine (CIKM 2016): published authors Hossein Hamooni, Biplob Debnath, Jianwu Xu, Hui Zhang, Guofei Jiang, Abdullah Al Mueen; pp. 1573–1582 (ACM record via search). Docx lists "H. Liu, S. He, J. Wang, L. Shi, J. Liu, and T. Zheng" → **mismatch**.
- [8] LogZip (ASE 2019, pp. 863–873): published authors Jinyang Liu, Jieming Zhu, Shilin He, Pinjia He, Zibin Zheng, Michael R. Lyu (ASE 2019 programme page; Semantic Scholar). Docx lists "J. Liu, S. He, J. Wang, T. Zheng" → **mismatch**.
- [21] "Log volume reduction in cloud-native environments using adaptive sampling", CLOUD 2021, S. Nair, A. Kumar, L. Zhang: **no record found** in the search. → **UNVERIFIED**.
- Not checked by me: [1]–[5], [7], [9]–[19]. Authors must verify each by reading (Decl 4).

### 3.7 Attached reference PDF (different file – NOT D1; reported for comparison only)
Attached `RICE2026_Paper287992_IntelliLog_CameraReady.pdf` (16 Oct 2026):
```
PDF version: 1.4   pages: 7   encrypted: False
MediaBox on all 7 pages: [0 0 612 792]  (US Letter)
annotations per page: none    outlines: none    embedded files: none
fonts (all embedded=True): TimesNewRoman, TimesNewRoman,Bold, TimesNewRoman,Italic, TimesNewRoman,BoldItalic, Arial, Arial,Italic, CambriaMath, StandardSymL(Type1)   Type 3: none
images: p5 887x633 DeviceRGB DCTDecode
Info: Creator "Certified by IEEE PDFExpress at October 16, 2026 13:29:41"; Producer "Neevia Document Converter Pro v7.3.0.184"; Title matches; Subject "RICE 2026 Paper #287992"
visible text per page: "PUBLIC" header (y≈17–27 pt, all 7 pages); placeholder footer "XXX-X-XXXX-XXXX-X/XX/$XX.00 ©20XX IEEE" (all 7 pages)
body text: Table II precedes Table I; caption label text "Fig. 3. Fig. 2." and duplicated "Fig. 1. Fig. 1." in the text layer
```
[INFERRED] This PDF is not the output of the current docx: it has a "Fig. 3" label, which the docx does not. Do **not** use it as D1. The "Certified by IEEE PDFExpress" string is metadata only and does not prove validation.

### 3.8 Pre-flight tests NOT run (no D1 exists)
pdfinfo / pdffonts / pdftotext / qpdf / pikepdf checks on the author's PDF: **NOT RUN – pending**. These run as soon as the author exports and provides the PDF (runbook step 5).

---
## 4. Changes made (summary; full list in source/CHANGES.md)

| File | Location | Before | After | Reason | Rule |
|---|---|---|---|---|---|
| word/footer1–6.xml | footers | visible "PUBLIC" text boxes | removed (placeholder kept) | author decision | marks not in official paper |
| word/document.xml | contributions bullet 1 | "(Section V, Table II)." | "(Section V)." | order of Table citation | T4 |

Nothing else was changed. Figures, tables, equations, references, title, author list and affiliation were not altered.

---
## 5. Similarity & language audit (local only – NOT IEEE CrossCheck)

- **CrossCheck:** run by the organisers, not by me. No similarity percentage is stated or estimated here. Intake B11: no similarity report.
- **Local checks:** repeated sentences ≥12 words: 0. Watchlist hits: 0. Em-dash rhythm: 26 em dashes (reported, not rewritten).
- **Grammar sweep:** not completed. Remaining work: subject–verb, article, tense, acronym definitions, "et al." formatting.
- **Generative AI:** intake says used for grammar and language only. Acknowledgment does not mention it. Recommended disclosure (not strictly required for grammar-only use) – author decision (D6 optional sentence).

---
## 6. Author action required (prioritised; IST times assume today)

| # | Action | Why | Who | Deadline (IST) |
|---|---|---|---|---|
| 1 | Confirm the paper ID #287992 and find its acceptance email. The only acceptance email in the workspace is for **#476130** (IntelliContext) | Identity mismatch risk | Kartik Mehta | **21:40** |
| 2 | Review `source/CHANGES.md` (E1, E2) and approve | Minimal-change rule | Kartik Mehta (and co-authors if any) | 21:45 |
| 3 | Decide on refs: [21] unverified (verify or replace – do not guess); [6] and [8] author lists (correct to published authors after reading); [20] internal (replace with public source or remove, if it is not essential) | T3, Decl 4, T12 | Kartik Mehta | 22:00 |
| 4 | Decide AI disclosure; supply tool name if disclosing | Decl 6 | Kartik Mehta | 22:00 |
| 5 | Confirm the copyright/IEEE footer line; replace placeholder only with organiser text. Ask riceconvenor@gmail.com if unknown (quote Paper ID) | B14 not provided; placeholder visible in proceedings | Kartik Mehta | 22:00 |
| 6 | Decide whether the organisation's "PUBLIC" sensitivity label (docProps/custom.xml) can stay. Word may re-add the footer marking | Mark not in official paper | Kartik Mehta with data-classification owner | 22:00 |
| 7 | Provide Fig. 2 as vector (PDF/EPS) from your plotting script, or confirm 327 dpi is acceptable. Check grayscale: dark-blue and teal bars may look alike | ≥600 dpi line art / B&W legibility | Kartik Mehta | 22:15 |
| 8 | Confirm ethics approval status (none stated; intake B10 missing); funding none; COI none | Decl 7 | Kartik Mehta | 22:00 |
| 9 | Open source zip → paper.docx in Word; check it is 6 pages or note 7; Save as PDF; provide the PDF to me for pre-flight | D1 is not produced here | Kartik Mehta | 22:15 |
| 10 | PDF eXpress: sign in with Conference ID **71332X** (organiser email says "still to confirm" – verify with riceconvenor before relying on it); validate; download the validated PDF | T8 | Kartik Mehta | **22:45** |
| 11 | ConfConnects: Submit Camera Ready (not Submit Paper); upload only the validated PDF; check the upload is listed | Email step 03 | Kartik Mehta | 23:00 |
| 12 | eCopyright: enter D5 block exactly | Decl 1 | Kartik Mehta | 23:05 |
| 13 | KonfHub: Paper ID #287992; title; page count; mode Online; "NA" for IEEE membership if non-member; pay (payer = Kartik Mehta or HSBC); add Additional Page ticket (INR 1,000) if >6 pages – confirm the ticket exists first | T9/T10, A10 | Kartik Mehta | **23:20** |
| 14 | Sign D6 personally; email step 06 to riceconvenor@gmail.com with the signed declaration (PDF named RICE2026_#287992_Declaration.pdf), KonfHub receipt, PDF eXpress pass screenshot, ConfConnects confirmation. Subject: "RICE 2026 – Paper ID #287992 – Declaration & Registration" | Email step 06; "not complete" without it | Kartik Mehta | **23:45** |
| 15 | Keep all confirmation emails and receipts | T12 response | Kartik Mehta | ongoing |
| 16 | Presentation: mode Online; slot will be emailed after registration; slot change requests until 3 Nov 2026 only | T1 | Kartik Mehta | after registration |

---
## 7. Risk register (top 5)

| # | Risk | Likelihood | Impact | Mitigation | Owner |
|---|---|---|---|---|---|
| 1 | Late or missing step 06 email / declaration – paper "treated as not submitted" | High (time) | Paper dropped | Start by 22:45 at latest; send the email before 23:45 | Kartik Mehta |
| 2 | PDF eXpress failure (Word export fonts/graphics; Fig. 2 raster) | Medium | Cannot upload validated PDF | Export from Word now; fix from source; re-validate | Kartik Mehta |
| 3 | Unverified / wrong references ([21], [6], [8], [20]) → Decl 4 / T3 / T12 breach | Medium–High | Malpractice review, dropped paper | Fix before PDF export; verify by reading | Kartik Mehta |
| 4 | Similarity >15%/>2% (CrossCheck, not run) | Unknown | Rejection | Run your own similarity check if you have access; I cannot estimate | Kartik Mehta |
| 5 | Presentation no-show (online; slot not yet assigned) | Medium | Absent / no-show | Note slot email after registration; glitch screenshot rules | Kartik Mehta |

Also note: 7-page PDF (if confirmed) = one extra page = INR 1,000 on KonfHub.

---
## 8. Hand-off

**Current state:** D1 not produced; not PDF eXpress-validated; **not** ready to upload. The phrase for the state is "PDF eXpress-ready; validation pending with Conference ID 71332X" only once a PDF exists and passes pre-flight. That has not happened yet.

**Exact next step (author, now, by 21:40 IST):**
1. Confirm the Paper ID #287992 acceptance email and reply in the chat with that confirmation or with corrections.
2. Open `source/IntelliLog_287992_source.zip` → `paper.docx` in Microsoft Word; export to PDF; save as `camera_ready/287992_camera_ready_pre-validation.pdf`; tell me. I will run the pre-flight suite on that file.
