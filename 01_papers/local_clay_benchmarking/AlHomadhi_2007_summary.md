# Al-Homadhi (2007) — Improving Local Bentonite Performance for Drilling Fluids Applications

**Full citation:** Al-Homadhi, E.S. (2007). "Improving local bentonite performance for drilling fluids applications." SPE 110951, presented at the 2007 SPE Saudi Arabia Technical Symposium, Dhahran, Saudi Arabia, 7–8 May 2007. Society of Petroleum Engineers. Author affiliated with King Saud University. Financially supported by SABIC.

**Deposit/location:** Khulays area, ~70 km north of Jeddah, adjacent to the Makkah-Madinah road, Saudi Arabia — **the same deposit later studied by Magzoub (2014)**, your KFUPM M.Sc.-thesis source. This paper predates Magzoub by 7 years and is a useful earlier independent data point on the identical deposit — worth reading the two together as a before/after or cross-validation pair.

**Method:** Bulk raw bentonite samples from Khulays → crushed, ball-milled, sieved to 45 µm → clay identification via XRD and SEM (compared directly against imported commercial bentonite, likely Wyoming-sourced) → particle-size analysis (Malvern Laser Sizer) → mud preparation at 5–15 wt% clay concentration, benchmarked against imported bentonite (Macogel/Aquagel) and a "high-yield clay" (Baroco) reference → beneficiation trials at a **fixed 7 wt% clay concentration**, testing five separate enhancement methods one at a time: (1) increased shearing/mixing speed, (2) CMC (HV grade), (3) Drispac (polyanionic cellulose polymer), (4) NaOH, (5) Na₂CO₃ (soda ash) → final combined-additive formulation proposed and benchmarked against imported bentonite and API/OCMA specs.

---

## Confirms this really is your "closest precedent" — and adds a genuinely new data point your other Khulays source doesn't have

This upgrades cleanly from 🟡 (snippet-only) to fully verified, and the read confirms the "closest precedent" framing in your `references.md`. What it adds beyond Magzoub (2014) on the same deposit: **direct XRD/SEM comparison against imported commercial bentonite** (not just against a specification table), and a **specific, well-reasoned finding that NaOH activation is not recommended for this particular clay** — a genuinely useful nuance that complicates the "just add NaOH/Na₂CO₃ and you're done" narrative running through several of your other sources.

## Key findings

**Reserve figures (citing Spencer 1986):** Khulays bentonite reserves are **420,000 tonnes proven, 28.9 million tonnes indicated, 38.9 million tonnes possible** — useful comparator figures alongside your Alaslaf reserve-quantification gap (still open in your Phase 0 checklist) and the Nigerian reserve figures already noted in Afolabi (2017).

**Mineralogical identification (XRD + SEM, Figs. 1–3):** XRD peaks of local Khulays bentonite show **good general agreement** with imported bentonite (confirming montmorillonite is present), but with two notable differences: a peak at **d = 3.34 Å**, indicating a **high concentration of quartz** impurity, and a peak at **d = 7.096 Å**, indicating a **minor concentration of kaolinite**. SEM imaging shows local bentonite particles as clean/uncoated, while **imported bentonite particles appear coated with a smooth material believed to be an extending polymer** — directly supporting (and citing) Bol's (SPE 13454) prior conclusion that commercial/imported bentonite is typically already polymer-extended, not "pure" raw material. **This is a genuinely useful framing point for your Chapter 1/2**: the standard you're benchmarking against (imported/commercial bentonite) may itself not be an unmodified natural material, which is worth acknowledging explicitly rather than treating "imported bentonite" as a pure, untreated baseline.

**Particle size (Malvern Laser Sizer, Fig. 4):** Local Khulays bentonite particle size range **0.03–20 µm, mean 3.1 µm, with 90% of particles below 10 µm.** Given that true clay particles are defined as <4 µm, this size distribution is read as **evidence of a quartz/silt fraction contaminating the sample** — consistent with the XRD quartz-peak finding — and the author explicitly recommends removing these coarser particles for better performance.

**Raw clay vs. imported bentonite vs. high-yield clay, at 5–15 wt% concentration (Figs. 5–7):**
- **Apparent viscosity:** local Khulays bentonite tracked below imported bentonite across the concentration range, but **above** the "high-yield clay" (Baroco) reference, especially at higher concentrations (~15 wt%: local ~72 cP vs. Baroco ~24 cP vs. imported ~higher still, though the imported curve is not fully extended to 15 wt% in the reported figure).
- **Filtration loss:** local clay showed **much higher** filtrate loss than imported bentonite at every concentration tested (roughly 40–60 mL for local vs. 9–18 mL for imported across 5–11 wt%) — a large, consistent gap.
- **pH:** local bentonite pH ran **~0.6 units lower** than imported bentonite across concentrations.

**API/OCMA specification table used (Table 1) — cross-check against your already-resolved primary-source values:**

| Property | API requirement (as cited here) | OCMA requirement (as cited here) |
|---|---|---|
| Fann-600 reading (7 wt% bentonite) | > 30 | — |
| Yield point (implicitly YP/PV) | < 3 | — |
| API filtrate | < 15 mL | — |
| Wet-sieving residue on sieve No. 200 (75 µm) | < 4 wt% | < 2.5 wt% |
| Wet-sieving residue on 100-mesh screen | — | < 2 wt% |

**This is fully consistent with your already-verified primary-source API 13A values (Table 8: filtrate ≤15.0 mL, residue ≤4.0 wt%)** — a fourth independent confirmation of the 15 mL API figure (alongside Magzoub, and now your own primary-source check), which further reinforces that 15 mL (not El-Mahllawy's 13.0 mL) is the correct API figure to standardize on. Notably, **this paper does not state an OCMA filtrate limit at all** (left blank in the original table) — it doesn't contribute evidence either way to the OCMA 12.5 vs. 16.0 mL question, but the residue figures (OCMA ≤2.5 wt% on #200, ≤2 wt% on 100 mesh) match your verified Table 10 OCMA residue value (2.5 wt%) exactly.

**Beneficiation trials at fixed 7 wt% clay concentration — five separate single-variable tests:**

| Method | Result |
|---|---|
| Increased shearing/mixing speed (6,000→15,000 rpm) | 200% increase in viscosity; 35% reduction in filtration loss — but economically/equipment-limited at scale |
| HV-CMC | At 6 g/L: viscosity doubled (but a relatively high dose); at 1 g/L: filtration loss dropped sharply from 50 to 21 mL |
| Drispac | At 1 g/L: filtration loss reaches API requirement; **2 g/L needed to reach API viscosity requirement** |
| NaOH | Viscosity increases via base exchange (Na⁺ replacing Ca²⁺), but **>1 g/L needed for meaningful viscosity gain, which pushes pH above 11 — exceeds acceptable range. NaOH activation explicitly NOT recommended for this clay.** |
| Na₂CO₃ (soda ash) | At 4 g/L: viscosity doubled; filtration loss reduced only 25% (insufficient alone, needs a second additive); pH raised to ~9 (acceptable) |

**⚠️ Notable point of disagreement with your other Na-activation sources:** Unlike Hassan (1998), El-Mahllawy (2013), and (implicitly) Khan (2017) and Magzoub (2014), all of which treat NaOH or Na₂CO₃ addition as a broadly successful activation route, **this paper specifically found NaOH problematic for the Khulays clay** — the dose needed for adequate viscosity improvement pushes pH into an unacceptable range (>11 vs. a ~9 target). Na₂CO₃ (soda ash) worked better on pH but still needed a second additive (Drispac) to fully address filtration. **This is a useful nuance to cite in your Chapter 3**: activator choice and dose response is deposit-specific, and NaOH/Na₂CO₃ effectiveness on Alaslaf material cannot simply be assumed from other deposits' success — your own Box-Behnken design, testing Na₂CO₃ and CMC together, is well-positioned to catch this kind of interaction (pH overshoot vs. viscosity gain) that this paper's OFAT approach only found by accident, one variable at a time.

**Final recommended formulation (Conclusions):** **5% Soda Ash + 0.5% Drispac** (both expressed relative to added bentonite mass) applied to local Khulays bentonite. Result: **7 wt% imported bentonite mud performance ≈ 8 wt% enhanced local bentonite mud performance** — i.e., roughly 8/7 ≈ **14% more local clay needed by mass** to match imported-bentonite performance after enhancement, a modest and economically reasonable premium.

**Yield and economics:** Imported bentonite yield = **95 bbl/ton**; enhanced local bentonite yield = **85 bbl/ton**, which the author notes can reach 95 bbl/ton with an additional 0.5% Drispac. Cost estimate (based on published Baroid additive pricing): **enhanced local bentonite costs less than 46% of imported bentonite cost** — though the author explicitly caveats this needs further investigation of local mining, processing, packing, and transportation costs before being treated as a firm figure. Directly useful, citable economics precedent for your own Section 8, alongside the similar cost framing already established via Hassan (1998).

## Numbers worth citing directly

- Khulays reserves: 420,000 t proven / 28.9 million t indicated / 38.9 million t possible
- XRD impurity peaks in local bentonite: d=3.34 Å (quartz, high concentration), d=7.096 Å (kaolinite, minor concentration)
- Particle size: 0.03–20 µm range, mean 3.1 µm, 90% below 10 µm
- Shearing speed 6,000→15,000 rpm: 200% viscosity increase, 35% filtration-loss reduction
- CMC at 1 g/L: filtration loss 50→21 mL
- Drispac: 1 g/L meets API filtration requirement; 2 g/L needed for API viscosity requirement
- NaOH: >1 g/L needed for viscosity gain, but pushes pH >11 (unacceptable) — not recommended
- Na₂CO₃ at 4 g/L: viscosity doubled; filtration loss reduced only 25% (needs a second additive)
- Final formulation: 5% Soda Ash + 0.5% Drispac (of bentonite mass) → 8 wt% enhanced local bentonite ≈ 7 wt% imported bentonite performance
- Yield: imported 95 bbl/ton; enhanced local 85 bbl/ton (→95 with extra 0.5% Drispac)
- Cost: enhanced local bentonite <46% of imported bentonite cost (caveat: needs further verification of full local production-cost chain)
- API spec (as cited here, consistent with your primary-source table): Fann-600>30, YP/PV<3, filtrate<15mL, residue<4.0wt% (#200 sieve); OCMA residue <2.5wt% (#200), <2wt% (100 mesh) — no OCMA filtrate figure stated

## Relevance to this thesis

- **Chapter 1 (Introduction):** your primary "closest precedent" citation, now fully verified — same regional narrative (single known deposit, 100% import-dependent industry, Ca-type clay needing enhancement) as your own Alaslaf framing. The "imported bentonite may itself already be polymer-extended, not a pure natural baseline" point (via Bol, SPE 13454, cited within) is a valuable nuance worth explicitly stating in your own benchmarking discussion.
- **Chapter 2/3 (methodological caveat, activator-specific behavior):** the NaOH-not-recommended finding is your most valuable new addition from this paper — it directly tempers any assumption that Na-based activation is a universal fix, and gives you a citable reason why your own Box-Behnken design (testing Na₂CO₃ and CMC jointly, across a dose range, rather than a single NaOH dose) is methodologically better-positioned to detect a pH/viscosity trade-off like the one found here.
- **Chapter 3 (Methodology):** direct precedent for XRD+SEM comparative identification of local vs. imported bentonite, and for a systematic (if OFAT) additive-screening sequence (shearing speed → CMC → Drispac → NaOH → Na₂CO₃) — useful as a "menu" of additive options to reference when framing your own factor selection, even though your factors (Na₂CO₃, CMC, clay concentration) are narrower and DOE-optimized rather than a broad OFAT sweep across five different methods.
- **Section 8 (Economic feasibility):** directly citable cost/yield figures (<46% of imported cost; 85→95 bbl/ton yield) — a second independent economics precedent alongside Hassan (1998), strengthening your import-substitution argument with cross-country consistency (Saudi Arabia and Egypt both showing substantial cost savings potential from local beneficiation).
- **Cross-reference note:** since this is the same deposit as Magzoub (2014), consider citing them together in Chapter 1/2 as a before/(this paper, 2007)-and-after/(Magzoub, 2014) pair on the identical Khulays material — useful for showing how research on a single deposit matured over time (from simple OFAT additive screening here to full purification-method-comparison + novel thermal-activation method in Magzoub).

## Caveats / limitations

1. **OFAT design throughout** — all five enhancement methods (shearing speed, CMC, Drispac, NaOH, Na₂CO₃) were tested one at a time at a single fixed 7 wt% clay concentration; no interaction effects between clay concentration and additive dose, or between multiple additives simultaneously, were explored (aside from the final combined 5% Soda Ash + 0.5% Drispac formulation, which was not itself optimized via a designed sweep) — another clear precedent for stating your Box-Behnken/RSM approach as a methodological improvement.
2. **No direct CEC or exchangeable Na/Ca ratio measurement** — clay quality assessment relies on XRD peak comparison, particle size, and empirical rheological/filtration behavior, not a quantified exchangeable-cation basis. Contrast this with Magzoub (2014)'s later SEM-EDS-based Na/Ca ratio work on the *same* deposit — worth citing Magzoub for the quantitative exchange-chemistry evidence and this paper for the earlier qualitative/XRD-SEM identification and additive-screening work.
3. The "2 mg/l" Drispac concentration mentioned in-text for the viscosity requirement appears to be a units inconsistency with the paper's own figure axis label ("Drispac Concentration (gm/l)") — almost certainly meant to read "2 gm/l," consistent with the other Drispac dosing figures; treat the in-text "mg/l" as a likely typo rather than a real hundred-fold unit difference.
4. Economic cost-comparison figure (<46% of imported cost) is explicitly flagged by the author as needing further investigation into local mining/processing/packing/transportation costs — don't treat this as a settled, final figure; cite it as an indicative estimate only.
5. Single-deposit study (Khulays only, though the same deposit is independently corroborated by Magzoub 2014 seven years later) — useful as a process/methodology precedent, not a geological analog to Alaslaf's Triassic rhyolitic-tuff origin.
