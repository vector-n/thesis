# Magzoub et al. (2018) — Thermochemical Upgrading of Calcium-Bentonite for Drilling Fluid Applications

**Full citation:** Magzoub, M., Mahmoud, M., Nasser, M., Hussein, I., Elkatatny, S., and Sultan, A. (2018). "Thermochemical Upgrading of Calcium-Bentonite for Drilling Fluid Applications." *Journal of Energy Resources Technology*, ASME. DOI: 10.1115/1.4041843. Received July 15, 2018; accepted October 31, 2018.

**Authors' affiliations:** Qatar University (Gas Processing Center) and KFUPM Petroleum Engineering Department / Center of Integrated Petroleum Research, Dhahran, Saudi Arabia.

**Deposit/location:** Ca-bentonite outcrop, Jeddah, South-Western Saudi Arabia.

**Method:** Purification of raw Ca-bentonite via an integrated multi-stage sedimentation + wet-sieving process (75 µm, >95% recovery) → characterization (XRD, SEM, EDX, laser-scattering particle size analysis) → soda ash (Na₂CO₃) dosing trial (2, 4, 12 wt.%) → **combined thermochemical treatment** (Na₂CO₃ addition + simultaneous heating at 70–90°C + stirring, time-optimized at 1/3/6/12/24 hr) → rheological (flow sweep, oscillation/frequency sweep, Fann 35) and API filtration benchmarking against commercial Na-bentonite (Sigma Aldrich) → performance testing in two full drilling-fluid formulations (unweighted 8.6 ppg and barite-weighted 11.16 ppg).

---

## ⚠️ Important note before using this paper: near-identical prior work by the same authors

This paper is **very likely the same underlying research program as Magzoub (2014)**, already summarized in your base (`Magzoub_2014_summary.md`) — same lead author, same KFUPM co-authors (Mahmoud, Nasser, Hussein, Sultan), and reference [22] in this 2018 paper is literally the authors' own 2017 US patent (US 9,676,669, "Method of producing sodium bentonite") covering the thermochemical process. The 2014 thesis was on **Khulays** bentonite (~95 km north of Jeddah); this 2018 paper says simply "Jeddah" — plausibly the same Khulays deposit described more loosely, or a related nearby outcrop. **Worth verifying whether this is the same physical deposit before treating the two as independent corroborating data points** — if so, cite as one continuous research program (thesis → patent → journal paper) rather than two separate validations.

The key methodological difference from 2014: the 2014 thesis's "novel" activation was soda-ash-dosing *then* separate heating/stirring; this 2018 paper's "thermochemical treatment" explicitly combines Na₂CO₃ addition **simultaneously** with heating (70–90°C) and stirring in one step — a refinement/optimization of the same core idea, framed here as resulting in bentonite platelet expansion that lets water invade interlayer spaces during the ion-exchange process itself, producing swelling that is retained on cooling.

## Key findings

**Optimum soda ash dose (Section 3.1, Fig. 5):** Chemical-only (soda ash, no heat) treatment showed viscosity increasing with Na₂CO₃ up to **4 wt.%**, then declining with further addition — this is identified as the point where calcium is fully replaced by sodium. Matches the "few % Na₂CO₃, typically 2–4%" consensus already documented from other papers in your base (Hassan 1998, ElMahllawy 2013, etc.) and is consistent with (not contradicting) Magzoub 2014's ~13 wt.%-relative-to-clay optimum found via a different dosing basis — **note the two papers use different % bases (this paper: wt.% of Na₂CO�3 relative to bentonite mass in a 6 wt.% suspension; 2014 thesis: grams per fixed bentonite mass) — take care not to directly equate the numbers without reconciling basis.**

**Thermochemical treatment impact (Section 3.1, Fig. 6):** At 4 wt.% Na₂CO₃, heating at 70°C for 24 hr increased viscosity at low shear rate (1 s⁻¹) from 0.92 to 4.1 Pa·s, and at high shear rate (60 s⁻¹) from 0.033 to 0.21 Pa·s — an order-of-magnitude-scale improvement attributable to the heat/stir step alone (on top of the soda-ash-only baseline).

**EDX / Na-Ca chemistry (Table 2) — directly comparable to Magzoub 2014's table:**

| Sample | Na (wt%) | Ca (wt%) | Na/Ca ratio |
|---|---|---|---|
| Commercial Na-bentonite | 1.39 | 0.48 | **2.89** |
| As-received Ca-bentonite | 0.75 | 0.82 | 0.915 |
| Raw (purified) Ca-bentonite | 0.77 | 0.89 | 1.97 |
| **Upgraded (thermochemically treated) Ca-bentonite** | 2.35 | 0.80 | **2.95** |

This is the paper's headline number: **thermochemical treatment pushed the Na/Ca ratio to 2.95 — actually exceeding the commercial Na-bentonite's 2.89** — i.e., full or over-conversion from Ca- to Na-bentonite by this metric. This is a materially stronger claimed result than Magzoub 2014 (which only reached ~1.77–2.04 even after soda-ash treatment, never approaching or exceeding the commercial reference). Useful contrast point: identical research group, same general deposit region, but the simultaneous-heat-and-chemical method in this 2018 paper claims a substantially better ion-exchange outcome than the sequential method in the 2014 thesis.

**Particle size distribution (Section 3, Fig. 4):** As-received: d10=1.92, d50=15.5, d90=1229 µm, Dₙ=213.6 µm (very wide/coarse — impurity-dominated). After purification only: d10=0.96, d50=3.45, d90=10.42 µm, Dₙ=4.9 µm — closely matching commercial Na-bentonite's stated 2–4 µm and meeting API specs on residue/fineness grounds.

**Rheology — API dial readings (Section 3.3, Fig. 10):**

| Sample | 300 rpm | 600 rpm | AV (cP) | PV (cP) | YP (lb/100ft²) |
|---|---|---|---|---|---|
| Raw Ca-bentonite | 2.8 | 5 | 2.5 | 2.2 | 1 |
| Commercial Na-bentonite | 15 | 23 | 11.5 | — | — |
| Upgraded Ca-bentonite | 35 | 40 | 20 | 6 | 28 |

Upgraded Ca-bentonite's 600-rpm dial reading (40) and AV (20 cP) both **exceed** commercial Na-bentonite's (23 rpm, 11.5 cP) — comfortably clears the API 13A minimum of 30 at 600 rpm (Table 1 in this paper, consistent with the API 13A limits your closed reference thread already verified).

**API filtration (Section 3.3, Fig. 11) — the standout result:**
- Raw Ca-bentonite: ~70 mL/30min (grossly non-compliant vs. API ≤15 mL)
- Commercial Na-bentonite: 14.5 mL/30min
- **Thermochemically upgraded Ca-bentonite: 11.8 mL/30min** — better than the commercial reference, and comfortably under the API 15 mL limit.

This directly contradicts the "rheology improves but filtration remains the harder problem" narrative from Magzoub 2014 (which topped out at 28 mL, still non-compliant) — in this 2018 paper, filtration control is fully solved and even outperforms commercial bentonite. **This is the strongest evidence in either Magzoub paper that the combined simultaneous heat+chemical approach is mechanistically superior to sequential treatment**, and is worth flagging explicitly in your Ch. 2 lit review as the more promising activation protocol to model your own Phase 1 activation trial on.

**Real drilling-fluid formulation testing (Section 3.4–3.5, Tables 3–5):**
- Formula 1 (unweighted, 8.6 ppg, xanthan gum + CaCO₃ system): upgraded Ca-bentonite gave PV=10, YP=40 vs. commercial's PV=20, YP=25 — lower PV (easier pumping) with higher YP (better hole cleaning) than commercial.
- Formula 2 (barite-weighted, 11.16 ppg, CMC system), hot-rolled at 71°C and 93.3°C: upgraded Ca-bentonite maintained YP/PV ratios of 1.02 (160°F) and 1.24 (200°F), both within the API-recommended YP/PV ≤3 range, and outperformed commercial bentonite's YP at high temperature (52 vs. 45 lb/100ft² at 200°F) — evidence of good thermal stability at HPHT-relevant conditions.
- Authors apply a hole-cleaning-efficiency correlation (their own prior work, Mahmoud 2006 MS thesis) predicting 100% cleaning efficiency for the upgraded-bentonite mud in an example 8.5" vertical hole scenario.

## Numbers worth citing directly

- Optimum soda ash dose: 4 wt.% Na₂CO₃ (matches broader literature consensus of 2–4%)
- Na/Ca ratio: commercial 2.89 → as-received 0.915 → purified-only 1.97 → thermochemically upgraded **2.95** (exceeds commercial)
- Thermochemical treatment temperature/time: 70–90°C, optimized duration up to 24 hr (heating kept <100°C to avoid evaporation)
- API filtration: raw Ca-bentonite 70 mL → thermochemically upgraded 11.8 mL (vs. commercial 14.5 mL, vs. API max 15 mL) — **upgraded material beats both the commercial reference and the API limit**
- Rheology: AV 2.5→20 cP, PV 2.2→6 cP, YP 1→28 lb/100ft² (raw → upgraded)
- PSD after purification: Dₙ = 4.9 µm (vs. 213.6 µm as-received), closely matching commercial's 2–4 µm
- API 13A specs restated (Table 1, consistent with your closed reference thread): dial@600rpm min 30; YP/PV max 3; filtration max 15 cm³/30min; residue on 75 µm max 4.0 wt%; moisture max 10.0 wt%

## Relevance to this thesis

- **Chapter 3 (Methodology):** This is your best available template for a *combined* simultaneous soda-ash + heat + stir activation protocol (vs. Magzoub 2014's sequential approach) — given its superior filtration outcome, consider explicitly modeling your own Na-activation trial (Phase 1, "if Na/Ca < 0.5 → trigger Na-activation") on this 2018 method rather than, or in addition to, the 2014 thesis's protocol. Their purification flow chart (multi-stage sedimentation tanks + wet sieving through 75 µm) is also a clean, directly reusable process diagram template for your Chapter 3 purification section.
- **Chapter 2 (Literature Review):** Strengthens the "local Ca-bentonite bentonite can be fully upgraded to match or exceed commercial Na-bentonite" claim — but pair this optimistic result with the more cautious/partial-success outcomes in Magzoub 2014, Al-Qunaibit-referenced Saudi studies (up to 5 wt.% Na₂CO₃ insufficient without added xanthan/CMC), and Akinwumi 2015, so your lit review doesn't overstate what's uniformly achievable across different deposits.
- **Chapter 3/5:** Useful precedent for reporting YP/PV ratio at multiple hot-rolling temperatures (160°F/200°F) as a thermal-stability metric — directly transferable to your own HPHT rheology reporting plan (Phase 3).
- Table 1 in this paper is another independent restatement of the API 13A specs consistent with your already-closed API 13A/13B-1 reference thread — no new discrepancy to resolve, but useful as an additional citation for those numbers.

## Caveats / limitations

1. **Possible non-independence from Magzoub (2014)** — flagged above; verify deposit identity (Khulays vs. "Jeddah") before citing both as separate corroborating studies. If the same underlying dataset/process was carried from MS thesis → patent → journal paper, treat this 2018 paper as the authoritative, most-refined published version and cite it preferentially over the unpublished thesis where they overlap.
2. Table 2's commercial Na-bentonite Na/Ca ratio (2.89) is presented as a single value with no replicate/error data — same limitation noted for Magzoub 2014's EDX data; treat all EDX-derived ratios as point estimates only.
3. The paper reports no XRD basal-spacing shift data (unlike your own Phase 1 protocol, which specifies confirming activation via "XRD basal-spacing shift + CEC change") — this paper relies on Na/Ca ratio, PSD, and rheology/filtration as its activation-confirmation evidence, not on quantitative XRD d-spacing values. If you want an XRD-basal-spacing precedent specifically, check the na_activation_mechanism papers (Bahranowski 2021, Karaguzel 2010) still pending summary.
4. Single-deposit case study; the strong filtration result (11.8 mL, beating commercial) should not be assumed to generalize automatically to Alaslaf bentonite, which has a different parent-rock origin (per Alshameri 2013, Triassic rhyolitic tuff vs. this paper's Jeddah outcrop).
5. No statistical/replicate reporting (single values throughout, no error bars, no ANOVA) — consistent with most of your local_clay_benchmarking cluster, and a good talking point for why your thesis's RSM/statistical approach (t-test/ANOVA vs. benchmark, per your Phase 3 checklist) is a methodological improvement over the bulk of this literature.
