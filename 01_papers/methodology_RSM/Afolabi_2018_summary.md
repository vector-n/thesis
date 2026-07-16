# Afolabi, Ogunkunle, Olabode & Yusuf (2018) — Dataset on the Beneficiation of a Nigerian Bentonite Clay Mineral for Drilling Mud Formulation

**Full citation:** Afolabi, R.O., Ogunkunle, T.F., Olabode, O.A., Yusuf, E.O. (2018). "Dataset on the beneficiation of a Nigerian bentonite clay mineral for drilling mud formulation." *Data in Brief*, 20, [in press at time of publication]. DOI: 10.1016/j.dib.2018.07.071. Open access, CC BY 4.0. Authors affiliated with Department of Petroleum Engineering (Afolabi, Ogunkunle, Olabode) and Department of Chemical Engineering (Yusuf), Covenant University, Ota, Ogun State, Nigeria.

**Type of paper:** *Data in Brief* — a data-descriptor journal article, not a conventional results/discussion paper. Presents the raw dataset, design matrix, and fitted statistical models underlying a companion study (Afolabi et al. 2017, cited as ref [1] in this paper — not yet in your reference base, worth obtaining: "Optimizing the rheological properties of silica nano-modified bentonite mud using overlaid contour plot..."). Note this is a **different Afolabi et al. paper from the one already in your `local_clay_benchmarking/Afolabi_2017_summary.md`** — check whether that summary is of the Applied Clay Science review (ref [2] here) or something else, since Afolabi appears as both a review-paper author and an RSM-dataset author in your reference base; worth a quick cross-check to avoid conflating the two.

**Deposit/location:** Ewekoro, Ogun State, South-West Nigeria (6°56′N, 3°13′E). Raw, non-treated bentonite clay. Same general South-Western Nigeria region already flagged in Agwu (2015) as the *only* SW Nigeria location among ~40 reviewed studies — useful cross-reference (Agwu's Table 2 lists a 2010 Salam et al. Ewekoro study; this Afolabi paper appears to be a later, separate study of the same locality).

---

## Method — this is your most directly relevant RSM precedent yet: **4-factor Central Composite Design (CCD)**, not Box-Behnken

**Design:** 2⁴ (2-level, 4-factor) **Central Composite Design**, 31 runs total (Table 2), generated and analyzed in **Minitab 17** — note this is the same software your own roadmap specifies, making this a directly useful "what the Minitab CCD/RSM output looks like in practice" template, even though your thesis uses Box-Behnken rather than CCD (same CCD-vs-BBD distinction already flagged in your Derringer & Suich 1980 summary).

**Four independent variables and their 5 coded levels (−2, −1, 0, +1, +2) — Table 1:**

| Variable | −2 | −1 | 0 | +1 | +2 |
|---|---|---|---|---|---|
| Bentonite content, g (X₁) | 20 | 25 | 30 | 35 | 40 |
| Polymer content, g (X₂) | 2.5 | 5 | 7.5 | 10 | 12.5 |
| Sodium carbonate, g (X₃) | 2 | 4 | 6 | 8 | 10 |
| Aging time, h (X₄) | 5 | 10 | 15 | 20 | 25 |

Polymer used: **Kelzan® XCD** — a xanthan gum biopolymer (white-tan powder, SG 1.5 at 25°C, pH 7.0 in 1 wt% solution). Sodium carbonate: high-purity Sigma Aldrich reagent grade (Ca <0.03%, Fe <5ppm, etc. — i.e., not a "local" additive like the trona/local materials used in several of your other Nigerian sources; this is lab-grade Na₂CO₃, directly comparable to what your own thesis will likely use).

**Beneficiation procedure (explicitly stated as following James et al. 2008, already in your reference base as [7] in this paper — a useful convergence point since James et al. 2008 is also cited independently in your Agwu 2015 review):**
1. Crush clay, remove pebbles/dirt, sieve to 2 mm to remove coarse particles
2. Oven-dry at 150–200°C to remove moisture/volatiles/combustible organics
3. Mill and screen to 150 μm
4. **Sodium saturation:** 25–50 g screened clay in 100 cm³ solution containing **2–10 g Na₂CO₃**, stir 30 min
5. Adjust suspension pH to **11–12 with 0.1 M NaOH**, stir a further 30 min
6. **Age 5–48 h** (this is your X₄ variable — a much longer aging window than typical, worth comparing against your own lab protocol's soaking-time flexibility already discussed in session 1)
7. Extract clay particles (2 mm) by repeated sedimentation and siphoning
8. Air dry, then treat with **5–12.5 g Kelzan XCD polymer** to improve rheology

**Rheological measurement:** OFITE Model 800 **8-speed** viscometer (3, 6, 30, 60, 100, 200, 300, 600 rpm) — a fuller speed range than the standard 6-speed Fann 35 your roadmap specifies, though PV/YP/AV here are calculated using only the standard θ600/θ300 readings via the conventional API equations (PV = θ600−θ300; YP = θ300−PV; AV = θ600/2).

**Response variable actually modeled via full ANOVA: YP/PV ratio** — chosen specifically because API Spec 13A imposes a **YP/PV ratio ≤ 3 (maximum)** as an explicit acceptance criterion (Table 3 in the paper, reproducing the API 13A requirement alongside θ600 ≥30 minimum and θ300 ≤24 maximum) — this is a clean, directly citable confirmation of an API 13A numeric criterion beyond the filtrate limits your standing reference document already resolved, useful to fold into that same API-standards reference file.

## Key results

**YP/PV model (the only one given full ANOVA treatment — Table 4):**
$$YP/PV = 1.55 - 0.1510X_1 + 0.3400X_2 + 0.1150X_3 + 0.0480X_4 + 0.00352X_2^2$$
- Model highly significant overall: F=44.77, p<0.0001
- All four linear terms significant (X₁, X₂, X₃, X₄ all p≤0.003); only X₂² (polymer quadratic term) retained as significant among squared terms (p=0.037); no interaction terms retained in the final model
- **Fit quality: R²=0.9411, Adj R²=0.9211, Pred R²=0.7996** — reasonably strong fit, though note the gap between Adjusted (0.9211) and Predicted (0.7996) R² is 0.1215, within the ~0.2 "reasonable agreement" threshold already noted in your Ossai (2025) summary.
- **Note the sign of X₁ (bentonite content) is negative** (−0.1510): increasing bentonite content *decreases* the YP/PV ratio in this model — i.e., pushes it further from the API maximum-3 ceiling, a beneficial direction. Polymer (X₂) has the largest positive coefficient (0.34) — polymer addition is the dominant driver increasing YP/PV toward (and potentially past) the API ceiling, so polymer dosage requires the most careful upper-bound control to avoid exceeding YP/PV=3.

**Other rheological properties (PV, YP, AV, θ600) — coefficients given (Table 5) but described as fitted models without a full reported ANOVA/significance breakdown in this particular paper (that level of detail may be in the companion Afolabi et al. 2017 paper referenced as [1]):**

| Response | β₀ | β₁ (Bentonite) | β₂ (Polymer) | β₃ (Na₂CO₃) | β₄ (Aging) | Other terms |
|---|---|---|---|---|---|---|
| PV | 19.90 | 1.25 | 4.08 | 0.67 | – | β₁₃=1.63 |
| YP | 81.35 | 7.50 | 26.25 | 4.75 | 3.08 | β₁₂=6.87, β₁₃=7.37, β₁₄=10.63 |
| AV | 60.58 | 5.00 | 17.21 | 3.21 | 2.21 | β₁₂=3.69, β₁₃=4.69, β₁₄=6.94 |
| θ600 | 121.16 | 10.00 | 34.42 | 6.42 | 4.42 | β₁₂=7.37, β₁₃=9.37, β₁₄=13.88 |

**Pattern across all four of these responses:** polymer (X₂) has by far the largest positive coefficient in every model (4.08–34.42, roughly 3–4× the bentonite coefficient in each case) — **Kelzan XCD polymer is the dominant driver of all rheological responses in this system**, consistently larger in effect than bentonite content, sodium carbonate, or aging time. This is a clean, directly citable finding if your own CMC (your planned third factor) shows a similarly dominant effect relative to clay concentration and Na₂CO₃ dosage.

**Overall conclusion (abstract):** beneficiation with sodium carbonate + Kelzan XCD polymer produced rheological properties "comparable with the API specification 13-A."

## Numbers worth citing directly

- API 13A YP/PV ratio requirement: **≤3 maximum** (Table 3, directly from the API specification — a second, independently useful API 13A numeric criterion for your standing API-standards reference document, alongside the filtrate limits already resolved)
- API 13A θ600 ≥30 minimum, θ300 ≤24 maximum (also Table 3)
- YP/PV model: R²=0.9411, Adj R²=0.9211, Pred R²=0.7996, F=44.77 (p<0.0001)
- Beneficiation protocol: 2–10 g Na₂CO₃ per 25–50 g clay in 100 cm³ solution; pH adjusted to 11–12; aging 5–48 h; 5–12.5 g Kelzan XCD polymer post-treatment
- Polymer (Kelzan XCD) coefficient consistently 3–4× larger than bentonite-content coefficient across PV, YP, AV, θ600 models — polymer is the dominant rheology-driving factor in this system
- Viscosity conversion: η (cp) = K·F·θ/RPM, with F=1, K=300 for R1B1 rotor/bob combination (OFITE convention — useful methodological reference for unit conversions in your own equipment write-up if using a similar viscometer)

## Relevance to this thesis

- **Chapter 3 (Methodology) — strong precedent for Minitab-based CCD/RSM workflow**, directly matching your planned software (Minitab), giving you a template for how coded-variable regression equations and ANOVA tables are conventionally presented for drilling-mud rheology in this literature.
- **Chapter 3 — YP/PV ratio as a candidate response/constraint:** consider whether to add YP/PV ≤3 as an explicit constraint or secondary response alongside your five planned responses (PV, YP, AV, gel strength, fluid loss) — this paper demonstrates it's a single API-13A-derived criterion that folds two of your existing planned responses (PV, YP) into one dimensionless target, potentially useful as an additional composite check in your Chapter 4/5 results discussion, or as an input to your Derringer & Suich desirability-function optimization (Chapter 3) alongside your other four responses.
- **Chapter 3/5 — polymer-dominance finding directly transferable framing:** if your own CMC factor shows a similarly outsized effect relative to clay concentration and Na₂CO₃ dosage in your Box-Behnken results, this paper gives you a directly citable precedent ("consistent with Afolabi et al. (2018), who found polymer/viscosifier dosage to be the dominant driver of rheological response, exceeding the effect of base clay content, in a structurally similar four-factor Nigerian bentonite RSM study").
- **Chapter 1/2 — standing API reference update:** this paper's Table 3 gives you a second, independently verified primary-standard citation for the YP/PV ≤3 requirement, worth adding to your existing API 13A/13B-1 standing reference document alongside the filtrate-limit thread already closed.
- **Methodological note for Chapter 3:** the beneficiation protocol here (Na₂CO₃ dosage varied 2–10 g against a fixed 25–50 g clay charge, i.e., roughly **4–40% Na₂CO₃ by clay mass** depending on which end of both ranges is combined) is a notably wider dosage range than your own roadmap's planned 2–6% Na₂CO₃ — worth a brief comparative note on why you've scoped your own trial range more narrowly (likely reflecting your Alaslaf clay's specific Na/Ca deficiency being less severe, pending your own Phase 1 characterization results).

## Caveats / limitations

1. **Full ANOVA/significance testing is reported only for the YP/PV composite response** (Table 4) — the PV, YP, AV, and θ600 models (Table 5) give fitted coefficients only, without R², F-values, or per-term p-values in this particular paper. If you want the full statistical diagnostics for those four individual responses, you likely need the companion paper (Afolabi et al. 2017, ref [1], "Optimizing the rheological properties of silica nano-modified bentonite mud using overlaid contour plot..." — *Cogent Engineering* 4(1)) — **recommend sourcing this companion paper if full diagnostics for PV/YP/AV/θ600 individually are needed for direct methodological comparison.**
2. As a *Data in Brief* article, this is explicitly a data-descriptor paper, not a full results/discussion paper — interpretation and discussion of the findings (beyond the bare statement that results were "comparable" to API 13A) is minimal; deeper interpretation likely again resides in the companion Cogent Engineering paper.
3. No mineralogical characterization (XRD/XRF/CEC) reported in this paper for the Ewekoro clay itself — Ca vs. Na dominance is inferred only implicitly from the fact that Na-saturation beneficiation was undertaken at all, not from a measured baseline exchangeable-cation ratio.
4. Lab-grade (Sigma Aldrich) Na₂CO₃ used, not a locally sourced material — this study sits closer to your own thesis's likely approach (using a defined, controlled reagent) than to the "local additive" studies elsewhere in your Nigerian comparator set (cassava starch, corn cob ash, trona, potash, etc.), worth noting when grouping/contrasting your comparator studies by additive type in Chapter 1/2.
5. CCD with axial points at ±2 coded levels reaching fairly wide extremes (e.g., bentonite content spans 20–40 g, a 2× range) — worth checking whether your own Box-Behnken factor ranges are proportionally as wide, since BBD's avoidance of extreme corner combinations is specifically meant to keep testing within a more realistic/achievable region, per the same design-choice rationale already flagged in your Derringer & Suich (1980) summary.
