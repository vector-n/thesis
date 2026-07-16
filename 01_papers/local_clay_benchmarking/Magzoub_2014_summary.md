# Magzoub (2014) — Development of Stable Bentonite for Drilling Fluid Formulations Using Local Sources

**Full citation:** Magzoub Elhag, M.I. (2014). *Development of Stable Bentonite for Drilling Fluid Formulations Using Local Sources.* M.Sc. Thesis, Petroleum Engineering, King Fahd University of Petroleum & Minerals (KFUPM), Dhahran, Saudi Arabia. Date of degree: November 2014. Advisor: Dr. Mohamed A. Mahmoud; Co-Advisor: Dr. Mustafa Saleh Nasser; Committee: Dr. Ibnelwaleed Ali Hussein, Dr. Abdullah Saad Sultan, Dr. Abdulazeez Abdulraheem.

**Deposit/location:** Khulays Area, North Jeddah, Saudi Arabia (~95 km north of Jeddah — the only known bentonite outcrop in the Kingdom).

**Method:** Full characterization (XRD, XRF, SEM/EDS, particle size, zeta potential) of raw local Ca-bentonite → purification (multiple methods compared: dry sieving, wet sieving, sedimentation, combined) → Na-activation via soda ash (Na₂CO₃) dosing → **novel combined heating + stirring activation method** developed by the author → drilling-fluid formulation and benchmarking (Fann 35 viscometer, API + HPHT filtration, mud balance density/pH) against standard commercial (Wyoming-type) bentonite and API 13A / OCMA specifications.

---

## Why this is your closest structural template

This is the single most directly analogous prior work to your own thesis: same regional context (untapped Arabian Peninsula Ca-bentonite deposit, no local drilling-grade supply, 100% import-dependent industry), same overall workflow (characterize → purify → Na-activate → benchmark against API), and it explicitly frames the same "local bentonite is Ca-type and needs Na-activation" narrative your proposal's risk flag anticipates for Alaslaf. Recommend using its chapter structure (Introduction → Literature Review → Objectives/Problem Statement → Methodology → Results → Conclusions) as a working skeleton for your own Chapters 1–5, adapted for your RSM/Box-Behnken design (Magzoub used simple one-factor-at-a-time dosing, not DOE — this is your key methodological improvement over his approach, worth stating explicitly in your Chapter 3 as a novelty claim).

## Key findings

**Problem framing (Ch. 1/3):** Saudi Arabia's drilling operations consume >100,000 tons/year of bentonite, all imported — direct structural parallel to your import-substitution argument for Yemen (useful for your Section 8 / economic feasibility framing).

**Chemical/mineralogical characterization — the Na/Ca ratio result (Table 13, Section 5.2–5.3):**
This is the paper's single most load-bearing number for your thesis. Using SEM-EDS elemental analysis:

| Sample | Na (wt%) | Ca (wt%) | Na/Ca ratio | Note |
|---|---|---|---|---|
| Standard (commercial) bentonite | 1.39 | 0.48 | **2.90** | Reference "drilling grade" benchmark |
| Raw Khulays (bent-1/bent-2, various purification batches) | 1.73–1.79 | 0.89–0.98 | **1.77–2.04** (raw), text also cites 1.97/1.78 for bent-1/bent-2 elsewhere | Below the ~2.9 commercial benchmark |

Author's conclusion: **purification alone cannot raise the Na/Ca ratio significantly**, because purification only removes non-clay impurities and doesn't change the sodium/calcium content intrinsic to the clay's exchange sites — the clay is proven to be genuinely Ca-dominant and requires a targeted Na-exchange/activation step, not just physical beneficiation. **This is directly transferable methodological logic for your Phase 1 go/no-go decision** — it validates that Na/Ca ratio must be measured on purified material specifically to decide on activation, and that beneficiation and activation are separate, non-substitutable steps.

Bulk elemental composition (SEM-EDS, wt%) of Khulays bentonite was otherwise very close to standard commercial bentonite: O 55.4–57.6%, Si ~24–28.9%, Al 6.8–9.6%, Mg 0.9–1.55%, K 0.19–0.48% — i.e., the aluminosilicate framework itself is comparable to commercial-grade material; the deficiency is specifically in exchangeable Na vs Ca. Notably, raw Khulays bentonite also showed elevated manganese (0.7–0.9 wt%, essentially absent in standard bentonite) — author notes Mn can favorably improve gel strength.

**Purification methods compared (Section 5.1):** dry sieving, wet sieving (200 mesh / 75 µm), sedimentation, and combinations thereof. **Wet sieving after dispersion + sedimentation gave the purest bentonite** (~100% clay fraction by hydrometer analysis) vs. dry sieving (~35% clay fraction only) — a concrete methodological recommendation directly applicable to your own Phase 1 purification protocol design.

**Na-activation via soda ash (Section 5.3.1–5.3.2):** Doses tested: 0, 0.5, 1.5, 2.5, 3, 4, 5, 7 g soda ash (on a 22.5 g bentonite / 350 mL slurry basis, i.e., ~6 wt% bentonite concentration). Apparent and plastic viscosity increased with soda ash addition, **peaking around 3 g** dose (~13 wt% relative to clay mass) before declining — i.e., there is an optimum soda ash dose beyond which further addition doesn't help (classic response-surface-shaped behavior — useful supporting precedent for your Box-Behnken design choice, since Magzoub's one-factor sweep already hints at a non-monotonic/curvature response that a full RSM would resolve more rigorously).

**Novel combined heating + stirring activation (Section 5.3.3) — the thesis's key original contribution:** Standard soda-ash-only activation was insufficient (max viscosity achieved ~12 cP, still below the API-required minimum of 15 cP dial reading at 600 rpm). The author introduced a combined heating-while-stirring treatment, which:
- Raised achievable apparent viscosity to 18–20 cP (vs. 6–12 cP for soda-ash-only activation, vs. 1–4 cP for untreated Ca-bentonite)
- Increased average particle size dramatically: from 2.4 µm (untreated) to 1286.9 µm — used as an indicator of successful swelling/activation
- Required a minimum of **3 hours** heating/stirring time to reach maximum viscosity (tested 1, 3, 6, 12, 24 hr)
- Reduced filtration loss to 28 mL (65% reduction vs. untreated) — **but this still exceeds the API 13A maximum of 15 cm³/30min**, i.e., filtration control was improved but not brought fully within spec even after best treatment

**API/OCMA reference specifications used for benchmarking (Tables 1–2, directly reusable in your Chapter 3):**
- API 13A: dial reading @600rpm minimum 30; YP/PV ratio maximum 3; filtration maximum 15 cm³/30min; residue on 200 mesh (75 µm) maximum 4.0 wt%; moisture maximum 10.0 wt%
- OCMA non-treated bentonite: YP/PV ratio maximum 1.5; plastic viscosity maximum 10 cP; filtrate volume maximum 12.5 cm³

**Final rheology summary (Table 30 — clean before/after comparison, very citable as-is):**

| Sample | Apparent Viscosity (cP) | Plastic Viscosity (cP) | Yield Point (lb/100ft²) |
|---|---|---|---|
| Ca-bentonite, not activated | 1–4 | 1–2 | 4–16 (table shows "41642", likely an OCR/typo artifact for a range like 4–16 or 4–42 — verify against original PDF table if citing this exact figure) |
| Soda-ash only (no heat/stir) | 6–12 | 2–6 | 3–12 |
| Hot/stirring activated | 18–20 | 3–6 | 12–32 |
| Full drilling mud formulation (1-B, hot/stirring-treated) | 30 | 10 | 40 |

**Drilling fluid formulation benchmark (Section 5.7, Table 20–25):** Two full mud formulations tested (bentonite + soda ash + caustic soda + xanthan gum + CaCO₃, with a second KCl/starch-extended formula). At 20 g bentonite/350 mL (~5.7 wt%): standard bentonite mud gave PV=20 cP, YP=25 lb/100ft², filtrate=9 mL; the treated local bentonite (bent-2) gave PV=10 cP, YP=40 cP (higher, favorable), but **filtrate=30 mL — more than 3× the standard mud's filtrate and 2× the API 15 mL maximum.** This is the paper's clearest illustration of a partial-success outcome: rheology can be brought up to or even above commercial-bentonite performance, but filtration control remains the harder-to-solve deficiency — a very useful "manage expectations" data point for your own Chapter 5 discussion/quantify-the-shortfall framing (parallel to how you're already using Akinwumi 2015 for a similar honest-gap narrative).

## Numbers worth citing directly

- Standard bentonite Na/Ca ratio (SEM-EDS): 2.90
- Raw Khulays bentonite Na/Ca ratio: 1.77–2.04 (varies by batch/purification method)
- Optimum soda ash dose: ~3 g per 22.5 g bentonite (~13 wt% relative to clay) at 6 wt% mud concentration
- Minimum effective heating/stirring activation time: 3 hours
- Particle size growth on activation: 2.4 µm → 1286.9 µm
- Best achieved filtration after full treatment: 28 mL (vs. API max 15 mL — not fully compliant)
- API 13A benchmark values: dial@600≥30, YP/PV≤3, filtrate≤15 cm³, residue≤4.0 wt%, moisture≤10.0 wt%
- OCMA benchmark: YP/PV≤1.5, PV≤10 cP, filtrate≤12.5 cm³

## Relevance to this thesis

- **Chapter 1:** strong structural/narrative template — same "huge import-dependent industry, local Ca-bentonite deposit, needs Na-activation" framing you can adapt for Yemen; also a good citation for the general "why Na-activation matters" argument (Foster 1953 is cited within this thesis for the Na/Ca-affects-properties claim — worth chasing that citation separately if you want the primary source).
- **Chapter 2 (Literature Review):** its own Section 2.2 (Bentonite in Drilling Fluids, Beneficiation, Activation) is a ready-made mini literature review you can cross-check your reference list against — it cites Al-Homadhi (2007, already in your base), a Turkish bentonite activation study (soda + MgO, likely Karaguzel 2010, already in your base), and Al-Qunaibit et al. (2005, Jeddah bentonite, Cu²⁺ sorption — not directly relevant to drilling but same deposit region, worth noting).
- **Chapter 3 (Methodology):** direct template for purification method comparison design, soda-ash dosing sweep methodology, and rheological/filtration test procedures (Fann 35 protocol, API/HPHT filtration protocol) — useful even though your own design will be RSM/Box-Behnken rather than OFAT.
- **Chapter 5 (Discussion):** the filtration-shortfall finding (rheology meets spec, filtration doesn't) is a valuable precedent for framing partial success honestly, and for anticipating that your own Alaslaf bentonite may show a similar asymmetric outcome.

## Caveats / limitations

1. **Methodologically pre-RSM**: all activation dosing is one-factor-at-a-time (OFAT), not designed experiments — this is exactly the gap your Box-Behnken/RSM approach improves on; make this contrast explicit in your Chapter 3 novelty statement.
2. The Yield Point value "41642" for the "not activated" row in Table 30 is almost certainly a text-extraction/OCR artifact from the original PDF table (columns likely merged) — **do not cite this number as-is**; verify against the original PDF table layout or treat the range as unknown/needs re-extraction before use.
3. Even the best-performing treated local bentonite did not fully meet the API 15 mL filtration maximum (achieved 28 mL) — don't overstate the "success" of the thermal-chemical method; it's a partial win, primarily on rheology, not on filtration control.
4. This is a single-deposit, single-country case study — useful as a structural and methodological analogue, not as a numerical prediction for what Alaslaf bentonite will do (different geological setting, different parent rock — Khulays vs. Alaslaf's Triassic rhyolitic tuff origin per Alshameri 2013).
5. Uses commercial/OCMA and API 13A specs consistently, matching your own benchmarking approach — good consistency check but confirm you're citing the same (current) edition of API 13A that this 2014 thesis used, since your own references.md flags the 2010 18th ed. as the version you're working from.
