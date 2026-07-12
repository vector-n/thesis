# References Index

**Instructions:** every time a new paper is added to `01_papers/`, add a row here. Every time a paper is actually cited in a chapter, mark it in the "Cited in" column. This file is what you paste at the start of a new AI session so the assistant has full context without needing to re-read every PDF.

Status legend: 🟢 fully verified (read in full, citation details confirmed) · 🟡 found via search/snippet only, needs full verification · 🔴 not yet obtained

---

## API Standards (foundational)

| Filename | Year/Edition | Status | Focus | Key relevance | Cited in |
|---|---|---|---|---|---|
| API_2010_13A_SpecificationDrillingFluidsMaterials.pdf | 2010, 18th Ed. (ANSI/API SPEC 13A, identical to ISO 13500:2009) | 🟢 | Specification for Drilling Fluids Materials | The primary specification standard your entire thesis benchmarks against (Table 1 in proposal) | Methodology, Results (pending) |
| API_2024_13B1_TestingWaterBasedDrillingFluids_6thEdBallotDraft.pdf | 6th Ed., Ballot Draft (not yet finalized — verify current published edition before defense) | 🟢 | Testing Water-based Drilling Fluids | Test procedures (PV, YP, gel strength, API fluid loss) — directly governs your Phase 3 methodology | Methodology |

## Core deposit

| Filename | Year | Status | Country/Deposit | Key relevance | Cited in |
|---|---|---|---|---|---|
| Alshameri_2013_YemenBentoniteCharacterization.pdf | 2013 | 🟢 | Yemen / Alaslaf | Only existing mineralogical characterization of the deposit. Source of CEC, swelling, XRD, chemical composition data. Basis for Na/Ca ratio risk flag. | Chapter 1 |

## Local clay benchmarking (international precedent)

| Filename | Year | Status | Country/Deposit | Key relevance | Cited in |
|---|---|---|---|---|---|
| Khan_2017_PakistaniBentoniteDrillingMud.pdf | 2017 | 🟢 | Pakistan / Jhelum, Jundola | Primary methodological template — raw clay vs. Mill Gel, improved with xanthan/CMC/starch | Chapter 1, proposal |
| AlHomadhi_2007_SaudiKhulaysBentoniteSPE.pdf | 2007 | 🟡 | Saudi Arabia / Khulays | Closest precedent — Ca-bentonite activated with 5% Na2CO3 + Drispac polymer, ~200% viscosity increase | Chapter 1 |
| Akinwumi_2015_NigeriaAbbiClayAPI.pdf | 2015 | 🟢 | Nigeria / Abbi, Delta State | API 13A/13B benchmarking, partial-deficiency-then-beneficiation outcome pattern | Chapter 1, thesis rating discussion |
| Nlemedin_2023_IkwoClayOilBasedMud.pdf | 2023 | 🟡 | Nigeria / Ikwo | Comparative bentonite vs. local clay, oil-based mud | Chapter 1 |
| Magzoub_KFUPM_MScThesis_SaudiBentoniteStabilization.pdf | — | 🔴 | Saudi Arabia / Khulays | Full M.Sc. thesis, close structural template — NOT YET DOWNLOADED, recommended | — |
| Egyptian_GabalHamdal_AbuZeneima_Beneficiation.pdf | — | 🔴 | Egypt / Sinai | Counter-example: poor Na-exchange response, low smectite purity. Important for balanced risk framing | Chapter 1 (citation incomplete) |
| Egyptian_ElFayoum_KomOshim_NanoBentonite.pdf | — | 🔴 | Egypt / El-Fayoum | NaOH + POLYPAC-R activation; non-activated samples unusable as-is | Chapter 1 (citation incomplete) |

## Methodology / RSM / Box-Behnken

| Filename | Year | Status | Focus | Key relevance | Cited in |
|---|---|---|---|---|---|
| Maulani_2024_RSM_BoxBehnken_CMC_AlkalinePolymer.pdf | 2024 | 🟡 | Indonesia | RSM/BBD precedent for multi-factor mud optimization across temperatures | Chapter 1 |
| Alhajabdalla_2021_RSM_FibrousDispersion_ACSOmega.pdf | 2021 | 🟡 | Qatar/general | RSM/BBD for fibrous dispersion stability in drilling fluids | Chapter 1 |

## Yemen geology / context

| Filename | Year | Status | Focus | Key relevance | Cited in |
|---|---|---|---|---|---|
| Zaid_2021_YemenExpansiveSoilsHazard.pdf | 2021 | 🟢 | Yemen / Taiz | Regional confirmation montmorillonite-forming processes active elsewhere in Yemen | Chapter 1 |
| Ahmed_2019_AlHururAbyanClay.pdf | 2019 | 🟢 | Yemen / Al-Harur, Abyan | Cautionary secondary indicator — low-grade clay, different depositional setting | Chapter 1 |
| FAO_1996_YemenSoilSeriesFramework.pdf | 1996 | 🟢 | Yemen (national) | General soil/geology background, not montmorillonite-specific | Background only |

---

## Papers still needed (gaps to fill in Phase 0 literature review)

- [ ] Full verified citations for the Egyptian Gabal Hamdal and El-Fayoum studies (currently 🟡/🔴, found via search snippets only)
- [ ] Magzoub KFUPM M.Sc. thesis — full PDF
- [ ] Broader RSM-in-drilling-fluids literature beyond the 2 papers currently held
- [ ] General montmorillonite/smectite mineralogy and rheology textbook or review reference (for Chapter 2 background section) — e.g. Darley & Gray, or a clay mineralogy review
- [ ] Sodium activation / cation exchange mechanism papers (general clay chemistry, not just applications)
- [ ] General RSM/DOE statistics reference (non-drilling-specific, for methodological rigor citation)
- [ ] Additional Nigeria/Saudi/Egypt comparator studies if available, to strengthen the "genre" argument in Chapter 1 Section 1.3
- [ ] Economic feasibility / import-substitution framing references (optional, supports Section 8)
- [x] ~~API 13A specification~~ — obtained 2010 18th Ed.
- [x] ~~API 13B-1 testing procedures~~ — obtained 6th Ed. ballot draft (verify final edition before defense)

## How to add a new paper (workflow)

1. Download the PDF, rename it to `AuthorLastName_Year_ShortTopic.pdf`
2. Place it in the correct subfolder under `01_papers/`
3. Add a row to the relevant table above with status 🟡 (until fully read) or 🟢 (once verified)
4. Note in `05_meeting_notes/log.md` that it was added and why
