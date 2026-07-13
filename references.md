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
| AlHomadhi_2007_SaudiKhulaysBentoniteSPE.pdf | 2007 | 🟢 | Saudi Arabia / Khulays | SPE 110951. Ca-bentonite activated with Na2CO3 (soda ash) extender + Drispac polymer; 8% enhanced local bentonite matched 7% imported bentonite performance; cost <46% of imported. | Chapter 1 |
| Magzoub_2014_SaudiKhulaysBentoniteThermoChemicalMScThesis.pdf | 2014 | 🟢 | Saudi Arabia / Khulays, N. Jeddah | Musaab Ibrahim Magzoub Elhag, KFUPM M.Sc. thesis (advisor: Dr. Mohamed Mahmoud). Same Khulays deposit as Al-Homadhi 2007. Thermo-chemically upgraded Ca-bentonite reported to outperform commercial standard bentonite. Worth contrasting directly against Al-Homadhi's near-parity outcome. | Chapter 1 (comparator), Methodology (thermo-chemical activation precedent) |
| Hassan_1998_EgyptGabalHamdalBentoniteBeneficiation.pdf | 1998 | 🟢 (full text obtained and verified this session) | Egypt / Gabal Hamdal (Miocene), Abu-Zeneima, Sinai | Hassan, M.S.; Abdel-Khalek, N.A. *Applied Clay Science* 13(2), 99–115. Low-grade Ca–Mg smectite (calcite/kaolinite/quartz/feldspar/dolomite gangue); MB-CEC only 40–43 meq/100g (low end of 40–120 commercial range); ROM swelling index 20–25, poor Na-exchange, ROM viscosity below API minimum. Beneficiation (crush → attrition scrub → 2" hydrocyclone → 0.5M HCl leach) removed most calcite/quartz, raised Al2O3 from 5.6–7.6% to 15.40%, CaO down to 1.77%. After beneficiation + 3–5% Na2CO3 activation: swelling index >100, PV 9–10 cP (within Meycogel/Wyoming range), exceeded API 13A drilling-mud requirements, bleaching ability 20%→55%→>90% (ROM→pre-concentrate→final). Cost US$21–30/t vs. US$150–400/t imported — strong economic comparator. **Does NOT describe NaOH+POLYPAC-R activation** (that remains a separate, still-unconfirmed source — see El-Fayoum row below) — but its reference list gives exact leads: Ibrahim, I.A. 1988 PhD thesis (Cairo University); Ibrahim, Felix & Ismail 1994; Inglethorpe et al. 1993. | Chapter 1 (counter-example/risk framing + economic comparator) |
| Egyptian_ElFayoum_KomOshim_NanoBentonite.pdf | — | 🔴 | Egypt / El-Fayoum, Kom-Oshim | NaOH + POLYPAC-R activation; non-activated samples unusable as-is. Still not the same paper as Hassan & Abdel-Khalek 1998. **New leads to chase** (from Hassan & Abdel-Khalek's own bibliography): Ibrahim, I.A. (1988) PhD Thesis, Cairo University, "Processing of Egyptian bentonites for industrial application"; Ibrahim, Felix & Ismail (1994) "Improvement of the rheological properties of Egyptian bentonitic clay through alkali activation," 1st Int. Symp. Ind. Appl. Clays, Cairo; Inglethorpe, Bloodworth & Razak (1993) Br. Geol. Surv. Tech. Report. | Chapter 1 (citation incomplete) |
| Akinwumi_2015_NigeriaAbbiClayAPI.pdf | 2015 | 🟢 | Nigeria / Abbi, Delta State | API 13A/13B benchmarking, partial-deficiency-then-beneficiation outcome pattern | Chapter 1, thesis rating discussion |
| Nlemedin_2023_IkwoClayOilBasedMud.pdf | 2023 | 🟡 | Nigeria / Ikwo | Comparative bentonite vs. local clay, oil-based mud | Chapter 1 |
| Manoufali_2016_SudanEdDamazinBentoniteDrillingMud.pdf | 2016 (Oct) | 🟡 (citation confirmed; full text not yet obtained) | Sudan / Ed-Damazin, Blue Nile State | Manoufali, O.A.A.; Ali, M.H.A.; Ahmed, M.A.K.; Marghani, M.F. "Evaluation of Local Bentonite for Utilization as Oil Well Drilling Mud (Ed-Damazin Sample)," Sudan University of Science & Technology. Same genre as Khan/Al-Homadhi/Akinwumi. **Upload PDF to upgrade to 🟢.** | Chapter 1 (pending) |
| Afolabi_2018_NigeriaBentoniteRSM_DataInBrief.pdf | 2018 | 🟢 (full text obtained and verified this session) | Nigeria / Ewekoro, Ogun State | Afolabi, R.O.; Ogunkunle, T.F.; Olabode, O.A.; Yusuf, E.O. *Data in Brief*, DOI 10.1016/j.dib.2018.07.071. **Note: uses a Central Composite Design (CCD, 2⁴ two-level four-factor, 31 runs, star points at ±2), not Box-Behnken** — still RSM family, but a different design structure than your thesis's planned BBD; useful comparator, not an identical template. Factors: Bentonite (20–40g), Kelzan XCD polymer (2.5–12.5g), Na2CO3 (2–10g), ageing time (5–25h). Na-saturation done at 2–10g Na2CO3 per 25–50g clay + pH adjusted to 11–12 with 0.1M NaOH, aged 5–48h. YP/PV ratio (≤3 per API 13-A) was primary response; all 4 factors significant (polymer most significant, F=171.1); model R²=0.9411. Software: Minitab 17 — same tool your proposal specifies. | Chapter 1/2 (RSM precedent), Methodology (Minitab precedent) |
| Afolabi_2017_NigeriaBentoniteReview_AppliedClaySci.pdf | 2017 | 🔴 (new lead, found in Afolabi 2018's reference list — not yet obtained) | Nigeria (review, multiple deposits) | Afolabi, R.O.; Orodu, O.D.; Efevobkhan, V.E. "Properties and application of Nigerian bentonite clay deposits for drilling mud formulation: recent advances and future prospects." *Applied Clay Science* 143, 39–49. Appears to be a **review paper** — potentially very useful as a single source summarizing multiple Nigerian deposits/studies for Chapter 1/2, reducing need to chase each individually. **High priority to obtain.** | Chapter 1/2 (review source, pending) |
| Agwu_2015_NigeriaBentoniteReview_SPE.pdf | 2015 | 🔴 (new lead, found in Afolabi 2018's reference list — not yet obtained) | Nigeria (review) | Agwu, O.E.; Okon, A.N.; Udoh, F.D. "A review of Nigerian bentonitic clays as drilling mud," SPE Nigeria Annual International Conference and Exhibition, Lagos. SPE-venue review paper, parallel to Al-Homadhi's SPE format. | Chapter 1 (review source, pending) |
| Falode_2008_NigeriaLocalBentonicClayDrillingFluids_AppliedClaySci.pdf | 2008 | 🔴 (new lead, found in Afolabi 2018's reference list — not yet obtained) | Nigeria | Falode, O.A.; Ehinola, O.A.; Nebeife, P.C. "Evaluation of local bentonic clay as oil well drilling fluids in Nigeria." *Applied Clay Science* 39, 19–27. Direct comparator, same genre as Khan/Al-Homadhi/Manoufali/Akinwumi — strengthens the multi-country genre table. | Chapter 1 (comparator, pending) |
| Magzoub_KFUPM_MScThesis_SaudiBentoniteStabilization.pdf (superseded placeholder) | — | — | — | Superseded — see Magzoub_2014 row above. Delete this row. | — |
| Egyptian_GabalHamdal_AbuZeneima_Beneficiation.pdf (superseded placeholder) | — | — | — | Superseded — see Hassan_1998 row above. Delete this row. | — |

## Na-activation mechanism / clay chemistry

| Filename | Year | Status | Focus | Key relevance | Cited in |
|---|---|---|---|---|---|
| Bahranowski_2021_RehydrationNaActivationBentonite.pdf | 2021 | 🟢 | Poland (Kopernica, Slovakia bentonite) — *Materials* (MDPI), 14, 7622 | Mechanistic study of Na-activation: dehydration at 200°C + rehydration with Na2CO3 solution (0.5–2.0 CEC) drives Ca→Na exchange, tracked via XRD/FTIR. Directly informs CEC-based Na2CO3 dosage rationale and go/no-go Na/Ca decision logic in Phase 1. | Chapter 1/2 (mechanism), Methodology (activation rationale) |

## Methodology / RSM / Box-Behnken

| Filename | Year | Status | Focus | Key relevance | Cited in |
|---|---|---|---|---|---|
| Maulani_2024_RSM_BoxBehnken_CMC_AlkalinePolymer.pdf | 2024 | 🟡 | Indonesia | RSM/BBD precedent for multi-factor mud optimization across temperatures | Chapter 1 |
| Alhajabdalla_2021_RSM_FibrousDispersion_ACSOmega.pdf | 2021 | 🟡 | Qatar/general | RSM/BBD for fibrous dispersion stability in drilling fluids | Chapter 1 |
| Afolabi_2018_NigeriaBentoniteRSM_DataInBrief.pdf | 2018 | 🟢 | Nigeria | See "Local clay benchmarking" table above — cross-listed here since it's also a key RSM methodology precedent (CCD, not BBD) | Chapter 1/2 |

## Yemen geology / context

| Filename | Year | Status | Focus | Key relevance | Cited in |
|---|---|---|---|---|---|
| Zaid_2021_YemenExpansiveSoilsHazard.pdf | 2021 | 🟢 | Yemen / Taiz | Regional confirmation montmorillonite-forming processes active elsewhere in Yemen | Chapter 1 |
| Ahmed_2019_AlHururAbyanClay.pdf | 2019 | 🟢 | Yemen / Al-Harur, Abyan | Cautionary secondary indicator — low-grade clay, different depositional setting | Chapter 1 |
| FAO_1996_YemenSoilSeriesFramework.pdf | 1996 | 🟢 | Yemen (national) | General soil/geology background, not montmorillonite-specific | Background only |
| Belder_1998_YemenAlIrrahSoilsFAO.pdf | 1998 | 🟢 | Yemen / Al-Irrah research station, Sana'a basin | FAO field document 10. Tangential relevance only — agricultural soils/land-suitability report. Cite sparingly, if at all. | Not yet cited — optional background only |
| Lezine_1998_YemenHoloceneLakesPaleoclimate.pdf | 1998 | 🟡 (citation confirmed; full text not yet obtained) | Yemen / Ramlat as-Sab'atayn | Lézine et al. *Quaternary Research* 50(3), 290–299. Low-priority regional depositional-context background only. | Not yet cited — optional background only |

---

## Papers still needed (gaps to fill in Phase 0 literature review)

- [ ] Egyptian El-Fayoum/Kom-Oshim source — chase via Ibrahim 1988 PhD thesis (Cairo Univ.), Ibrahim/Felix/Ismail 1994, or Inglethorpe et al. 1993
- [ ] Manoufali 2016 (Sudan Ed-Damazin) — full PDF, upgrade 🟡→🟢
- [ ] Afolabi, Orodu & Efevobkhan 2017 (Nigeria review, *Applied Clay Science* 143:39–49) — **high priority**, likely a strong single-source review for Ch.1/2
- [ ] Agwu, Okon & Udoh 2015 (Nigeria review, SPE Nigeria Conference) — medium priority
- [ ] Falode, Ehinola & Nebeife 2008 (Nigeria, *Applied Clay Science* 39:19–27) — medium priority, direct comparator
- [ ] Lézine 1998 (Yemen Holocene lakes) — full PDF, low priority — background only
- [ ] General montmorillonite/rheology textbook (e.g., Darley & Gray, or Grim's *Clay Mineralogy*) for Chapter 2 background section
- [ ] General RSM/DOE statistics reference (e.g., Montgomery, *Design and Analysis of Experiments*)
- [ ] Economic feasibility / import-substitution framing references — you now have strong comparators for this from Al-Homadhi 2007 (<46% of import cost), Hassan & Abdel-Khalek 1998 (US$21–30/t vs. US$150–400/t imported)
- [x] ~~Egyptian Gabal Hamdal citation and full text~~ — obtained, verified: Hassan & Abdel-Khalek 1998
- [x] ~~Magzoub KFUPM M.Sc. thesis~~ — obtained, confirmed 2014
- [x] ~~General montmorillonite/smectite mineralogy — mechanism~~ — filled by Bahranowski 2021
- [x] ~~Sodium activation / cation exchange mechanism papers~~ — filled by Bahranowski 2021
- [x] ~~API 13A specification~~ — obtained 2010 18th Ed.
- [x] ~~API 13B-1 testing procedures~~ — obtained 6th Ed. ballot draft (verify final edition before defense)

## How to add a new paper (workflow)

1. Download the PDF, rename it to `AuthorLastName_Year_ShortTopic.pdf`
2. Place it in the correct subfolder under `01_papers/`
3. Add a row to the relevant table above with status 🟡 (until fully read) or 🟢 (once verified)
4. Note in `05_meeting_notes/log.md` that it was added and why