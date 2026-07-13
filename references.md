# References Index

**Instructions:** every time a new paper is added to `01_papers/`, add a row here. Every time a paper is actually cited in a chapter, mark it in the "Cited in" column. This file is what you paste at the start of a new AI session so the assistant has full context without needing to re-read every PDF.

Status legend: 🟢 fully verified (read in full, citation details confirmed) · 🟡 in repo, filename/topic known but full citation details (authors, exact title, journal/pages) not yet verified against the actual PDF text · 🔴 not yet obtained

**Rebuilt 2026-07-13** directly from `git ls-files 01_papers/` — this version replaces the previous references.md, which had drifted out of sync with the repo (several held papers were missing, several listed papers didn't exist in the repo). See log entry 2026-07-13 for the reconciliation.

---

## API Standards (foundational)

| Filename | Status | Focus | Key relevance | Cited in |
|---|---|---|---|---|
| API_2010_13A_SpecificationDrillingFluidsMaterials.pdf | 🟢 | Specification for Drilling Fluids Materials, 18th Ed. (ANSI/API SPEC 13A, ≈ ISO 13500:2009) | Primary specification standard the whole thesis benchmarks against (Table 1 in proposal) | Methodology, Results (pending) |
| API_2024_13B1_TestingWaterBasedDrillingFluids_6thEdBallotDraft.pdf | 🟢 | Testing Water-based Drilling Fluids, 6th Ed. Ballot Draft (verify final published edition before defense) | Test procedures (PV, YP, gel strength, API fluid loss) — governs Phase 3 methodology | Methodology |

## Core deposit

| Filename | Status | Country/Deposit | Key relevance | Cited in |
|---|---|---|---|---|
| Alshameri_2013_YemenBentoniteCharacterization.pdf | 🟢 | Yemen / Alaslaf | Only existing mineralogical characterization of the deposit — CEC, swelling, XRD, chemical composition. Basis for Na/Ca ratio risk flag | Chapter 1 |

## Local clay benchmarking (international precedent)

| Filename | Status | Country/Deposit | Key relevance | Cited in |
|---|---|---|---|---|
| Khan_2017_ImprovementofLocallyRawBentonite.pdf | 🟡 | Pakistan (per prior notes — reverify against PDF; filename changed from earlier `Khan_2017_PakistaniBentoniteDrillingMud.pdf`) | Primary methodological template — raw clay vs. Mill Gel, improved with xanthan/CMC/starch | Chapter 1, proposal |
| AlHomadhi_2007_SaudiKhulaysBentoniteSPE.pdf | 🟡 | Saudi Arabia / Khulays | Closest precedent — Ca-bentonite activated with 5% Na2CO3 + Drispac polymer, ~200% viscosity increase | Chapter 1 |
| Akinwumi_2015_NigeriaAbbiClayAPI.pdf | 🟢 | Nigeria / Abbi, Delta State | API 13A/13B benchmarking, partial-deficiency-then-beneficiation outcome pattern | Chapter 1, thesis rating discussion |
| Hassan_1998_EgyptGabalHamdalBentoniteBeneficiation.pdf | 🟡 | Egypt / Gabal Hamdal | **Resolves prior "Egyptian Gabal Hamdal" gap.** Counter-example: poor Na-exchange response, low smectite purity — important for balanced risk framing | Chapter 1 (citation to be finalized) |
| Magzoub_2014_SaudiKhulaysBentoniteThermoChemicalMScThesis.pdf | 🟡 | Saudi Arabia / Khulays | **Resolves prior "Magzoub KFUPM thesis" gap — already obtained.** Full M.Sc. thesis, close structural template for chapter organization | Chapter 1 |
| Magzoub_2018_ThermochemicalUpgradingCaBentonite_JERT.pdf | 🟡 | Saudi Arabia / Khulays | Journal (JERT) companion paper to the 2014 Magzoub thesis — thermochemical upgrading of Ca-bentonite | Chapter 1 |
| Manoufali_2016_SudanEdDamazinBentoniteDrillingMud.pdf | 🟡 | Sudan / Ed-Damazin | **Resolves prior "Manoufali 2016" gap — already obtained.** Regional (Sudan) precedent, strengthens regional-not-just-cross-continental framing | Chapter 1 |

## Methodology / RSM / Box-Behnken

| Filename | Status | Country/Focus | Key relevance | Cited in |
|---|---|---|---|---|
| Afolabi_2018_NigeriaBentoniteRSM_DataInBrief.pdf | 🟡 | Nigeria | RSM data-in-brief companion paper; note this uses Kelzan XCD (xanthan derivative) — relevant to Tier 4 xanthan gum gap too | Chapter 1 |
| Alhajabdalla_2021_RSM_FibrousDispersion_ACSOmega.pdf | 🟡 | Qatar/general | RSM/BBD for fibrous dispersion stability in drilling fluids | Chapter 1 |
| Asmungi_2021_RSM_BoxBehnken_BentoniteTanninXanthan_WBM.pdf | 🟡 | — | Box-Behnken design, tannin + xanthan water-based mud optimization | Chapter 1 |
| Ossai_2025_BoxBehnken_DrillingMud_NigeriaLocalMaterials.pdf | 🟡 | Nigeria | Box-Behnken, local-materials drilling mud optimization — recent (2025) precedent | Chapter 1 |
| Satiyawira_2025_RSM_BoxBehnken_DrillingFluidOptimization_SCOG.pdf | 🟡 | — | RSM/Box-Behnken drilling fluid optimization, published in SCOG — recent (2025) precedent | Chapter 1 |
| README.md | — | — | Folder notes file, not a paper | — |

## Na-activation mechanism (clay chemistry)

| Filename | Status | Focus | Key relevance | Cited in |
|---|---|---|---|---|
| Bahranowski_2021_RehydrationNaActivationBentonite.pdf | 🟡 | General clay chemistry | **Partially resolves prior "Na-activation/cation exchange mechanism" gap.** Rehydration and Na-activation mechanism, not application-specific | Chapter 1/2 |

## Yemen geology / context

| Filename | Status | Focus | Key relevance | Cited in |
|---|---|---|---|---|
| Ahmed_2019_AlHururAbyanClay.pdf | 🟢 | Yemen / Al-Harur, Abyan | Cautionary secondary indicator — low-grade clay, different depositional setting | Chapter 1 |
| Belder_1998_YemenAlIrrahSoilsFAO.pdf | 🟡 | Yemen / Al-Irrah | FAO soils report, general Yemen geological/soils background | Background only |
| FAO_1996_YemenSoilSeriesFramework.pdf | 🟢 | Yemen (national) | General soil/geology background, not montmorillonite-specific | Background only |
| Lezine_1998_YemenHoloceneLakesPaleoclimate.pdf | 🟡 | Yemen | Low priority — paleoclimate/lake context, background only | Background only (optional) |

---

## Papers previously flagged as missing that you actually already have (corrected this session)

- ~~Manoufali et al. 2016 (Sudan)~~ → in repo, `local_clay_benchmarking/Manoufali_2016...pdf`
- ~~Magzoub KFUPM M.Sc. thesis~~ → in repo, `local_clay_benchmarking/Magzoub_2014...pdf`
- ~~Egyptian Gabal Hamdal beneficiation~~ → in repo, `local_clay_benchmarking/Hassan_1998...pdf`
- ~~Lézine et al. 1998~~ → in repo, `yemen_geology_context/Lezine_1998...pdf`

## Papers listed in a prior version of this file that do NOT exist in the repo (removed — re-add only if actually downloaded)

- `Nlemedin_2023_IkwoClayOilBasedMud.pdf` — not in repo
- `Zaid_2021_YemenExpansiveSoilsHazard.pdf` — not in repo
- `Maulani_2024_RSM_BoxBehnken_CMC_AlkalinePolymer.pdf` — not in repo
- `Egyptian_ElFayoum_KomOshim_NanoBentonite.pdf` — not in repo, still genuinely missing (see gap list below)

## Papers still genuinely needed (not in repo, confirmed gaps)

**Tier 1 — finish existing threads**
- [x] ~~Afolabi, Orodu & Efevobkhan 2017, *Applied Clay Science* 143:39–49 (Nigerian bentonite review) — distinct from the 2018 Afolabi Data in Brief paper already held~~
- [x] ~~Agwu, Okon & Udoh 2015, SPE Nigeria Conference (Nigerian bentonite review)~~
- [x] ~~Falode, Ehinola & Nebeife 2008, *Applied Clay Science* 39:19–27~~
- [ ] Egyptian El-Fayoum/Kom-Oshim source (Ibrahim 1988 PhD thesis; Ibrahim, Felix & Ismail 1994; Inglethorpe et al. 1993)

**Tier 2 — foundational/textbook references**
- [ ] Darley & Gray, *Composition and Properties of Drilling and Completion Fluids*
- [ ] Grim, R.E., *Clay Mineralogy*
- [ ] Rheological models comparison reference (Bingham/power-law/Herschel-Bulkley)
- [ ] Montgomery, *Design and Analysis of Experiments* (or Myers/Montgomery/Anderson-Cook RSM text)
- [ ] Derringer & Suich 1980, *Journal of Quality Technology* (desirability function)

**Tier 3 — regional comparator net**
- [ ] Other Gulf/Middle East bentonite studies (UAE, Oman, Jordan, Iraq nuclear-waste paper, Iran Khorasan-Yazd paper)
- [ ] Karagüzel et al. 2010 (seawater/soda-ash Ca-bentonite upgrading)
- [ ] Mahmoud et al. 2019 (Na-activation, drilling-mud-specific)
- [ ] Additional Yemen mineral/clay occurrence reports (Yemen Ministry of Oil and Minerals / Yemeni Geological Survey Authority)

**Tier 4 — methodology specifics for Chapter 3**
- [ ] General CMC mechanism reference (fluid-loss/viscosifier, independent of Khan 2017/Al-Homadhi 2007 applied mentions)
- [ ] General xanthan gum/biopolymer mechanism reference (beyond Afolabi 2018's applied use of Kelzan XCD)
- [ ] Wyoming bentonite reference composition/benchmark paper
- [ ] Hydrocyclone/attrition-scrubbing beneficiation method reference (standalone mineral-processing source)

**Tier 5 — Yemen economic/context data (optional)**
- [ ] Yemen bentonite/drilling-fluid import statistics (UN Comtrade, Yemen Central Statistical Organization)
- [ ] Yemen oil & gas sector overview / drilling activity reports (demand-scale figure, cf. Al-Homadhi's Saudi "100,000 tons/year" framing)

**Tier 6 — journal-target formatting**
- [ ] 2–3 recent JPEPT articles on similar bentonite/drilling-fluid topics, for structure/citation-density/figure conventions

## How to add a new paper (workflow)

1. Download the PDF, rename it to `AuthorLastName_Year_ShortTopic.pdf`
2. Place it in the correct subfolder under `01_papers/`
3. Add a row to the relevant table above with status 🟡 (until fully read) or 🟢 (once verified)
4. Note in `05_meeting_notes/log.md` that it was added and why
