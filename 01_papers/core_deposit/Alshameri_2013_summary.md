# Alshameri et al. (2013) — Characteristics, Modification and Environmental Application of Yemen's Natural Bentonite

**Full citation:** Alshameri, A., Abood, A.R., Yan, C., Muhammad, A.M. (2013). "Characteristics, modification and environmental application of Yemen's natural bentonite." *Arabian Journal of Geosciences*. DOI: 10.1007/s12517-013-0855-z. Received 17 Sep 2012 / Accepted 21 Jan 2013 / Published online 07 Feb 2013.

**Deposit/location:** Alaslaf area, ~7 km northeast of Alrahidah (Alqbitah), Lahij Province, south Yemen. Also referred to in the paper as "Alaslef-Alqabitah."

**Method:** Mineralogical/chemical/physical characterization (XRD, SEM, FTIR, chemical analysis, CEC, BET, swelling/water absorption) **+ an unrelated applied study**: synthesis of an organobentonite (CTAB-modified) and its use as an adsorbent for ammonium (NH₄⁺) removal from aqueous solution, with kinetics (pseudo-1st/2nd order, intraparticle diffusion) and isotherm modeling (Langmuir, Freundlich).

---

## ⚠️ Scope correction vs. current `references.md` entry

Your existing `references.md` entry describes this as your "core deposit" mineralogical source (correct) and as supporting "Methodology, Results" sections — **but this paper contains zero drilling-fluid, rheology, or filtration data.** It is fundamentally an environmental engineering paper about wastewater treatment. Recommend narrowing its "Cited in" tag to **Chapter 1 (background/deposit characterization) and Chapter 3 (as the source of baseline mineralogical/chemical/CEC data for the deposit)** — not "Methodology" in the drilling-fluid testing sense. Its value to you is entirely in the raw characterization numbers (Table 1, Table 2, CEC, XRD basal spacing, BET) — not the ammonium-adsorption experiments/models, which are not relevant to your thesis at all.

---

## Geological/site description (useful for Chapter 1 site background)

- Alaslaf area is covered by basic rocks (Migmatite–Gneiss) overlain by Triassic volcanics, represented by acidic rocks (Rhyolite–Tuff–Ignimbrite), basaltic rocks, and Quaternary deposits.
- **Internal inconsistency in the source paper itself:** the clay-bearing unit is described once as "greenish gray Rhyolitic tuff of Triassic age" and later, in the same paragraph block, as "Rhyolite tuff of tertiary" — likely an editing error in the original article. Worth being cautious citing an exact age from this paper alone; cross-check against Khaled & Philippe (2010), which they cite for the regional volcanic stratigraphy.
- Clay-bearing outcrops: decomposed to fine-grained friable soft mud with "soapy texture," some containing black volcanic glass (pitchstone), zeolite, and minor iron oxides.
- Outcrop thickness: ~2 m at the Alaslaf outcrop itself, up to 10 m in the Warzan-Simda valley. Lateral extent: 5–15 m at Alaslaf, up to 70 m at Warzan-Simda.
- Overlying tuffaceous ignimbrite: 1.5 m thick at Alaslaf, up to 15 m at Warzan-Simda.
- **Coordinates given in the paper are garbled/likely OCR-corrupted:** stated as "0429120E and 1479830N" — this is not valid DMS format (minutes/seconds can't exceed 59) and the leading digits don't match Yemen's actual longitude (~43–44° E, not 04° E). **This is exactly the "confirm exact sampling coordinates" open item already flagged in your `CHECKLIST_ROADMAP.md` Phase 0 — this paper does NOT resolve it and should not be relied on for GPS coordinates as printed.** You'll need the original geological map (Fig. 1b, UTM-gridded, scale 1:250,000) or field guidance to pin down the actual sampling point.

## Key mineralogical/chemical findings

**Semi-quantitative mineralogy (Table 1, wt%):**

| Mineral | Natural | Purified | Wyoming (natural/purified) | Tunisian (natural/purified) |
|---|---|---|---|---|
| Montmorillonite | 50–60% | >95% | 85% / 100% | 60% / 88% |
| Quartz | 10–15% | <5% | 10% / – | 5% / – |
| Gypsum | ~5% | – | – | – |
| Albite | ~15% | – | – | – |
| Calcite | ~5% | 5% (Wyoming natural) | – | 15% / – |
| Pyrophyllite | ~5% | – | – | – |

Purification method: crushed sample soaked in distilled water 12 h, HCl-dosed settling (0.1 M HCl, few drops), 8+ h settling, decant/dry cycles repeated multiple times — **this is essentially the same purification logic already in your `03_lab_protocols/` Arabic protocol**, useful as a secondary methods cross-check.

**Bulk chemical composition (Table 2, wt% oxides):**

| Oxide | Natural | Purified |
|---|---|---|
| SiO₂ | 62.12 | 54.18 |
| Al₂O₃ | 14.53 | 15.55 |
| Fe₂O₃ | 4.25 | 5.53 |
| TiO₂ | 0.45 | 0.59 |
| MgO | 1.81 | 1.48 |
| Na₂O | 1.88 | 2.80 |
| CaO | 1.59 | 0.74 |
| K₂O | 0.74 | 0.30 |
| LOI | 13.03 | 19.06 |

**Important methodological caveat for your Na/Ca risk-flag calculation:** these are **bulk oxide percentages from whole-rock chemical analysis**, not exchangeable-cation concentrations from a CEC/ammonium-acetate extraction. Bulk Na₂O and CaO include Na/Ca locked in non-exchangeable phases (e.g., albite is a major Na-bearing mineral here at ~15% of the natural sample; gypsum/calcite are non-exchangeable Ca-carriers). Computing a "Na/Ca ratio" directly from Table 2 (roughly molar Na/Ca ≈ 2.1 natural, ≈6.9 purified) is **not the same metric** as the Khan et al. (2017) exchangeable-cation-based Na/Ca ratio your methodology (Phase 1 go/no-go decision) is built around. **Don't use Table 2 oxide data as a substitute for an actual CEC/exchangeable-cation test on your own Alaslaf sample.**

**More diagnostically useful:** the natural bentonite's XRD basal spacing (d₀₀₁) = **15.3 Å**. After forced Na-saturation (1 M NaCl, 12 h stirring, repeated 3×) it dropped to **12.6 Å**. A d₀₀₁ of ~15 Å is classically associated with Ca²⁺-dominated smectite in its 2-water-layer hydrated state, while ~12.4–12.6 Å is typical of Na⁺-dominated smectite. **This is a genuinely useful independent line of evidence supporting the "likely Ca-dominant, may need Na-activation" hypothesis already flagged in your references.md risk discussion** — worth citing specifically for that point rather than the oxide ratios.

**Other measured properties (method appears to be on purified or natural sample — paper doesn't fully disambiguate, worth flagging as a limitation):**
- CEC = 129.94 mmol/100g (equivalent to ~130 meq/100g — reasonably high, consistent with a mostly-smectite purified fraction)
- Water absorption = 202%
- Gelling value = 98 mL/15g
- Swelling capacity = 32.5 mL/g
- BET surface area: natural bentonite 32.5 m²/g (total pore volume 0.0033 mL/g, avg. pore diameter 72.55 Å); CTAB-modified bentonite 8.5 m²/g (0.0004 mL/g, 170.9 Å) — the modified-bentonite BET values are not relevant to your thesis (post-organomodification), only the **natural bentonite BET value (32.5 m²/g)** is a usable baseline number.

## Not relevant to this thesis (do not cite for these)

- CTAB/organobentonite synthesis procedure and characterization (IR peaks, SEM "corn flakes" texture description, d₀₀₁ = 19.7 Å for the CTAB-modified material)
- Ammonium adsorption kinetics (pseudo-1st/2nd order rate constants), Langmuir/Freundlich isotherm parameters, pH/dosage effect curves — this is a wastewater-treatment application entirely orthogonal to drilling fluids

## Relevance to this thesis

- **Chapter 1 (Introduction/Background):** primary and currently only source for site description, outcrop geometry, and geological setting of the Alaslaf locality; also the only existing published mineralogical/chemical baseline for the deposit — retain as the "only existing characterization" citation.
- **Chapter 3 (Methodology):** useful as a secondary cross-check for a purification procedure (dilute HCl-assisted sedimentation), and as prior XRD basal-spacing evidence motivating your own Na/Ca work.
- **NOT usable** as a source for rheology, filtration, or API-13B-relevant data — the paper contains none.

## Caveats / limitations

1. Not a drilling-fluid-application paper — scope is environmental (ammonium adsorption). Only the raw characterization data (mineralogy, chemistry, CEC, BET, XRD spacing) transfers to your thesis.
2. Sample coordinates as printed in the paper are corrupted/unusable — still need field-verified GPS coordinates (open Phase 0 item).
3. Table 2's Na₂O/CaO values are bulk oxide chemistry, not exchangeable-cation chemistry — do not conflate with the Khan (2017)-style Na/Ca ratio needed for your go/no-go decision.
4. Internal inconsistency in stated age of the host tuff (Triassic vs. "tertiary" in different paragraphs) — cross-check against Khaled & Philippe (2010) before using an age claim in Chapter 1.
5. Unclear whether CEC/water absorption/gelling/swelling values (129.94 mmol/100g etc.) were measured on the natural or purified sample — paper doesn't explicitly state; treat as approximate until clarified, or plan to generate your own CEC data in Phase 1 regardless.
