# Thesis Checklist & Roadmap

**Instructions:** update this file after every work session — check off completed items, add new ones as they come up. This is the second file (with `references.md`) to paste at the start of a new AI conversation to restore context quickly.

**Last updated:** 2026-07-12 (Session 4)

---

## Overall status snapshot

- Proposal: ✅ approved/final draft complete
- Literature base: 🟡 in progress — 18 papers identified (3 new leads surfaced this session), most core comparators now 🟢 verified
- Chapter 1 (Introduction): 🟡 first draft complete, needs: Manoufali/3 new Nigeria leads full text, Sections 1.6/1.7 finalized
- Chapter 2 (Literature Review): 🔴 not started
- Chapter 3 (Methodology): 🔴 not started (proposal Section 5 is the base to expand from)
- Lab protocol (purification + Na-activation): ✅ first version complete (Arabic), in `03_lab_protocols/`
- Experiments: 🔴 not started — pending Phase 0 (sampling coordinates + XRD/XRF/CEC lab access confirmation)

---

## Phase 0 — Feasibility Confirmation (Weeks 1–4)

- [ ] Confirm exact sampling coordinates for Alaslaf locality (cross-check with Alshameri et al. 2013 site, with author's field guidance)
- [ ] Confirm whether XRD, XRF, CEC analysis available in-house at Faculty — or identify + cost external lab
- [ ] Complete full literature review compilation (see gaps list in `references.md`)
- [x] ~~Verify Egyptian Gabal Hamdal citation + obtain full text~~ — done: Hassan & Abdel-Khalek 1998, *Applied Clay Science* 13(2):99–115
- [ ] Verify Egyptian El-Fayoum/Kom-Oshim citation (new leads: Ibrahim 1988 PhD thesis; Ibrahim/Felix/Ismail 1994; Inglethorpe et al. 1993)
- [x] ~~Obtain Magzoub KFUPM thesis~~ — obtained, confirmed 2014
- [ ] Obtain full PDFs for: Manoufali 2016 (Sudan); Afolabi/Orodu/Efevobkhan 2017 review (high priority); Agwu et al. 2015 review; Falode et al. 2008; Lézine 1998 (low priority)

## Phase 1 — Sample Collection & Mineralogical Characterization

- [ ] Collect ~2 kg clay sample from confirmed Alaslaf locality
- [ ] Run small test batch (50–100g) of purification protocol before full-scale processing
- [ ] Full purification of working sample
- [ ] XRD, XRF, CEC, particle size distribution, Atterberg limits, specific gravity on purified sample
- [ ] Compute Na/Ca and (Na+K)/(Ca+Mg) ratios (Khan et al. 2017 method)
- [ ] **Go/no-go decision point:** if Na/Ca < 0.5 → trigger Na-activation (see `03_lab_protocols/`)
- [ ] If activation triggered: run activation trial dosages (2–6% Na2CO3), confirm via XRD basal-spacing shift + CEC change — cross-check against Bahranowski et al. 2021 (CEC-based ladder), Magzoub 2014 (thermo-chemical), and Hassan & Abdel-Khalek 1998 (1–5% Na2CO3, swelling index >100 achieved at 3–5%) — three independent dosage precedents now available to triangulate your 2–6% range

## Phase 2 — DOE-Based Formulation Design

- [ ] Finalize 3-factor Box-Behnken design in Minitab (clay concentration, Na2CO3 dosage, CMC concentration)
- [ ] Prepare 15 experimental formulations (12 edge-midpoint + 3 center-point replicates)
- [ ] Prepare parallel commercial Wyoming bentonite reference formulations + Mill Gel-equivalent benchmark
- [ ] Triplicate rheological/filtration measurement plan confirmed
- [ ] Note: Afolabi et al. 2018 used a 4-factor Central Composite Design (Minitab 17) with YP/PV as primary response — useful as a statistical-reporting-style template (ANOVA table format, regression equation presentation) even though your design type (BBD) differs

## Phase 3 — Rheological and Filtration Benchmarking

- [ ] Fann 35 viscometer readings (600/300/200/100/6/3 rpm) for all formulations
- [ ] Compute PV, YP, AV, gel strength (10-sec/10-min)
- [ ] API filter press fluid-loss measurements
- [ ] Mud balance density + pH for all batches
- [ ] Build RSM model (Minitab Response Optimizer + independent Python cross-check)
- [ ] Statistical comparison (t-test/ANOVA) vs. commercial benchmark and API targets

## Phase 4 — Data Reporting

- [ ] Report results against API 13A benchmark, quantify any shortfall
- [ ] Economic feasibility summary — now have three independent cost comparators to draw on: Al-Homadhi 2007 (<46% of imported cost), Hassan & Abdel-Khalek 1998 (US$21–30/t vs. US$150–400/t imported)
- [ ] Draft manuscript sections mapped to JPEPT submission structure

## Thesis Writing

- [ ] Chapter 1 — Introduction (🟡 draft done, needs finalizing)
- [ ] Chapter 2 — Literature Review (🔴 not started — NEXT UP)
- [ ] Chapter 3 — Methodology (🔴 not started)
- [ ] Chapter 4 — Results (pending experimental data)
- [ ] Chapter 5 — Discussion (pending experimental data)
- [ ] Chapter 6 — Conclusions & Recommendations
- [ ] Full reference list formatted per Faculty/journal style
- [ ] Defense preparation

---

## Open questions / decisions pending

- [ ] Exact Na2CO3 dosage range to trial (currently 2–6%) — now triangulated against 3 precedents (Bahranowski 2021, Magzoub 2014, Hassan & Abdel-Khalek 1998)
- [ ] External lab identity + cost, if XRD/XRF/CEC not available in-house
- [ ] Whether to include Magzoub 2014 thesis structure as a model for chapter organization
- [ ] How much space to give tangential Yemen-context papers (Belder 1998, Lézine 1998)
- [ ] Reconcile Al-Homadhi 2007 (near-parity) vs. Magzoub 2014 (outperformance) on the same Khulays deposit
- [ ] Whether Afolabi/Orodu/Efevobkhan 2017 (if obtained) makes some of the individually-tracked Nigeria papers (Nlemedin 2023, Falode 2008, Akinwumi 2015) redundant as a single review citation, or whether all should still be cited individually for depth

## Next session should pick up with

→ Obtain Afolabi/Orodu/Efevobkhan 2017 review paper (highest-value remaining gap) and Manoufali 2016, then move to **Chapter 2 (Literature Review)** drafting.