# Thesis Checklist & Roadmap

**Instructions:** update this file after every work session — check off completed items, add new ones as they come up. This is the second file (with `references.md`) to paste at the start of a new AI conversation to restore context quickly.

**Last updated:** 2026-07-16

---

## Overall status snapshot

- Proposal: ✅ approved/final draft complete
- Literature base: 🟢 strong — 22 papers/sources confirmed in hand (`01_papers/`), spanning API standards, core deposit, 11 local-clay benchmarking papers (Nigeria/Saudi/Egypt/Sudan), 6 RSM/methodology papers, 2 Na-activation mechanism papers, and 4 Yemen geology/context papers. Far broader than previously tracked — literature review is now well-resourced for Chapter 2.
- Chapter 1 (Introduction): 🟡 first draft complete, Egyptian citations verified, now has a much wider set of Nigeria/Saudi/Sudan comparators available to strengthen Section 1.3's "genre" argument
- Chapter 2 (Literature Review): 🔴 not started — literature base is now in very good shape to begin
- Chapter 3 (Methodology): 🔴 not started (proposal Section 5 is the base to expand from; now has 6 direct RSM/Box-Behnken precedent papers plus 2 mechanistic Na-activation papers to draw on)
- Lab protocol (purification + Na-activation): ✅ first version complete (Arabic), in `03_lab_protocols/`
- Experiments: 🔴 not started — pending Phase 0 (sampling coordinates + XRD/XRF/CEC lab access confirmation)

---

## Phase 0 — Feasibility Confirmation (Weeks 1–4)

- [ ] Confirm exact sampling coordinates for Alaslaf locality (cross-check with Alshameri et al. 2013 site, with author's field guidance)
- [ ] Confirm whether XRD, XRF, CEC analysis available in-house at Faculty — or identify + cost external lab
- [x] Complete full literature review compilation — repo now holds 22 verified papers across all categories (2026-07-16); see `references.md` for the complete index and small list of open items
- [x] Verify Egyptian source citations (Gabal Hamdal, El-Fayoum) — done, both confirmed with correct authors/journal/DOI
- [x] Obtain Magzoub KFUPM thesis in full — done, plus its 2018 journal follow-up (JERT) also confirmed in hand
- [ ] Confirm whether the Myers/Montgomery/Anderson-Cook RSM textbook and Caenn/Darley/Gray drilling fluids textbook (both identified as useful in a prior session) are actually held anywhere, or still need to be obtained — not found in current `01_papers/` listing
- [ ] Confirm status of Nlemedin/Nlemedim 2023 (Ikwo clay, Nigeria) — previously tracked, not in current `01_papers/` listing; decide if still needed
- [ ] Review `01_papers/methodology_RSM/README.md` — content not yet reviewed, may contain useful notes on how the RSM papers are meant to be used

## Phase 1 — Sample Collection & Mineralogical Characterization

- [ ] Collect ~2 kg clay sample from confirmed Alaslaf locality
- [ ] Run small test batch (50–100g) of purification protocol before full-scale processing
- [ ] Full purification of working sample
- [ ] XRD, XRF, CEC, particle size distribution, Atterberg limits, specific gravity on purified sample
- [ ] Compute Na/Ca and (Na+K)/(Ca+Mg) ratios (Khan et al. 2017 method)
- [ ] **Go/no-go decision point:** if Na/Ca < 0.5 → trigger Na-activation (see `03_lab_protocols/`)
- [ ] If activation triggered: run activation trial dosages (2–6% Na2CO3), confirm via XRD basal-spacing shift + CEC change — Bahranowski 2021 and Karaguzel 2010 now available for mechanistic grounding of this step

## Phase 2 — DOE-Based Formulation Design

- [ ] Finalize 3-factor Box-Behnken design in Minitab (clay concentration, Na2CO3 dosage, CMC concentration) — Asmungi 2023 and Ossai 2025 offer directly comparable 3-factor BBD designs worth reviewing before finalizing factor levels
- [ ] Prepare 15 experimental formulations (12 edge-midpoint + 3 center-point replicates)
- [ ] Prepare parallel commercial Wyoming bentonite reference formulations + Mill Gel-equivalent benchmark
- [ ] Triplicate rheological/filtration measurement plan confirmed

## Phase 3 — Rheological and Filtration Benchmarking

- [ ] Fann 35 viscometer readings (600/300/200/100/6/3 rpm) for all formulations
- [ ] Compute PV, YP, AV, gel strength (10-sec/10-min)
- [ ] API filter press fluid-loss measurements
- [ ] Mud balance density + pH for all batches
- [ ] Build RSM model (Minitab Response Optimizer + independent Python cross-check) — Derringer & Suich (1980) desirability function now in hand as the foundational citation for Minitab's optimizer methodology
- [ ] Statistical comparison (t-test/ANOVA) vs. commercial benchmark and API targets

## Phase 4 — Data Reporting

- [ ] Report results against API 13A benchmark, quantify any shortfall
- [ ] Economic feasibility summary (indicative cost comparison) — El-Mahllawy 2013, Hassan & Abdel-Khalek 1998, Agwu 2015, and Manoufali 2016 all touch on import-substitution economics and may partially support this section
- [ ] Draft manuscript sections mapped to JPEPT submission structure

## Thesis Writing

- [ ] Chapter 1 — Introduction (🟡 draft done, Egyptian citations verified, wider comparator set now available for Section 1.3)
- [ ] Chapter 2 — Literature Review (🔴 not started — NEXT UP, literature base now well-resourced across mineralogy/beneficiation, Na-activation mechanism, and RSM methodology)
- [ ] Chapter 3 — Methodology (🔴 not started — Magzoub 2014/2015 thesis + 2018 journal paper, plus 6 RSM/BBD precedent papers and Derringer & Suich 1980, now available as structural/statistical templates)
- [ ] Chapter 4 — Results (pending experimental data)
- [ ] Chapter 5 — Discussion (pending experimental data)
- [ ] Chapter 6 — Conclusions & Recommendations
- [ ] Full reference list formatted per Faculty/journal style
- [ ] Defense preparation

---

## Open questions / decisions pending

- [ ] Exact Na2CO3 dosage range to trial (currently 2–6%, "to be refined against literature" per proposal — Magzoub 2014/2018, Karaguzel 2010, and Bahranowski 2021 all offer dosage/CEC-ratio precedents to help refine this)
- [ ] External lab identity + cost, if XRD/XRF/CEC not available in-house
- [ ] Whether to include Magzoub KFUPM thesis structure as a model for chapter organization — worth a dedicated read-through session given both the thesis and its journal follow-up are now in hand
- [ ] Whether to cite the Abdou/Al-Sabagh/Dardir 2013 nano-bentonite paper separately from El-Mahllawy et al. 2013 (previously conflated — see references.md note; note this nano-bentonite paper itself does not appear to be in your current `01_papers/` holdings, only referenced as background)
- [ ] Confirm holdings status of the two general-reference textbooks (Myers et al. RSM; Caenn/Darley/Gray) and Nlemedin 2023 — see Phase 0 checklist above

## Next session should pick up with

→ **Chapter 2 (Literature Review) expansion** — the literature base is now substantially stronger than previously tracked (22 confirmed papers across all categories). Recommended sub-steps: (1) do a full read-through of the Magzoub 2014/2015 thesis and its 2018 journal follow-up together, since both are now in hand, to extract structural/methodological detail for Chapter 3; (2) integrate the now-verified Egyptian citations plus the newly-confirmed Nigeria/Saudi/Sudan comparators (Afolabi 2017 review, Agwu 2015 review, Falode 2008, Manoufali 2016) into Chapter 1 Section 1.3's "genre" argument; (3) begin drafting Chapter 2 background sections, drawing on the 6 RSM/BBD papers for methodology framing and Bahranowski 2021 / Karaguzel 2010 for Na-activation mechanism framing; (4) resolve the small list of open items in `references.md` (textbook holdings, Nlemedin 2023 status, README review).
