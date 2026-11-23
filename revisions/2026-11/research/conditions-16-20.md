# CMID currency audit — Group D (conditions 16–20)
Audit date: 2026-11-23. Reference build: 2026-05-11. Synthesis rule applied: federal > specialty society > foundation; conflicts flagged; more conservative interval wins when sources agree on the item.

---

## 16 Osteoporosis
### Source status
- uspstf-osteo-2025 (USPSTF, JAMA 2025;333(6):498) → CURRENT. Topic page shows final rec released 2025-01-14 and no update in progress (https://www.uspreventiveservicestaskforce.org/uspstf/recommendation/osteoporosis-screening)
- aace-osteo-2020 → CURRENT, but AACE marks it as being revised: the AACE Bone & Parathyroid page lists the 2020 guideline as its only osteoporosis guideline and says "An update of this guideline is currently in development." (https://pro.aace.com/clinical-guidance/bone-and-parathyroid)
- endo-osteo-2019 + endo-osteo-2020-update → CURRENT. The endocrine.org guideline page still shows the 2019 full guideline and the 2020 Update A, latest date 2020-02-18, with no retirement notice (https://www.endocrine.org/clinical-practice-guidelines/osteoporosis-in-postmenopausal-women)
- Endocrine Society "Osteoporosis in Men" (Watts 2012; not footnoted, but the Notes attribute a men-screening position to "Endocrine Society") → RETIRED on 2025-10-16. JCEM correction notice, doi:10.1210/clinem/dgaf645 (https://academic.oup.com/jcem/advance-article/doi/10.1210/clinem/dgaf645/8351036). No replacement found.
- acp-osteo-2023 → CURRENT (reaffirmed). ACP Version 1 Update Alert 1 / Surveillance Note 1 (Ann Intern Med 2025;178(3); doi:10.7326/ANNALS-24-03547) found no new evidence and reaffirmed the recommendations (https://stacks.cdc.gov/view/cdc/261711)
- bhof-2022 → CURRENT. No newer Clinician's Guide was found; BHOF's 2025 newsletters and annual report mention none (https://www.bonehealthandosteoporosis.org/news/bone-health-and-osteoporosis-foundations-updated-clinicians-guide-to-prevention-and-treatment-of-osteoporosis-is-now-available/)
- cms-dxa-ncd (NCD 150.3) → CURRENT. Only ICD-10 and coding revisions were made (Transmittal 13752 added CPT 0554T–0558T retroactive to 2024-01-01; Oct-2026 and Jan-2027 ICD-10 updates). Coverage criteria and frequency are unchanged (https://www.cms.gov/medicare-coverage-database/view/ncd.aspx?ncdid=256)
- FDA label (not previously cited): Prolia (denosumab) Boxed Warning for severe hypocalcemia in advanced CKD, FDA Drug Safety Communication 2024-01-19 (http://www.fda.gov/drugs/drug-safety-communications/fda-adds-boxed-warning-increased-risk-severe-hypocalcemia-patients-advanced-chronic-kidney-disease). It predates the build but is missing from the monograph.

### Changes to make
1. **Notes ("Men.")**
   - CURRENT: "AACE, BHOF, and Endocrine Society support screening men ≥70 (and ≥50 with risk factors)."
   - NEW: "Men. USPSTF 2025 issues an I-statement for men. BHOF supports screening men ≥70 (and 50–69 with risk factors). The Endocrine Society 2012 men's guideline was retired Oct 2025 with no replacement, so it is no longer an operative source."
   - Source: endo-men-2012-retired (https://academic.oup.com/jcem/advance-article/doi/10.1210/clinem/dgaf645/8351036); uspstf-osteo-2025.
   - Caveat: AACE 2020 is a postmenopausal-women guideline. Its men's statement should be re-checked before keeping "AACE" in this sentence.
2. **Laboratory (Serum calcium line) + At-a-glance Labs (As indicated)**
   - CURRENT: "Serum calcium (corrected) — prior to each IV zoledronate or denosumab dose; before initiating any antiresorptive. Avoid hypocalcemia, especially with CKD."
   - NEW: "Serum calcium (corrected) — prior to each IV zoledronate or denosumab dose; before initiating any antiresorptive. Denosumab (FDA Boxed Warning 2024): assess eGFR before prescribing. If eGFR <30 or on dialysis, evaluate for CKD-MBD (nephrology input), correct Ca and replete with Ca + activated vit D before dosing, and monitor serum Ca closely after each dose. Peak risk is weeks 2–5 (range 2–10) post-injection."
   - Source: fda-prolia-boxed-2024 (URL above).
3. **Notes — add a new note**
   - NEW: "AACE update pending. AACE lists its 2020 postmenopausal osteoporosis guideline as under revision (update in development as of Nov 2026). Re-audit DXA-on-therapy intervals when it is published."
   - Source: https://pro.aace.com/clinical-guidance/bone-and-parathyroid
4. **Notes ("DXA on therapy." / "Bone-turnover markers.")**
   - CURRENT text cites "ACP 2023."
   - NEW: "ACP 2023 (reaffirmed by 2025 surveillance note)".
   - Source: acp-osteo-2025-surv.
5. **Functional / surveys (FRAX line)**, optional precision edit
   - CURRENT: "FRAX 10-year fracture risk recalculation — at baseline and as indicated…"
   - NEW: append "USPSTF 2025: for postmenopausal women <65 with risk factors, use a validated risk tool (FRAX, OST, ORAI, SCORE) to select for DXA. FRAX has no USPSTF screening threshold. Race-specific FRAX calculators may underestimate risk in Asian, Black, and Hispanic patients."
   - Source: uspstf-osteo-2025.

### New bibliography entries
- endo-men-2012-retired — Correction to: "Osteoporosis in Men: An Endocrine Society Clinical Practice Guideline" (guideline retired October 16, 2025). J Clin Endocrinol Metab. 2026;111(2):e648. doi:10.1210/clinem/dgaf645. https://academic.oup.com/jcem/advance-article/doi/10.1210/clinem/dgaf645/8351036
- acp-osteo-2025-surv — Qaseem A, Cooney TG, Shamliyan TA, Yost J, Hicks LA. Pharmacologic Treatment of Primary Osteoporosis or Low Bone Mass to Prevent Fractures in Adults: A Living Clinical Guideline From the ACP (Version 1: Update Alert 1: Surveillance Note 1). Ann Intern Med. 2025;178(3). doi:10.7326/ANNALS-24-03547. https://stacks.cdc.gov/view/cdc/261711
- fda-prolia-boxed-2024 — U.S. FDA. Drug Safety Communication: FDA adds Boxed Warning for increased risk of severe hypocalcemia in patients with advanced chronic kidney disease taking osteoporosis medicine Prolia (denosumab). January 19, 2024. https://www.fda.gov/drugs/drug-safety-communications/fda-adds-boxed-warning-increased-risk-severe-hypocalcemia-patients-advanced-chronic-kidney-disease

### Unverified / flagged
- AACE update: "in development," with no publication date. Not yet a change.
- The NCD 150.3 coding addition of CPT 0554T–0558T (CT-based bone strength / fracture-risk analysis) was seen only in search excerpts (ACR 2026-06-18 news; CMS Transmittal 13752). I did not open the transmittal. It does not change the monograph's DXA frequency statements.
- The Notes line "USPSTF 2025 limits Grade B screening to postmenopausal women 1…" is truncated in the flattened text (lost "<65 at increased risk"). Check the HTML source; the content itself is correct per USPSTF.

### No change needed
I verified that USPSTF 2025 grades and populations, the USPSTF 4–8 yr interval language, the Endocrine Society 2019/2020 postmenopausal guideline, BHOF 2022, ACP 2023 recommendations, and the CMS 2-year DXA frequency are all still current.

---

## 17 Prostate Cancer
### Source status
- nccn-pca-2025 (v1.2025) → SUPERSEDED by NCCN Prostate Cancer v5.2026 (at least). See NCCN Guidelines Insights: Prostate Cancer, Version 5.2026, Spratt DE et al., JNCCN 2026;24(5):140-149, doi:10.6004/jnccn.2026.0023 (https://scholars.duke.edu/publication/1824627). The 2026 changes include removal of the very-low-risk group, revised Principles of Active Surveillance, and caution on focal therapy.
- aua-astro-pca-2022 → UPDATED by the Clinically Localized Prostate Cancer: AUA/ASTRO Guideline (2022; Amended 2026). AUA Board approved Feb 2026; released 2026-04-16; J Urol doi:10.1097/JU.0000000000005060 (summary: https://www.auanet.org/documents/Guidelines/PDF/2026%20Guidelines/Localized%20Pros.%20Cancer%20Amendment%20SUMMARY%2012.5.25.pdf ; full text: https://www.auanet.org/documents/Guidelines/PDF/2026%20Guidelines/LoPC%20Unabridged%20FINAL.pdf)
- aua-apc-2023 → UPDATED by Advanced Prostate Cancer: AUA/SUO Guideline (2020; Amended 2023; Amended 2026). Released 2026-05-12; 40 statements; J Urol doi:10.1097/JU.0000000000005219 (summary: https://www.auanet.org/documents/Guidelines/PDF/2026%20Guidelines/2026%20APC%20Amendment%20SUMMARY_Final.pdf ; full text: https://www.auanet.org/documents/Guidelines/PDF/2026%20Guidelines/2026%20APC%20Unabridged%20FINAL.pdf)
- aua-pca-detection-2023 → UPDATED by Lin DW, Carlsson S, Filson CP, et al. Updates to Early Detection of Prostate Cancer: AUA/SUO Guideline (2026). J Urol. doi:10.1097/JU.0000000000004995. Released 2026-02-26 (https://www.auanet.org/about-us/media-center/aua-press-center/aua-announces-updates-to-the-early-detection-of-prostate-cancer-guideline). Statement 7 on personalizing re-screening intervals has revised text, and there is new DRE and 5-ARI content.
- uspstf-pca-2018 → CURRENT. The topic page still shows the 2018-05-08 final rec, flagged "This topic is being updated," with no draft posted (https://www.uspreventiveservicestaskforce.org/uspstf/recommendation/prostate-cancer-screening)
- ascoacs-pca-2015 → CURRENT. No ACS/ASCO prostate survivorship update was found.
- asco-surv-2024 → CURRENT. No newer general ASCO survivorship update was found.

### Changes to make
1. **Summary, Laboratory, At-a-glance (PSA on active surveillance)**. CONFLICT, flag it.
   - CURRENT: "PSA on active surveillance — every 3–6 months."
   - NEW: "PSA on active surveillance — every 3–6 months per NCCN (often q3–6 mo in yr 1). AUA/ASTRO 2026 advises PSA generally no more often than every 6 months; a rising PSA should first be re-tested, then trigger MRI ± biopsy. Interval individualized; less intense in low-progression-risk / limited life expectancy."
   - Source: aua-astro-pca-2026, Statement 18 supporting text.
2. **Imaging (Confirmatory / surveillance biopsy) + Summary + At-a-glance.** Apply the conservative interval.
   - CURRENT: "within 6–12 months of AS enrollment; then every 2–5 years or as triggered."
   - NEW: "MRI first if the diagnostic biopsy was not MRI-guided. PI-RADS 4–5 → prompt targeted confirmatory biopsy; PI-RADS 1–3 → confirmatory biopsy within ~12 months. Then surveillance biopsy every 1–4 years (age, health, progression risk, preference) or as triggered. MRI does not replace periodic biopsy."
   - Source: aua-astro-pca-2026, Statement 19.
   - Note: NCCN v5.2026 also revised its AS principles, but I could not verify the specifics (see Unverified).
3. **Physical examination (DRE on active surveillance)**
   - CURRENT: "DRE on active surveillance — annually."
   - NEW: "DRE on active surveillance — annually (NCCN). AUA/ASTRO 2026 allows every 1–2 years. Annual retained as the more conservative interval."
   - Source: aua-astro-pca-2026, Statement 18.
4. **Laboratory (PSA post-RP and post-RT) + Summary + At-a-glance.** Apply the conservative interval.
   - CURRENT: "every 6–12 months for 5 years, then annually."
   - NEW: "PSA every 3–6 months for the first 2 years after treatment, every 6 months years 2–5, then annually (AUA/ASTRO 2026). NCCN / ACS-ASCO allow every 6–12 months for 5 yr. The more frequent AUA cadence is adopted. Beyond 10 yr with undetectable PSA, duration is a shared decision. Query urinary, bowel, and sexual function with validated instruments at each check."
   - Source: aua-astro-pca-2026, Statement 45 supporting text; ascoacs-pca-2015.
   - Move "PSA post-curative (q6–12 mo first 5 yr)" in the At-a-glance Every-6-months cell to "q3–6 mo yr 1–2; q6 mo yr 2–5".
5. **Imaging (PSMA PET/CT) + Notes ("PSMA PET utilization.") + Summary**
   - CURRENT: "PSMA PET/CT — at BCR with negative or equivocal conventional imaging; for initial staging of unfavorable intermediate / high-risk…" and Summary "PSMA PET is now first-line at biochemical recurrence when conventional imaging is negative."
   - NEW: "PSMA PET/CT — initial staging of unfavorable intermediate / high-risk: PSMA PET OR bone scan + cross-sectional imaging (AUA/ASTRO 2026, Strong); PSMA PET may be added if conventional imaging is negative. Not routine in asymptomatic low / favorable-intermediate risk. PSA recurrence after exhaustion of local therapy: PSMA PET preferred because of greater sensitivity, or when conventional imaging is negative (AUA/SUO 2026)."
   - Notes: replace "AUA 2023 update strongly supports…" with "AUA/ASTRO 2026 and AUA/SUO 2026 amendments position PSMA PET as an equal-alternative (initial staging) or preferred (BCR) modality."
   - Source: aua-astro-pca-2026, Statements 6–8; aua-apc-2026, Statements 6–7.
6. **Imaging. Add an nmCRPC line** (the monograph has none).
   - NEW: "nmCRPC (rising PSA, castrate T, no metastases) — conventional or PSMA PET imaging every 6–12 months; may extend to annually once on ARPI without other progression indicators. PSA every 3–6 months with PSADT calculation."
   - Source: aua-apc-2026, Statements 20–21 + supporting text.
7. **Imaging (DEXA / BMD on ADT) + At-a-glance**
   - CURRENT: "baseline before ADT; every 1–2 years on ADT (or per FRAX risk)."
   - NEW: "Baseline DXA + FRAX before / at ADT start. Re-assess FRAX + DXA 1 year after starting ADT / systemic therapy (greatest loss in yr 1), then every 1–2 years per risk. Calcium, vit D, smoking cessation, and weight-bearing exercise for all on ADT. High fracture risk → bisphosphonate or denosumab."
   - Source: aua-apc-2026, Statements 37–39 + supporting text.
8. **Laboratory. Add a germline / somatic testing line** (As indicated).
   - NEW: "Germline genetic testing — offer to all patients with advanced prostate cancer; add somatic tumor testing in metastatic disease (guides PARP inhibitor eligibility and cascade testing of relatives)."
   - Source: aua-apc-2026, Statement 4.
9. **Laboratory (Abiraterone monitoring)**
   - CURRENT: "Abiraterone monitoring (LFTs, potassium, BP) — every 2 weeks × first 3 months, then monthly."
   - NEW: append "Now also applies to high-risk localized / cN1 disease treated with RT + ADT + abiraterone/prednisone for 24 months (AUA/ASTRO 2026)."
   - Source: aua-astro-pca-2026, Statement 44.
10. **Notes ("PSA screening framework disagreement.")**
    - CURRENT: "AUA/SUO Early Detection 2023…"
    - NEW: "AUA/SUO Early Detection (2023; amended 2026)… USPSTF update in progress (no draft posted as of Nov 2026)."
    - Source: aua-pca-detection-2026; uspstf-pca-2018 page.
11. **Footnotes / Summary.**
    - Replace "NCCN v1.2025" with "NCCN v5.2026".
    - Replace "AUA/ASTRO 2022" with "AUA/ASTRO 2022, amended 2026".
    - Replace "AUA 2023 update" (advanced) with "AUA/SUO 2026 amendment".

### New bibliography entries
- nccn-pca-2026 — Spratt DE, Srinivas S, Adra N, et al. NCCN Guidelines Insights: Prostate Cancer, Version 5.2026. J Natl Compr Canc Netw. 2026;24(5):140-149. doi:10.6004/jnccn.2026.0023. https://www.nccn.org/guidelines/guidelines-detail?category=1&id=1459
- aua-astro-pca-2026 — Eastham JA, Barocas DA, Chu CE, Morgans AK, Rodrigues G, et al. Clinically Localized Prostate Cancer: AUA/ASTRO Guideline (2022; Amended 2026). J Urol. 2026. doi:10.1097/JU.0000000000005060. https://www.auanet.org/documents/Guidelines/PDF/2026%20Guidelines/LoPC%20Unabridged%20FINAL.pdf
- aua-apc-2026 — Advanced Prostate Cancer: AUA/SUO Guideline (2020; Amended 2023; Amended 2026). J Urol. 2026. doi:10.1097/JU.0000000000005219. https://www.auanet.org/documents/Guidelines/PDF/2026%20Guidelines/2026%20APC%20Unabridged%20FINAL.pdf
- aua-pca-detection-2026 — Lin DW, Carlsson S, Filson CP, et al. Updates to Early Detection of Prostate Cancer: AUA/SUO Guideline (2026). J Urol. 2026. doi:10.1097/JU.0000000000004995. https://www.auanet.org/guidelines-and-quality/guidelines/early-detection-of-prostate-cancer

### Unverified / flagged
- **NCCN v5.2026 Principles of Active Surveillance.** The JNCCN abstract confirms they were revised, but the full text (jnccn.org) and the NCCN site returned 403. Specific PSA, DRE, MRI, and biopsy intervals and the very-low-risk elimination wording are not verified. The current nccn.org version number may be higher than 5.2026. Re-check before finalizing items 1–3.
- **NCCN post-treatment PSA interval** (6–12 mo × 5 yr) is assumed unchanged from v1.2025; not re-verified.
- **AUA Early Detection Statement 7.** The re-screening interval text was revised, but I did not read the new wording. The monograph only uses this guideline in the screening-framework Note.
- **USPSTF prostate update.** In progress; no draft posted as of the topic page check.
- Several flattened Summary/Laboratory fragments (testosterone target "<50 ng/dL", "Target undetectable (<0.1…") are truncated at "<" in the .txt. Check the HTML. AUA/SUO 2026 retains castrate T <50 ng/dL.

### No change needed
Still current: USPSTF 2018 grades (C 55–69; D ≥70), ACS/ASCO prostate survivorship 2014/2015, ASCO survivorship 2024, mCRPC baseline labs (AUA/SUO 2026 Stmt 25), mCRPC imaging at least annually without PSA progression (Stmt 26), Phoenix and post-RP BCR definitions, and the PSA q3–6 mo on ADT in mHSPC (Stmt 13).

---

## 18 Non-Alzheimer's Dementia
### Source status
- aan-dementia-2001 (reaffirmed Oct 2024) → CURRENT. A replacement is in development: the AAN "Etiologic Diagnosis of Dementia Practice Guideline" (Day GS et al.) is posted as a public-comment draft marked "Not for duplication, dissemination, or citation" (https://www.aan.com/siteassets/home-page/policy-and-guidelines/guidelines/guidelines-and-measures-open-for-public-comment/26-diagnosis-of-dementia-guideline-public-comment.pdf)
- aan-mci-2018 (retired Feb 2024) → no change (already annotated as retired).
- aan-driving-2010 → CURRENT (no newer AAN driving guideline found).
- apa-dementia-antipsy-2016 → CURRENT. No new APA practice guideline found. APA issued a 2026 position statement on access to antipsychotics for BPSD (Assembly May 2026 / Board July 2026). It is a position statement, not a guideline, and I did not open it (see Unverified).
- ags-beers-2023 → CURRENT (no 2026 Beers edition found). UPDATED by the companion paper "Alternative Treatments to Selected Medications in the 2023 AGS Beers Criteria," J Am Geriatr Soc 2025, doi:10.1111/jgs.19500 (https://www.news-medical.net/news/20250818/New-update-to-the-2023-AGS-Beers-Criteria-highlights-safer-pharmacologic-options-for-older-adults.aspx)
- alz-detecd-2024 → CURRENT.
- uspstf-cog-2020 → CURRENT. An update is in progress: the draft research plan was posted 2025-03-06 and finalized, with no draft recommendation yet (https://www.uspreventiveservicestaskforce.org/uspstf/cognitive-impairment-older-adults-screening-draft-research-plan)
- cms-cog-99483 → CURRENT. No CY2026 PFS change to 99483 found.
- cms-guide-2024 → CURRENT. GUIDE is ongoing: the July 2026 MLN fact sheet (MLN7172818) still describes community-dwelling FFS beneficiaries and the PY2026 respite cap of $2,625 (https://www.cms.gov/files/document/mln7172818-guiding-improved-dementia-experience-model.pdf). The July 2026 appendix CR states "no policy changes."
- cms-awv → CURRENT.

### Changes to make
1. **Physical examination (Medication review with AGS Beers Criteria)**
   - CURRENT: "Avoid / deprescribe anticholinergics, benzodiazepines, Z-drugs, first-generation antihistamines; address cumulative anticholinergic burden."
   - NEW: append "Use AGS 2025 Beers Alternatives guidance for non-pharmacologic-first and safer pharmacologic substitutes when deprescribing (identify the underlying cause of the symptom; monitor for symptom recurrence after withdrawal)."
   - Source: ags-beers-alt-2025.
2. **Notes ("Population screening.")**
   - CURRENT: "USPSTF 2020 issued an I-statement…"
   - NEW: append "USPSTF update in progress (final research plan 2025); the I-statement remains operative."
   - Source: uspstf-cog-2020 research-plan page.
3. **Notes ("Routine repeat neuroimaging.")**, informational
   - NEW: append "AAN Etiologic Diagnosis of Dementia guideline is in draft (public comment). The 2001 parameter remains operative until it is finalized."
   - Source: AAN draft URL above. Do not cite the draft content.

### New bibliography entries
- ags-beers-alt-2025 — American Geriatrics Society Beers Criteria® Alternatives Panel. Alternative Treatments to Selected Medications in the 2023 American Geriatrics Society Beers Criteria®. J Am Geriatr Soc. 2025. doi:10.1111/jgs.19500. https://doi.org/10.1111/jgs.19500

### Unverified / flagged
- APA 2026 position statement on access to antipsychotics for BPSD: seen only in a search snippet (psychiatry.org PDF). I did not open it, so it is not used.
- A secondary source (Carlat, Jan 2026) attributes "trial discontinuation after 3–4 months of stability" to "APA 2023." I could not verify this against APA. The monograph's 4-month taper (APA 2016) is retained.
- An AHCA/NCAL blog says residents of dedicated memory-care units are no longer GUIDE-eligible. It is undated and not confirmed in the CMS fact sheet, which still says "community-dwelling." No change made.
- Footnote key "alz-detecd-2024" vs the citation "Alzheimer's Dement. 2025" is a cosmetic inconsistency to reconcile.

### No change needed
Still current: AAN 2001 (reaffirmed 2024), AAN driving 2010, APA 2016, AGS Beers 2023 (core list), Alzheimer's Association DETeCD-ADRD, USPSTF 2020 I-statement, CPT 99483 (180-day), the GUIDE model (2024–2032), and the AWV cognitive-detection requirement.

---

## 19 Breast Cancer (Female)
### Source status
- asco-bca-followup-2013 (Khatcheressian) → SUPERSEDED by Nahleh Z, Alfano CM, Somerfield MR, et al. Breast Cancer Follow-Up and Surveillance After Primary Treatment: ASCO Guideline Update. J Clin Oncol. 2026; doi:10.1200/JCO-26-01700. ASCO Post: "ASCO's last update was in 2013" (https://ascopost.com/issues/september-25-2026/guideline-update-recommends-tailoring-breast-cancer-surveillance-based-on-recurrence-risk/). Detail: https://www.cancernetwork.com/view/top-9-takeaways-from-asco-s-2026-breast-cancer-surveillance-update
- ascoacs-bca-2016 (Runowicz) → CURRENT for survivorship / late-effects content. No ACS/ASCO replacement found. Its surveillance-interval content is now superseded by the 2026 ASCO update.
- asco-cardio-2017 (Armenian) → CURRENT. ASCO listing shows "Current; last updated 2023-03-21" (search excerpt; ace.asco.org not reachable).
- nccn-bca-2025 (v5.2025) → SUPERSEDED by a 2026 version. Secondary sources report v2.2026 (Feb 2026) and v4.2026, plus NCCN education slides for "NCCNbc26" (https://education.nccn.org/sites/default/files/course/2026-02/07_Metastatic_NCCNbc26_v3.pdf). The exact current version number is not verified.
- uspstf-bca-2024 → CURRENT.
- acog-tam-601 → status NOT VERIFIED (ACOG page returned 402). Last known: reaffirmed 2016.

### Changes to make
1. **Summary**
   - CURRENT: "ASCO/ACS (Runowicz 2016) and ASCO Follow-Up (Khatcheressian 2013), still the operative US framework and reinforced by NCCN Breast Cancer v5.2025, call for a detailed cancer-related history and physical exam every 3–6 months for the first 3 years, every 6–12 months years 4–5, then annually…"
   - NEW: "ASCO 2026 (Nahleh) replaces the uniform 2013 follow-up schedule with risk-tiered surveillance. Low intensity (DCIS; stage I HR+ off systemic therapy; TNBC/HER2+ ≥5 yr from diagnosis): annual visit (in-person or virtual), suitable for primary care / survivorship / APP / gynecology. Intermediate (stage I TNBC/HER2+ <5 yr; stage II–III TNBC/HER2+ with pCR; on endocrine therapy): H&P every 6–12 months for 5–10 yr. High (TNBC/HER2+ with residual disease <5 yr; inflammatory BC <10 yr; germline BRCA1/2 / PALB2; HR+ on endocrine + CDK4/6 inhibitor; active systemic therapy): H&P every 3–6 months up to 10 yr, chest-wall exam every 6 months. Runowicz 2016 remains the operative framework for late-effects and survivorship care."
   - Source: asco-bca-followup-2026.
2. **Physical examination (Cancer-related H&P) + At-a-glance**
   - CURRENT: "every 3–6 months for first 3 years; every 6–12 months years 4–5; then annually."
   - NEW: "Risk-tiered (ASCO 2026): low intensity annually; intermediate every 6–12 mo for 5–10 yr; high every 3–6 mo up to 10 yr."
   - At-a-glance: replace "Cancer-related H&P every 3–6 months years 1–3" / "every 6–12 months years 4–5, then annually" with "H&P q3–6 mo (high tier)" (Quarterly / 6-mo cells) and "H&P q6–12 mo (intermediate) / annual (low)" (Annual cell).
   - Source: asco-bca-followup-2026.
3. **Imaging (Mammography) + At-a-glance + Notes**
   - CURRENT: "Mammography of intact breast — annually post-mastectomy (unilateral). Annual bilateral diagnostic mammography post-lumpectomy + radiation."
   - NEW: "Mammography — after BCS: annual for the first 3 years. Then age ≥50 with low-risk features (T1, low grade, node-negative, ER+, recurrence-free at 3 yr) may extend to every 1–2 years (Mammo-50). Age <50 or TNBC/HER2+: remain annual. Annual remains an option by preference. After unilateral mastectomy: annual contralateral. After bilateral mastectomy: not recommended unless symptomatic."
   - Synthesis note: NCCN (annual) is more conservative for the same item. Flag the conflict in Notes and keep "annual" as the default, with de-escalation allowed per ASCO 2026 after shared decision.
   - Source: asco-bca-followup-2026.
4. **Imaging (Breast MRI)**
   - CURRENT: "annually as adjunct to mammography only if ACS high-risk criteria (BRCA1/2, prior chest radiation age 10–30, lifetime risk ≥20%); NOT routine after breast cancer alone."
   - NEW: "Supplemental breast MRI — offer via shared decision for germline carriers (BRCA1/2, PTEN, STK11, TP53, etc.) with intact breast tissue, and chest radiation at age 10–30. Consider when diagnosed <50, invasive lobular histology, cancer missed by / within 12 mo of negative mammogram, or extremely dense breasts. Contrast-enhanced mammography or US if MRI unavailable / contraindicated. No evidence MRI surveillance improves survival."
   - Source: asco-bca-followup-2026.
5. **Laboratory. Add a ctDNA line**
   - NEW: "Circulating tumor DNA (ctDNA / cfDNA) — NOT recommended for recurrence monitoring outside a clinical trial (ASCO 2026)."
   - Mirror it in the At-a-glance Labs "As indicated" cell.
   - Source: asco-bca-followup-2026.
6. **Notes ("DEXA cadence on AI.") and ("Routine surveillance imaging…")**
   - Update the attribution "ASCO / NCCN / ACS" to "ASCO 2026 / NCCN / ACS".
   - Add a Note: "Mammography interval conflict. ASCO 2026 permits every 1–2 yr mammography after 3 recurrence-free years in low-risk BCS patients ≥50 (Mammo-50); NCCN / ACS retain annual. Default annual; de-escalate by shared decision."
   - Source: asco-bca-followup-2026.
7. **Footnotes**
   - Replace footnote 2 (Khatcheressian 2013) with asco-bca-followup-2026.
   - Update the NCCN footnote to "NCCN Breast Cancer, 2026 version (current)."

### New bibliography entries
- asco-bca-followup-2026 — Nahleh Z, Alfano CM, Somerfield MR, et al. Breast Cancer Follow-Up and Surveillance After Primary Treatment: ASCO Guideline Update. J Clin Oncol. 2026. doi:10.1200/JCO-26-01700. https://ascopubs.org/doi/10.1200/JCO-26-01700
- nccn-bca-2026 — NCCN. Clinical Practice Guidelines in Oncology: Breast Cancer, Version [current].2026. https://www.nccn.org/guidelines/guidelines-detail?category=1&id=1419

### Unverified / flagged
- **ASCO 2026 primary text.** The JCO full text returned 403. Details come from ASCO Post (ASCO's own publication) plus CancerNetwork and OncoDaily summaries, which agree with each other.
  - The online publication date differs between sources (July 16 vs Aug 26, 2026).
  - Verify exact wording before publishing, especially the low-risk definition ("stage I HR+ after completing systemic therapy" vs "off all systemic therapy") and the mammography de-escalation criteria.
- **NCCN Breast current version number** (v4.2026 reported by a secondary source); the survivorship surveillance section was not checked.
- **ACOG CO 601 status** could not be opened (402). A 2023 cohort reports increased endometrial cancer risk in premenopausal tamoxifen users, which conflicts with CO 601's premenopausal statement. Not acted on.
- ASCO cardio-oncology 2017: "current, last updated 2023" comes from a search excerpt only.

### No change needed
Still current: the routine CBC / chemistry / LFT / tumor-marker NOT recommended statement (re-endorsed by ASCO 2026), no routine distant-metastasis imaging (re-endorsed by ASCO 2026, 97% consensus), USPSTF 2024 (Grade B, 40–74 biennial; survivors excluded), trastuzumab LVEF schedule (ASCO 2017), DEXA on AI, and the Runowicz 2016 lifestyle and late-effects items.

---

## 20 Asthma
### Source status
- gina-2025 → SUPERSEDED by the 2026 GINA Strategy Report (Global Strategy for Asthma Management and Prevention, 2026 update; released May 2026) (https://ginasthma.org/2026-gina-strategy-report/). Executive summary: "2026 GINA Strategy Report: Executive Summary and Key Changes," Am J Respir Crit Care Med 2026, doi:10.1093/ajrccm/aamag542 (https://ginasthma.org/2026-gina-strategy-report-executive-summary-published/)
- naepp-2020 → CURRENT. No new NAEPP focused update found. The NHLBI page could not be opened (403); secondary sources show the 2020 update is still operative.
- CDC/ACIP vaccine recommendations (cited generically "per ACIP / CDC") → CHANGED:
  - Pneumococcal: routine at age ≥50 with PCV15, PCV20, or PCV21; PPSV23 only after PCV15 (https://www.cdc.gov/vaccines/hcp/imz-schedules/adult-notes.html).
  - RSV: ≥75 all; 50–74 at increased risk, explicitly including chronic lung disease such as asthma; single dose (same CDC page).
  - COVID-19: CDC adopted individual-based decision-making 2025-10-06 (https://cdc.gov/media/releases/2025/cdc-immunization-schedule-adopts-individual-based-decision.html). The CDC 2026–2027 interim guidance, updated 2026-09-23, now states "A 2026-2027 COVID-19 vaccine is recommended for all adults ages 18 years and older," with 2 doses ~6 mo apart for ≥65 (https://cdc.gov/covid/hcp/vaccine-considerations/routine-guidance.html).
- FDA: depemokimab (Exdensur) approved 2025-12-16 as add-on maintenance for severe asthma with eosinophilic phenotype, age ≥12, 100 mg SC every 6 months (https://www.hcplive.com/view/fda-approves-depemokimab-ulaa-exdensur-for-severe-asthma)

### Changes to make
1. **Footnote 1 + all "GINA 2025" mentions (Summary, Notes "Mild asthma reliever.", Notes "LAMA placement.")**
   - CURRENT: "GINA 2025 recommends against SABA-only reliever therapy for all adults / adolescents…"; "GINA 2025 reserves add-on LAMA…"
   - NEW: "GINA 2026…". The substance is unchanged: SABA-only not recommended for adults / adolescents; as-needed low-dose ICS-formoterol at Steps 1–2 (Evidence A); MART from Step 3; add-on LAMA at Step 4–5 then refer for phenotyping.
   - Source: gina-2026 (https://ginasthma.org/2026-gina-strategy-report/); content summary at https://www.2minutemedicine.com/guidelines/gina-asthma/
2. **Functional / surveys (Biologic candidacy assessment)**
   - CURRENT: "Mepolizumab, benralizumab, reslizumab, dupilumab, omalizumab, tezepelumab."
   - NEW: "Mepolizumab, benralizumab, reslizumab, depemokimab (anti-IL-5, SC every 6 months; FDA Dec 2025, age ≥12, eosinophilic phenotype), dupilumab, omalizumab (incl. biosimilar), tezepelumab."
   - Source: fda-depemokimab-2025 (HCPLive / GSK release). GINA 2026 reportedly added depemokimab and an omalizumab biosimilar (see Unverified).
3. **Functional / surveys (Vaccination status) + At-a-glance (Annual) + Summary**
   - CURRENT: "Influenza, COVID-19 per CDC, pneumococcal (PCV20 or PCV15 + PPSV23 per ACIP), RSV per ACIP age criteria, Tdap."
   - NEW: "Influenza annually (age ≥65: HD-IIV3, RIV3, or aIIV3 preferred). COVID-19 per current-season CDC guidance (2026–27: recommended for all adults ≥18; ≥65 two doses ~6 mo apart). Pneumococcal at age ≥50: one dose PCV20 or PCV21, or PCV15 followed by PPSV23 ≥1 yr later. RSV: single dose at ≥75, or at 50–74 with chronic lung disease (asthma qualifies; self-attestation acceptable). Tdap / Td per schedule."
   - At-a-glance: replace "PCV20 or PCV15 + PPSV23, RSV per ACIP" with "PCV20/PCV21 (or PCV15→PPSV23) at ≥50; RSV ×1 at ≥75 or 50–74 with asthma".
   - Summary: "Annual influenza, COVID-19, and pneumococcal vaccinations are standard" → "Annual influenza and current-season COVID-19 vaccination; one-time pneumococcal (≥50) and RSV (≥75, or 50–74 with asthma)."
   - Source: cdc-adult-notes; cdc-covid-2026.

### New bibliography entries
- gina-2026 — Global Initiative for Asthma. Global Strategy for Asthma Management and Prevention, 2026 Update. https://ginasthma.org/2026-gina-strategy-report/
- gina-2026-exec — 2026 Global Initiative for Asthma (GINA) Strategy Report: Executive Summary and Key Changes. Am J Respir Crit Care Med. 2026. doi:10.1093/ajrccm/aamag542. https://doi.org/10.1093/ajrccm/aamag542
- cdc-adult-notes — CDC. Adult Immunization Schedule Notes (pneumococcal, RSV, influenza). https://www.cdc.gov/vaccines/hcp/imz-schedules/adult-notes.html
- cdc-covid-2026 — CDC. 2026–2027 COVID-19 Vaccination Guidance (interim clinical considerations; updated Sept 23, 2026). https://cdc.gov/covid/hcp/vaccine-considerations/routine-guidance.html
- fda-depemokimab-2025 — FDA approval of depemokimab-ulaa (Exdensur) for add-on maintenance treatment of severe asthma with an eosinophilic phenotype, age ≥12; December 16, 2025. https://www.hcplive.com/view/fda-approves-depemokimab-ulaa-exdensur-for-severe-asthma

### Unverified / flagged
- **GINA 2026 change details.** The full report PDF, the executive summary, and the "What's new" deck were not machine-readable (the deck is image-only). These points come from secondary summaries only and are not yet used for text changes beyond the citation year:
  - added biologics (depemokimab, omalizumab-igec biosimilar)
  - "new early anti-inflammatory strategy and flow charts"
  - pediatric Peds-AIRQ
  - any changes to FeNO / eosinophil thresholds, spirometry interval, or remission criteria
  - Re-check the monograph's BEC ≥150/≥300 and FeNO ≥20 ppb thresholds against GINA 2026 before finalizing.
- **COVID-19 federal guidance shifted twice:**
  - Oct 2025: individual-based decision-making for all ages.
  - Sept 2026: CDC page reads "recommended for all adults ≥18."
  - The CDC adult schedule-notes page I fetched still shows a "last updated July 2, 2025" COVID entry.
  - Write the vaccine line as "per current-season CDC guidance" and re-verify at publication.
- **NAEPP.** The NHLBI asthma page (403) reportedly lists "Focused Updates… 2026" in a snippet. Another search attributes that label to page labeling of the 2020 document. Not confirmed. Re-check https://www.nhlbi.nih.gov/health-topics/asthma-for-health-professionals.
- **FDA depemokimab approval.** Confirmed via trade press (HCPLive, citing the GSK release), not via an FDA page.

### No change needed
Still current: NAEPP 2020 statements (FeNO conditional, SLIT conditional-against, SCIT in non-severe disease, multicomponent allergen mitigation), the spirometry cadence, the ACT/ACQ every visit, the inhaler technique, adherence, and action-plan items, and the exacerbation follow-up cadence (GINA: follow up within days after an exacerbation, consistent with "within 1 week").
