# Ossai, Oyedoh, Magbuwe & Atapia (2025) — Optimization of the Formulation of Drilling Mud using Box-Behnken Design

**Full citation:** Ossai, J.E., Oyedoh, E.A., Magbuwe, V.O., Atapia, M.I. (2025). "Optimization of the Formulation of Drilling Mud using Box–Behnken Design." *Journal of Energy Technology and Environment*, 7(2), 166–173. DOI: 10.5281/zenodo.15609815. ISSN 2682-583x. Authors affiliated with Department of Chemical Engineering, University of Benin, Benin City, Nigeria. Received 18 Apr 2025, accepted 28 May 2025.

**Deposit/location:** Local clay from Ovia River, Edo State, Nigeria (5°20′–6°35′N, 5°05′–5°40′E). Note: this is the same Ovia location already referenced secondhand in your Agwu (2015) review (Imuentinyan & Adewole 2014 studied "Ovia" clay) — worth cross-referencing if you cite both.

**Method — this is your first paper showing the full BBD/RSM workflow actually applied to a drilling-mud rheology response, directly parallel to your planned Phase 2–3 approach:**
- Local clay dried and crushed; characterized only by SEM (morphology/porosity/particle distribution) — **no XRD, XRF, or CEC reported**, a significant gap relative to your own planned mineralogical characterization.
- Two locally sourced beneficiating/functional additives prepared in-house: **cassava starch** (washed, peeled, pulped, water-extracted, filtered, dried) and **corn cob ash** (incinerated at 600°C for 2 hours, ground).
- **Four factors** varied in the Box-Behnken design: Clay (A: 5–20 g), Ash (B: 0–3 g), NaOH (C: 1–2 g), Starch (D: 2–8 g) — a **4-factor BBD**, larger than the classic 3-factor BBD (your own roadmap specifies 3 factors: clay concentration, Na₂CO₃ dosage, CMC concentration). **29 runs total**, including 5 center-point replicates (runs 5, 16, 18, 22, 23 all at the 12.5/1.5/1.5/5 center point) — useful as a real precedent for how many center points a 4-factor BBD needs (yours will need fewer for 3 factors).
- Mud prep: 350 mL distilled water base, NaOH added first for pH adjustment, clay mixed in, then corn cob ash and starch added for filtration/viscosity control, stirred 30 min, aged 10 min before testing.
- Viscosity measured with a **Baroid Model 286 rheometer** (3/100/200/300/600 rpm) — note this differs from the standard Fann 35 (600/300/200/100/6/3 rpm) your own roadmap specifies; the missing 3 and 6 rpm low-shear readings mean this paper's dataset **cannot support gel-strength or full YP/PV calculation** the way a standard API 13B-1 6-speed protocol can.
- **Only two responses modeled**: apparent viscosity (AV) and plastic viscosity (PV). No yield point, gel strength, fluid loss, density, or pH reported as RSM responses (pH is mentioned as measured in methods but never reported as a result) — a much narrower response set than your thesis's planned five responses (PV, YP, AV, gel strength, fluid loss).
- Quadratic polynomial models fitted via regression, validated by ANOVA (Design-Expert software implied by terminology — "Adeq Precision," "C.V.%," coded equations — though not explicitly named in text).

---

## Key results

**Optimum formulation:** Clay 20 g, Ash 1.5 g, NaOH 2 g, Starch 5 g → predicted **apparent viscosity = 116.431 mPa·s**, **plastic viscosity = 75.6167 mPa·s**.

**Apparent viscosity model (Table 2–3):**
- Model highly significant: F = 36.97, p < 0.0001
- Significant individual terms (p<0.05): Clay (A), Ash (B), Starch (D) — **NaOH (C) alone was not significant** (p=0.2252), though its quadratic term C² was highly significant (p<0.0001)
- Significant interactions: AB (clay-ash), AD (clay-starch), CD (NaOH-starch)
- All four quadratic terms (A², B², C², D²) highly significant — strong nonlinearity/curvature in the response surface
- **Fit quality: R² = 0.9737, Adjusted R² = 0.9473, Predicted R² = 0.9067, Adeq Precision = 19.275** — predicted vs. adjusted R² gap = 0.0406 (<0.2, acceptable per the paper's own stated criterion), lack-of-fit not significant (p=0.9149) — a genuinely well-fitted model by standard RSM diagnostic criteria.
- Coded equation: AV = 163.05 + 15.59A + 8.38B + 2.41C + 16.44D − 9.50AB − 5.16AC + 10.28AD − 2.04BC + 2.96BD − 7.97CD − 27.43A² − 23.16B² − 32.03C² − 32.34D²
- **Interpretation:** clay and starch have the largest positive linear coefficients (15.59 and 16.44) — both are the primary AV-increasing factors, consistent with expectations (more clay = more solids loading; starch is a viscosifier/filtration-control agent).

**Plastic viscosity model (Table 4–5, mislabeled "ANOVA for Apparent Viscosity" in the paper's own table heading — **this is an error in the original paper**, confirmed by the response values matching PV not AV):**
- Model significant: F = 22.03, p < 0.0001
- Significant individual terms: Clay (A, p<0.0001), Ash (B, p<0.0001) — **NaOH and Starch NOT significant individually** for PV (p=0.1034, p=0.2199)
- Significant interaction: **BC (ash-NaOH)** only (p=0.0007) — notably different interaction structure from the AV model
- All four quadratic terms significant
- **Fit quality: R² = 0.9566, Adjusted R² = 0.9132, Predicted R² = 0.7621, Adeq Precision = 14.5243.** Predicted-vs-adjusted R² gap = 0.1511, close to but within the paper's own 0.2 threshold. **⚠️ Lack-of-fit F-value p = 0.0561** — the paper's own text explicitly flags this as "troubling" (their word) since it's below the conventional 10% threshold sometimes used as a caution flag, though they still proceed to validate the model. Worth noting as a real, self-acknowledged weak point in this paper's own PV model relative to its AV model.
- Coded equation: PV = 90.78 + 9.94A + 11.00B + 2.66C + 1.96D − 1.27AB − 0.825AC + 0.8425AD + 11.49BC + 3.5BD − 1.07CD − 15.65A² − 10.546B² − 12.95C² − 25.26D²

**Author's stated conclusion:** clay and starch content primarily drive apparent viscosity; clay and ash primarily drive plastic viscosity.

## Numbers worth citing directly

- Optimum formulation: Clay 20 g / Ash 1.5 g / NaOH 2 g / Starch 5 g (per 350 mL water) → AV 116.431 mPa·s, PV 75.6167 mPa·s
- AV model: R²=0.9737, Adj R²=0.9473, Pred R²=0.9067, Adeq Precision=19.275, F=36.97 (p<0.0001)
- PV model: R²=0.9566, Adj R²=0.9132, Pred R²=0.7621, Adeq Precision=14.524, F=22.03 (p<0.0001), lack-of-fit p=0.0561 (self-flagged as "troubling")
- 4-factor BBD, 29 runs, 5 center-point replicates
- Corn cob ash prepared by incineration at 600°C for 2 hours

## Relevance to this thesis

- **Chapter 3 (Methodology) — closest available precedent for your exact planned workflow.** This is the first paper in your collection showing BBD + quadratic RSM + ANOVA + Design-Expert-style diagnostics (R², Adj R², Pred R², Adeq Precision, lack-of-fit test) applied directly to a Nigerian local-clay drilling mud, with real coded equations and full ANOVA tables reproducible as templates for how to present your own Chapter 4 results tables.
- **Chapter 3 — center-point replication precedent:** 5 center points out of 29 runs (~17%) for a 4-factor BBD is a useful benchmark; standard 3-factor BBD designs (yours) typically use 12 edge-midpoints + 3 center points = 15 runs, which your roadmap already specifies — this paper's ratio is broadly consistent.
- **Chapter 3 — diagnostic thresholds, directly citable:** the paper explicitly states the two standard acceptance criteria you should also apply and cite: (1) Predicted R² should be within ~0.2 of Adjusted R² ("reasonable agreement"); (2) Adeq Precision should exceed 4 ("adequate signal"). Useful as a secondary methodological citation alongside your core RSM/Box-Behnken sources.
- **Chapter 3/5 — cautionary example of a self-acknowledged borderline lack-of-fit result:** the PV model's lack-of-fit p=0.0561 (explicitly called "troubling" by the authors, who nonetheless proceeded to use the model) is a useful, citable example of how to handle and honestly report a borderline diagnostic result in your own thesis, rather than silently omitting it if your own models show similar marginal lack-of-fit issues.
- **Chapter 1/5 — limited response scope as a point of methodological differentiation for your own thesis:** this paper optimizes only AV and PV, omitting YP, gel strength, and fluid loss entirely, and does not benchmark against Wyoming bentonite or API 13A/13B-1 targets numerically anywhere in the results — your thesis's five-response, API-benchmarked design is a clear, citable methodological advance over this immediate precedent.
- **Introduction/economic framing:** reinforces the "import-substitution, locally sourced additive" framing already established across your Nigerian comparator set (Agwu 2015, Khan 2017, etc.) — cassava starch and corn cob ash are novel-to-your-collection local additives (distinct from the potash/Na₂CO₃/CMC/trona/Drispac already seen elsewhere), worth noting as another entry in the "diverse local additive" landscape if you want to survey additive diversity in Chapter 1/2.

## Caveats / limitations

1. **No mineralogical characterization beyond SEM** — no XRD, XRF, or CEC reported, so the clay's cation type (Ca vs. Na) and montmorillonite content are entirely unknown; the beneficiation rationale (why NaOH, specifically) is asserted rather than justified by measured exchangeable-cation deficiency, unlike your own planned Na/Ca-ratio-driven go/no-go decision framework.
2. **Table 4 is explicitly mislabeled "ANOVA for Apparent Viscosity"** in the original paper when its content (and the paper's own subsequent narrative) makes clear it is actually the plastic viscosity ANOVA — flagged here so you don't propagate the paper's own labeling error if citing this table.
3. **Only 4 rheometer speeds used (3, 100, 200, 300, 600 rpm)**, missing the 6 rpm reading used in the standard 6-speed API 13B-1 Fann-35 protocol — this means YP (which requires the 300 rpm reading, available here) could technically be back-calculated from their raw data, but gel strength (10-sec/10-min, which needs the 3 rpm/GEL reading after a rest period, not just a continuous run) cannot be reliably reconstructed from what's reported. The paper does not report YP or gel strength at all despite apparently having partial capability to do so.
4. **PV model shows meaningfully weaker predictive performance than the AV model** (Predicted R² 0.7621 vs. 0.9067, self-flagged borderline lack-of-fit) — if you want to cite this paper's PV results as a benchmark, note the model itself is less reliable than its AV counterpart.
5. **No benchmarking against Wyoming/commercial bentonite or explicit API 13A/13B-1 numeric targets anywhere in the paper** — the abstract claims results are "comparable to conventional drilling muds" but no side-by-side commercial-bentonite control formulation or numeric API comparison table is presented to substantiate this claim directly.
6. Small NaOH dosage range tested (1–2 g in 350 mL, i.e. a narrow band) relative to the coarser 2–6% (of clay mass) Na₂CO₃ range your own roadmap specifies — the two studies use different beneficiating agents (NaOH here vs. planned Na₂CO₃ for your thesis) and different dosing conventions (fixed gram range here vs. percentage-of-clay-mass planned for yours), so direct numeric comparison of optimal dosages is not meaningful across the two studies.
