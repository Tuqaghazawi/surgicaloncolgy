# KHCC Oncology — Year 1 Study Hub

Interactive study hub for the KHCC Radiation Oncology Year 1 written examination.

**Live site:** https://tuqaghazawi.github.io/KHCConcologystudying/

## Topics

| Topic | Exam Weight | Sections |
|---|---|---|
| Breast Cancer | 18–20 marks | 14 |
| Colorectal Cancer | 18–20 marks | 14 |
| Thyroid Cancer | 10–15 marks | 14 |
| Hepatobiliary & Pancreas | 10–15 marks | 14 |
| Upper GI | 10–15 marks | 14 |
| Research & Statistics | 5 marks | 14 |
| Basic Science, Melanoma & Sarcoma | 15 marks | 14 |

## Structure

Each topic contains 14 sections:

1. Basics (anatomy, physiology)
2. Molecular Basis & Genetics
3. TNM Staging
4. NCCN Guidelines
5. KHCC Guidelines
6. Fact Sheet
7. Main Neoadjuvant Trials
8. Main Adjuvant Trials
9. Surgical Focus Trials
10. Locoregional Management
11. Surgical Standards (operative)
12. NotebookLM Discussion
13. Review Books Summary
14. Webinars

## How to add a new artifact

1. Save the artifact file (`.html`, `.pdf`, `.pptx`) into the correct topic folder (e.g. `breast/`)
2. Open `breast/index.html` and find the relevant section row
3. Change it from a `<div class="section-row coming">` to an `<a href="your-file.html" class="section-row live">`
4. Commit and push — GitHub Pages updates in ~2 minutes

## Deployment

GitHub Pages is configured to serve from the `main` branch root.
The homepage is `index.html` at the root of the repository.
