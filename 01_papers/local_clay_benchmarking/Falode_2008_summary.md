# Falode et al. (2008) — Evaluation of Local Bentonitic Clay as Oil Well Drilling Fluids in Nigeria

**Full citation:** Falode, O.A., Ehinola, O.A., Nebeife, P.C. (2008). "Evaluation of local bentonitic clay as oil well drilling fluids in Nigeria." *Applied Clay Science*, 39, 19–27. DOI: 10.1016/j.clay.2007.04.011. Received 22 Jul 2006; revised 10 Apr 2007; accepted 19 Apr 2007. Authors affiliated with University of Ibadan (Petroleum Engineering and Geology departments), Nigeria.

**Deposit/location:** Pindiga Formation, Yalmatu-Deba Local Government Area, Gombe State, Northeastern Nigeria (Upper Benue Trough, Borno Basin). Coordinates stated as longitude 11°23′E, latitude 11°26′N — **correctly labeled this time** (unlike the coordinate-axis-swap errors already flagged in Alshameri 2013 and Akinwumi 2015).

**Method:** Fresh clay collected from a pit dug to 1.6 m depth (dry season) → sun-dried 5 days, ground, sieved to 63 µm fraction → XRD (X'Pert Pro PAnalytical) mineralogical analysis, chemical composition (cited from a prior B.Sc. thesis, Ademibawa 1999) → mud preparation at six concentrations (20, 40, 60, 80, 115, 125 g/350 mL) benchmarked against a Wyoming bentonite control (20 g/350 mL) → rheological (four-speed Rheometer Model 286: PV, AV, YP) and filtration (low-pressure filter press) testing, unbeneficiated → beneficiation trials using Na₂CO₃ (0–10%, tested across the clay-concentration range), potash (0–5 g at fixed 40 g/350 mL clay), and starch (fixed 40 g/350 mL clay, variable dose) → final comparison against Wyoming bentonite and API specification (referenced qualitatively, no specific numeric API table reproduced in this paper).

---

## Major finding: this paper is very likely the *original source* of a figure you'd already flagged as suspicious in Khan (2017)

In your Khan (2017) and Afolabi (2017) summaries, you flagged that Khan's reported "55% and 33% reduction in mud cake thickness" (attributed to starch and CMC HV) was suspiciously identical to the same percentages reported for Falode (2008)'s Pindiga work (attributed to starch and potash). **Having now read Falode (2008) directly, this is confirmed as the original, primary source of those exact figures**: Falode's own conclusion states *"there was a reduction of about 55% and 33% in mud cake thickness as starch and potash were used respectively."* Khan (2017)'s conclusion states *"there was a reduction of about 55% and 33% in the mud cake thickness as starch and CMC HV was used to support the local mud"* — nearly identical sentence structure, identical percentages, with only the second additive's name swapped (potash → CMC HV). **Falode (2008) is explicitly reference [43] in Khan (2017)'s own bibliography**, confirming Khan had direct access to this paper while writing. This is a significant citation-integrity concern worth being cautious about: **it looks like Khan et al. (2017) may have reused Falode's reported percentage figures and framing language rather than reporting a genuinely independent measurement from their own Jhelum/Jundola experiments for this specific metric.** Recommend not treating Khan's mud-cake-thickness figures as fully independent corroboration of anything — if you cite mud-cake-thickness reduction numbers, cite Falode (2008) as the primary/original source and treat Khan's identical figures with appropriate skepticism.

## Key findings

**Chemical composition (Table 1, cited from Ademibawa 1999) — matches Afolabi (2017)'s review data exactly, good cross-check:**

| Oxide | Pindiga | Wyoming |
|---|---|---|
| SiO₂ | 53.06 | 47.37 |
| Al₂O₃ | 12.09 | 17.82 |
| Fe₂O₃ | 2.71 | 1.72 |
| CaO | 1.30 | 1.41 |
| MgO | 1.10 | 1.50 |
| MnO | 0.08 | 0.10 |
| Na₂O | 6.40 | 15.41 |
| TiO₂ | 1.53 | 1.17 |
| K₂O | 1.25 | 0.88 |
| LOI | 20.19 | 12.00 |

**⚠️ Arithmetic check flags an apparent error in the paper's own text:** The paper states the Al₂O₃/SiO₂ ratio "was approximately 1/3 in Wyoming bentonite... while it was higher in Pindiga clay." **Computing the ratio directly from the paper's own Table 1 gives the opposite result**: Wyoming = 17.82/47.37 ≈ 0.376 (≈1/2.7, roughly consistent with "approximately 1/3"), but Pindiga = 12.09/53.06 ≈ 0.228 (≈1/4.4) — **Pindiga's ratio is lower than Wyoming's, not higher, contradicting the paper's own stated claim.** Worth flagging as a likely writing error in the original paper (possibly the comparison direction was meant to run the other way, or "higher" was meant to describe SiO₂ dominance rather than the ratio itself) — recommend not repeating this specific claim in your own thesis without independently verifying the ratio direction, which the raw table data does allow you to do yourself.

**Mineralogy (Table 2, XRD-derived semi-quantitative):**

| Sample | Quartz | Calcite | Biotite | Feldspar (Albite) | Montmorillonite | Kaolinite | Total clay fraction |
|---|---|---|---|---|---|---|---|
| Pindiga | 44.57 | 11.38 | 3.23 | 13.78 | 22.19 | 4.81 | ~27% |
| Wyoming | 23.98 | 8.32 | 3.23 | 23.98 | 35.85 | 5.01 | ~41% |

**Note the text itself has the clay-ratio figures transposed**: it states *"The Wyoming and Pindiga bentonite samples studied have clay ratios of 27 and 40% respectively"* — but the table data actually gives Pindiga ≈27% clay and Wyoming ≈41% clay, i.e., the sentence has the two deposits' figures swapped relative to the table. **Use the table values (Pindiga ~27%, Wyoming ~41%), not the transposed sentence, when citing this.** This is a **notably low montmorillonite content for Pindiga (22.19%)** — lower than most other Nigerian deposits reported in Afolabi (2017)'s review (which ranged higher for most locations) — and a substantial quartz+feldspar impurity load (44.57% + 13.78% = 58.35% combined), consistent with the very poor raw rheological performance described below.

**Raw (unbeneficiated) rheological/physical properties (Figs. 4–7):**
- **Density:** slight increase at lower clay concentrations, sharp increase at higher concentrations; optimum mud density obtained at **115 g/350 mL**.
- **Sand content:** no significant change with concentration — abrasivity not a significant factor for this material.
- **Rheology:** apparent viscosity, plastic viscosity, and yield point all increased substantially as clay concentration rose from 20 to 125 g/350 mL; **optimum rheological properties approximating Wyoming mud observed at 80 g/350 mL** — i.e., roughly 4× the standard reference loading, structurally identical to the "raw local clay needs 3–4× standard concentration to match commercial bentonite" pattern already established in your Khan (2017) summary (where Jhelum needed 80 g/350 mL and Jundola 60 g/350 mL against the same 20–21 g/350 mL API reference basis).
- **Filtration:** filtrate loss decreased as clay concentration increased, but **remained higher than the Wyoming control's filtrate loss at every single concentration tested, including the highest (125 g/350 mL)** — Pindiga clay never closed the filtration gap with Wyoming through concentration alone, unlike its rheological properties which did approach Wyoming's at 80 g/350 mL.

**Beneficiation with Na₂CO₃ (0–10%, across the clay-concentration range):** Dial readings and plastic viscosity increased with both increasing Na₂CO₃ concentration (0→10%) and increasing clay concentration; **a similar rheological trend to Wyoming bentonite was observed at 80 g Pindiga clay + 10% Na₂CO₃.** Free swell volume increased by **64%** as Na₂CO₃ increased from 5% to 10%, most pronounced at lower clay concentrations (20–40 g range). Mechanism stated explicitly: **Ca²⁺ in the clay is substituted by Na⁺ from the ionized sodium carbonate, increasing cleavage (basal) spacing and water-adsorption capacity** — a clean, directly citable mechanistic statement paralleling the Ca-bentonite + NaOH → Na-bentonite + Ca(OH)₂ mechanism already noted in your El-Mahllawy (2013) summary.

**Beneficiation with potash (fixed 40 g/350 mL clay, dose sweep):** At **12.5% potash** (≈5 g potash per 40 g clay), dial reading at 600 rpm increased sharply **from 5 to 65** — a **1200% increase in dial reading**, giving a **750% increase in plastic viscosity and 3000% increase in yield point**. Potash gave the single best rheological improvement of any additive tested in this paper.

**Beneficiation with starch (fixed 40 g/350 mL clay, dose sweep):** Resulted in **"relatively little improvement"** in rheological properties — the paper explicitly states starch **"cannot be considered a potential beneficiating material"** for rheology specifically (though it performs much better on filtration control, see below).

**Filtration results after beneficiation (Figs. 11–12):** Na₂CO₃ produced a dramatic decrease in filtrate loss as both clay concentration and Na₂CO₃ percentage increased. At fixed 40 g/350 mL clay: **12.5% potash and starch gave 32% and 35% reductions in filtrate loss, respectively** (starch marginally better for filtration despite being weak for rheology) — and **33% and 55% reductions in mud cake thickness, respectively** (potash=33%, starch=55%, per the paper's own stated order — see the citation-integrity note above regarding Khan 2017's identical figures).

**Conclusion (author's own framing):** *"The Pindiga clay at normal concentrations does not possess any property required for use as oil well drilling mud."* However, beneficiation with Na₂CO₃, starch, and potash brought it to a state that *"satisfies API specification at optimum condition of clay and additives concentrations."* **Potash gave the best rheological improvement; starch gave the best filtration control; a combination of both is recommended** as the best beneficiating strategy — this exact three-way framing (best-rheology additive / best-filtration additive / combination recommended) is structurally almost identical to Khan (2017)'s own three-way conclusion (Xanthan gum best rheology / starch best filtration / CMC HV best combined), reinforcing the likelihood that Khan's paper drew significant structural and numerical inspiration from this one.

## Numbers worth citing directly

- Pindiga montmorillonite content: 22.19% (vs. Wyoming 35.85%); total clay fraction ~27% (Pindiga) vs. ~41% (Wyoming) — **use table values, not the paper's own transposed sentence**
- Optimum raw-clay concentration approximating Wyoming rheology: 80 g/350 mL (~4× standard reference loading)
- Raw Pindiga filtrate loss remained above Wyoming's at every concentration tested, even at 125 g/350 mL — concentration alone cannot close the filtration gap
- Na₂CO₃ 5%→10%: 64% increase in free swell volume (most pronounced at 20–40 g clay concentration)
- Potash 12.5% (40 g/350 mL clay): dial reading 5→65 (1200% increase); 750% PV increase; 3000% YP increase
- Starch: "relatively little improvement" in rheology — not recommended as a rheology-improving additive on its own
- Filtrate loss reduction at 12.5% dose: potash 32%, starch 35%
- Mud cake thickness reduction at 12.5% dose: potash 33%, starch 55% (⚠️ figures appear reproduced nearly verbatim, with an additive substituted, in Khan 2017's conclusion)

## Relevance to this thesis

- **Chapter 1 (balanced risk framing):** a genuinely poor-grade Nigerian deposit (only ~27% total clay fraction, 22% montmorillonite) still achieved API-compliant performance after simple, cheap beneficiation (Na₂CO₃ + potash + starch) — a useful "even a fairly marginal deposit can be salvaged" precedent alongside Hassan (1998)'s similar Gabal Hamdal finding.
- **Chapter 2/3 (methodological caveat-building and citation hygiene):** this is your most concrete, primary-source-verified example yet of a likely citation-integrity issue in another source in your own reference base (Khan 2017) — worth a brief explicit note in your literature review methodology section that you cross-checked derivative figures against primary sources wherever practical, and found at least one instance where a secondary source's numbers appear to trace back to this paper rather than to independent experimentation.
- **Chapter 3 (Methodology):** direct precedent for testing beneficiating agents (Na₂CO₃, potash, starch) at both a concentration sweep and fixed-concentration dose sweeps — useful as another comparator in your "three-way additive comparison" framing (rheology-best / filtration-best / combination), now confirmed as a recurring structure across at least two of your Nigerian sources.
- **Chapter 5 (Discussion):** the "concentration alone cannot close the filtration gap, even at 6× the reference loading" finding is a good, clean illustration for your own discussion of why beneficiation/activation (not just raising clay concentration) is necessary — directly reusable framing regardless of what your own Alaslaf results show.

## Caveats / limitations

1. **Two clear internal inconsistencies in the paper's own text**, both flagged above: (a) the Al₂O₃/SiO₂ ratio comparison direction (text says Pindiga is "higher," but the paper's own Table 1 data show Pindiga is lower); (b) the clay-ratio percentages for Wyoming and Pindiga appear transposed in the prose relative to Table 2. **Always cite the table values directly, not the paper's own descriptive sentences, for these two specific claims.**
2. **The 55%/33% mud-cake-thickness reduction figures appear (with an additive substituted) nearly verbatim in Khan (2017)'s own conclusion** — treat this as a likely case of Khan reusing Falode's reported results rather than independent data; cite Falode as the primary source for these numbers and be cautious using Khan's version as independent corroboration.
3. No exchangeable-cation/CEC data reported — Ca-dominance is inferred from bulk oxide chemistry (Na₂O 6.40% vs. CaO 1.30% for Pindiga) and from comparative rheological/filtration underperformance relative to Wyoming, not from a direct exchangeable-cation measurement. Same general caveat as your other bulk-oxide-based sources, though here the comparison is at least anchored to a genuine Na-bentonite reference (Wyoming, Na₂O 15.41%) rather than an isolated absolute number.
4. Simple OFAT/grid design (clay concentration alone; then clay concentration × Na₂CO₃% grid; then fixed-concentration dose sweeps for potash and starch tested separately) — no combined multi-additive DOE — another clear precedent for stating your Box-Behnken/RSM approach as a methodological improvement.
5. Sample sieved to 63 µm, described as being "to suit the API specification for bentonite" — note that the actual API 13A residue specification (per your own verified primary-source summary) targets particles **greater than 75 µm** (200 mesh, max 4.0 wt% residue), not a 63 µm target size per se; a minor imprecision in how the paper frames its own sample-prep rationale, not a significant issue but worth being precise about if you compare sieving protocols directly.
6. Different geological setting (Cretaceous marine montmorillonitic shale, Upper Benue Trough, Albian–Lower Senonian) from Alaslaf's Triassic rhyolitic-tuff origin — useful as a process/methodology comparator, not a geological analog.
