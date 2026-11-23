# CMID revision — November 2026

**Revision date:** 2026-11-23 (previous build 2026-05-11)
**Scope:** all 30 condition monographs, plus the two companion sites that draw on them.

| Site | Commit | What changed |
|---|---|---|
| [CMID top thirty](https://patrickrutledge.github.io/topthirty/) | `55c3da3` | 336 text edits, footnoted to new sources; bibliography corrected; "November 2026 update" section added |
| [Medicare preventive services](https://patrickrutledge.github.io/preventative_services/) | `a13e15e`, `7fffed6` | All 32 services on CMS MLN006559 (Oct 2026) and every listed code |
| [Designed visits](https://patrickrutledge.github.io/designed_visits/) | `bc2efe7` | Updated CMID monitoring content plus a "Medicare preventive" tab per visit |

## Method

- Every cited source was checked on the issuing body's own page or its PubMed/PMC record for anything published after 2026-05-11. Sources checked included guidelines, USPSTF statements, CMS NCDs and LCDs, CDC vaccine guidance and FDA labels.
- Changes were applied only when the primary source, or the issuer's own summary, confirmed them. Items confirmed only from secondary coverage (trade press, search snippets) were **not** changed and are listed under *Open items* below.
- When sources disagree, the most conservative interval wins (synthesis rule), and the conflict is described in that condition's Notes.
- The edits were made directly in the rendered `index.html`. **The markdown source (`cmid/`) was not available and is now out of date.** Regenerating the site from markdown would undo this revision.

## Superseded sources replaced

| # | Condition | Edits | Old source → new source |
|---|---|---|---|
| 01 | Hypertension | 16 | ACC/AHA 2017 → **2025 AHA/ACC High BP guideline** (Jones, Hypertension 2025;82(10):e212). PREVENT risk; UACR for all patients with hypertension; aldosterone:renin ratio in resistant HTN |
| 02 | Hyperlipidemia | 12 | ACC/AHA 2018 → **2026 ACC/AHA Dyslipidemia** (Blumenthal, Circulation 2026;153(17):e1154). PREVENT-ASCVD strata; non-HDL goals; Lp(a); apoB |
| 03 | RA / OA | 15 | AAO HCQ 2016 → AAO 2025 revision (Ophthalmology 2026); EULAR 2019 → EULAR 2025; ACR 2026 OA summary |
| 04 | BPH | 13 | AUA 2023 → **AUA 2026 LUTS/BPH guideline** |
| 05 | Diabetes | 26 | ADA 2025 → **ADA Standards of Care 2026**; AACE 2023 → AACE 2026 algorithm |
| 06 | Cataract | 5 | AAO Adult Eye Evaluation PPP 2020 → 2026 PPP |
| 07 | Ischemic heart disease | 17 | 2026 dyslipidemia applied; cardiac rehab NCD 20.10 (retired) → 42 CFR §410.49 |
| 08 | Anemia | 20 | KDIGO 2012 → **KDIGO 2026 Anemia in CKD**; ASH 2025 draft → ASH 2026 final iron-deficiency diagnosis |
| 09 | Hypothyroidism | 2 | ATA 2017 pregnancy → ATA 2026 preconception/pregnancy/postpartum (citation only; see open items) |
| 10 | Mood disorders | 9 | IGSLi/ISBD 2026 lithium–kidney guidance; screening wording |
| 11 | CKD | 30 | KDIGO 2026 anemia; 2025 BP guideline in Notes; finerenone label (Sept 2026) |
| 12 | Glaucoma | 9 | AAO 2025/2026 glaucoma PPPs (3 further edits held; see open items) |
| 13 | AF / flutter | 6 | 2026 AF performance measures; NCD 20.34 reviewed |
| 14 | COPD | 34 | GOLD 2025 → **GOLD 2027** |
| 15 | Heart failure | 26 | ACC HFpEF ECDP 2023 → **2026 HFpEF ECDP** (Kittleson, JACC 2026) |
| 16 | Osteoporosis | 7 | USPSTF 2025; NCD 150.3 checked |
| 17 | Prostate cancer | 31 | NCCN v1.2025 → v5.2026; AUA/ASTRO/SUO 2026 amendments |
| 18 | Non-Alzheimer dementia | 3 | Minor currency updates |
| 19 | Breast cancer | 19 | ASCO 2013 → **ASCO 2026 follow-up guideline** (risk tiers); NCCN 2025 → 2026 |
| 20 | Asthma | 7 | GINA 2025 → **GINA 2026** |
| 21 | Stroke / TIA | 16 | 2025 BP and 2026 lipid guidelines in Notes; 2026 AHA/ASA stroke rehabilitation |
| 22 | Alzheimer's | 11 | Lecanemab label (rev. 7/2026; SC initiation, MRI schedule); donanemab label |
| 23 | Parkinson's | 4 | Vaccine wording |
| 24 | Colorectal cancer | 1 | NCCN version note (v2.2026 or later; not confirmed) |
| 25 | Acute MI | 10 | Cardiac rehab → 42 CFR §410.49; 2026 lipid guideline |
| 26 | Pneumonia | 11 | CDC COVID 2025 → 2026–27; pneumococcal ≥50; RSV ≥75 / 50–74 at risk; ATS 2025 CAP update |
| 27 | Lung cancer | 11 | NCCN NSCLC, SCLC and LCS → v1.2027; Survivorship v3.2026; Smoking Cessation v2.2026; ICI toxicity v1.2026 (bibliography URLs corrected) |
| 28 | Hip fracture | 2 | Minor currency updates |
| 29 | Endometrial cancer | 5 | NCCN Uterine v3.2026; SGO 2026 surveillance (Salani, Gynecol Oncol 2026;204:109) |
| 30 | Urologic cancer | 10 | AUA/SUO NMIBC 2026 amendment; AUA/ASCO/ASTRO/SUO MIBC; NCCN Kidney v2.2027 |

**Still current (no change):** USPSTF hypertension 2021, statin 2022 and osteoporosis 2025; ACC/AHA 2023 chronic coronary disease guideline; AHA 2023 AF guideline; ACC/AHA 2022 HF guideline.

## Vaccines — check again at every refresh

- On 2026-03-16 a court order in *AAP v. Kennedy* (D. Mass.) paused the ACIP/CDC changes made after 2025-06-11. This mostly reverts the adult schedule to January 2025.
- The 1st Circuit appeal (No. 26-1503) was argued around 2026-10-06, and no decision had been found. If the order is reversed, COVID-19 vaccination goes back to shared clinical decision-making.
- The CDC page currently reads "A 2026–2027 COVID-19 vaccine is recommended for all adults ages 18 years and older," but it carries conflicting update dates.
- mFlusiva (an mRNA flu vaccine, FDA-approved 2026-08-05 for adults ≥50) has no CDC preference statement. Per the synthesis rule, the CDC wording is what the monographs show.

## Open items (not changed — need full text or a decision)

### Paywalled or login-gated; confirmed only from secondary sources

- **01 / 11 / 21:** whether the 2025 BP guideline "encourages SBP <120 if tolerated." Many 2017-era monitoring items in the hypertension monograph are still footnoted to 2017 until the 2025 full text is checked (BMP/K⁺ cadence, ECG, echo, fundoscopy, ABI, visit cadence).
- **02 / 07 / 21 / 25:** the 2026 dyslipidemia guideline's lipid re-check interval and its very-high-risk definition (Table 2), which decides whether LDL-C <55 applies after a single MI or stroke. The AFP editorial says "within 12 weeks, then annually," which conflicts with the monographs' 4–12 weeks then every 3–12 months; the more conservative interval is kept.
- **04:** the 2026 BPH details (PSA on 5-ARI, creatinine, Qmax, DRE, watchful-waiting cadence) came from Urology Times and PubMed only. AUA restricts AI use of guideline content, so a person should check them against the full text.
- **09:** the specifics of the ATA 2026 pregnancy guideline (TSH interval, target, LT4 dose increase, TPOAb role) are unconfirmed. The TPOAb "TSH >2.5" line is probably outdated.
- **12:** three glaucoma edits were held because they rest only on secondary sources: post-LPI follow-up, corneal hysteresis, and an OCT note.
- **15:** the monitoring details in the 2026 HFpEF ECDP (natriuretic peptides, KCCQ, follow-up, amyloid and iron screening).
- **17 / 19 / 24 / 27 / 29 / 30:** NCCN surveillance tables, which need a login. The current version numbers are recorded, but the intervals were not re-read. The ASCO 2026 breast details came from ASCO Post and two other summaries.
- **21:** the DAPT window changes in the 2026 AIS guideline (NIHSS ≤5, 24–72 h, CYP2C19-guided ticagrelor).
- **25:** β-blocker duration after MI (2025 ACS guideline; REDUCE-AMI, REBOOT, BETAMI-DANBLOCK) and colchicine's class after CLEAR SYNERGY.

### Errors inside the monographs (found, not yet fixed)

- **21 Stroke:** the at-a-glance cell says "INR weekly during DOAC initiation / change". INR does not monitor DOACs. Replace with "Cr/eGFR + CBC at DOAC initiation / dose change."
- **22 Alzheimer's:** the Summary says "MMSE 20–30" and Functional says "MMSE 22–30", while the labels specify neither. Harmonize to "MCI or mild dementia stage."
- **25 Acute MI:** the β-blocker threshold appears as both "LVEF <50%" and "LVEF ≤50%."
- **27 Lung cancer (SCLC):** chest CT appears as both "every 2–6 mo × 1 yr" (at-a-glance) and "every 2–3 mo × yr 1" (Imaging).
- **08 Anemia:** "AGA suggests ≥50" ferritin after iron therapy has no AGA source. Re-source it or remove it.
- **06 Cataract:** LCD L37027 returned "Invalid LCD Version" and may be retired or renumbered.
- **Cosmetic:** the bibliography key `alz-detecd-2024` cites a 2025 paper, and `aan-pd-qm-2021` is the 2020 measure set.

### Pending publications to watch

- ADA Standards of Care 2027 (expected December 2026)
- KDIGO 2026 Diabetes in CKD and 2027 CKD Medications focused updates
- AGS Beers 2026
- AACE osteoporosis update
- ASH iron-deficiency treatment guideline (possibly 2027)
- USPSTF prostate cancer screening update (in progress)
- USPSTF CKD screening (2012 statement inactive; update in progress)
- The CMS NCD 200.3 (anti-amyloid mAbs) reconsideration

## Companion site changes

### Medicare preventive services

- **Coverage:** the site now covers all 32 services on CMS MLN006559 (October 2026). New cards: flu, pneumococcal, hepatitis B and COVID-19 vaccines; DSMT; MNT; MDPP; and prolonged preventive services. Each card shows coverage, frequency and patient cost, with a link to the CMS chart.
- **Codes corrected:**
  - G0389 → 76706
  - G0297 → 71271 / G0296
  - 86703 → G0475
  - 86803 → G0472
  - G0539 / G0540 → G0011 / G0013
  - G9873 → G9886
  - 87624 → G0476
  - 88142 → G0123
  - IPPE ECG added as G0403

### Designed visits

- **CMID content:** each visit's monitoring and care-cascade content was regenerated from the revised CMID text.
- **New "Medicare preventive" tab** on each visit:
  - the services that apply to the condition, with codes, coverage and a reason for each;
  - cautions where a screening benefit no longer applies after diagnosis (for example PSA in prostate cancer, or colonoscopy in colorectal cancer). Cardiac and pulmonary rehab are noted as not being preventive services.
  - the core set for every Medicare patient: AWV, ACP, depression, alcohol, tobacco, flu, pneumococcal, COVID-19, HIV, HCV, IBT for CVD, and prolonged preventive services.
- **Built into each visit:**
  - the top three preventive services as care-cascade "enroll" steps;
  - an A&P step (8) to close preventive gaps;
  - a pre-visit eligibility task for the MA / care coordinator;
  - a billing row noting that preventive services are billed separately from the E/M.

## Next refresh

Recommended by **May 2027**, or sooner when any of these happens:
- ADA 2027 is released;
- the 1st Circuit rules in *AAP v. Kennedy*;
- CMS publishes the CY2027 PFS final rule and an updated MLN006559.

Before the next refresh, resolve the open items above. Then either regenerate the markdown source from this HTML or apply the same changes to it.
