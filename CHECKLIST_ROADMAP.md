# Thesis Checklist & Roadmap

**Instructions:** update this file after every work session — check off completed items, add new ones as they come up. This is the second file (with `references.md`) to paste at the start of a new AI conversation to restore context quickly.

**Last updated:** 2026-07-12

---

## Overall status snapshot

- Proposal: ✅ approved/final draft complete
- Literature base: 🟡 in progress — 15 papers identified (5 added/verified this session), several still need full verification or acquisition
- Chapter 1 (Introduction): 🟡 first draft complete, needs Egyptian citations verified + Sections 1.6/1.7 finalized
- Chapter 2 (Literature Review): 🔴 not started
- Chapter 3 (Methodology): 🔴 not started (proposal Section 5 is the base to expand from)
- Lab protocol (purification + Na-activation): ✅ first version complete (Arabic), in `03_lab_protocols/` — candidate update: consider adding thermochemical (heat + stir) step per Magzoub 2018
- Experiments: 🔴 not started — pending Phase 0 (sampling coordinates + XRD/XRF/CEC lab access confirmation)

---

## Phase 0 — Feasibility Confirmation (Weeks 1–4)

- [ ] Confirm exact sampling coordinates for Alaslaf locality (cross-check with Alshameri et al. 2013 site, with author's field guidance)
- [ ] Confirm whether XRD, XRF, CEC analysis available in-house at Faculty — or identify + cost external lab
- [x] Reference index reviewed and expanded this session — see `references.md`
- [ ] Verify Egyptian source citations (Gabal Hamdal, El-Fayoum) — still outstanding
- [ ] Obtain Magzoub KFUPM thesis in full — still outstanding (note: 2018 JERT journal paper by same author now obtained separately, do not conflate)
- [ ] Complete full literature review compilation (remaining gaps listed in `references.md`)

## Phase 1 — Sample Collection & Mineralogical Characterization

- [ ] Collect ~2 kg clay sample from confirmed Alaslaf locality
- [ ] Run small test batch (50–100g) of purification protocol before full-scale processing
- [ ] Full purification of working sample
- [ ] XRD, XRF, CEC, particle size distribution, Atterberg limits, specific gravity on purified sample
- [ ] Compute Na/Ca and (Na+K)/(Ca+Mg) ratios (Khan et al. 2017 method)
- [ ] **Go/no-go decision point:** if Na/Ca < 0.5 → trigger Na-activation (see `03_lab_protocols/`)
- [ ] If activation triggered: run activation trial dosages (2–6% Na2CO3), confirm via XRD basal-spacing shift + CEC change
- [ ] Consider Magzoub 2018 thermochemical step (soda ash + 70–90°C heating/stirring, up to 24 hr) as an enhancement if simple chemical activation proves insufficient — flagged for Phase 1 protocol decision

## Phase 2 — DOE-Based Formulation Design

- [ ] Finalize 3-factor Box-Behnken design in Minitab (clay concentration, Na2CO3 dosage, CMC concentration)
- [ ] Prepare 15 experimental formulations (12 edge-midpoint + 3 center-point replicates)
- [ ] Prepare parallel commercial Wyoming bentonite reference formulations + Mill Gel-equivalent benchmark
- [ ] Triplicate rheological/filtration measurement plan confirmed
- [ ] Review Ossai 2025, Alhajabdalla 2021, Satiyawira 2025, and Asmungi 2021 reporting formats (ANOVA tables, coded regression equations, response surface plots, fit statistics, multi-response desirability optimization) as templates for Chapter 3/4 presentation — Satiyawira 2025 is the strongest template if testing extends across multiple temperatures
- [ ] Consider whether tannin (natural deflocculant, per Asmungi 2021) is worth a Chapter 1/8 mention as a parallel local-additive angle, even if not experimentally trialled — check if a Yemen-local tannin source exists

## Phase 3 — Rheological and Filtration Benchmarking

- [ ] Fann 35 viscometer readings (600/300/200/100/6/3 rpm) for all formulations
- [ ] Compute PV, YP, AV, gel strength (10-sec/10-min)
- [ ] API filter press fluid-loss measurements
- [ ] Mud balance density + pH for all batches
- [ ] Build RSM model (Minitab Response Optimizer + independent Python cross-check)
- [ ] Statistical comparison (t-test/ANOVA) vs. commercial benchmark and API targets

## Phase 4 — Data Reporting

- [ ] Report results against API 13A benchmark, quantify any shortfall
- [ ] Economic feasibility summary (indicative cost comparison)
- [ ] Draft manuscript sections mapped to JPEPT submission structure

## Thesis Writing

- [ ] Chapter 1 — Introduction (🟡 draft done, needs finalizing — NEXT UP per user's stated priority for this session)
- [ ] Chapter 2 — Literature Review (🔴 not started)
- [ ] Chapter 3 — Methodology (🔴 not started)
- [ ] Chapter 4 — Results (pending experimental data)
- [ ] Chapter 5 — Discussion (pending experimental data)
- [ ] Chapter 6 — Conclusions & Recommendations
- [ ] Full reference list formatted per Faculty/journal style
- [ ] Defense preparation

---

## Open questions / decisions pending

- [ ] Exact Na2CO3 dosage range to trial (currently 2–6%, "to be refined against literature" per proposal) — Magzoub 2018 supports 4 wt.% as optimum single-stage dosage, useful data point
- [ ] External lab identity + cost, if XRD/XRF/CEC not available in-house
- [ ] Whether to include Magzoub KFUPM thesis structure as a model for chapter organization
- [ ] Whether to adopt a thermochemical (heat + stir) activation step in the lab protocol, given Magzoub 2018's strong results (2.5→20 cP apparent viscosity, filtration 70→11.8 mL) vs. simple chemical-only activation

## Next session should pick up with

→ **Chapter 1 finalization**, drawing on the newly added Magzoub 2018 (JERT) and Ossai 2025 papers, then **Chapter 2 (Literature Review) expansion** once Chapter 1 is closed out.
