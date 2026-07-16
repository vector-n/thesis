# Manoufali et al. (2016) — Evaluation of Local Bentonite for Utilization as Oil Well Drilling Mud (Ed-Damazin Sample)

**Full citation:** Manoufali, O.A.A., Ali, M.H.A., Ahmed, M.A.K., and Marghani, M.F. (2016). *Evaluation of Local Bentonite for Utilization as Oil Well Drilling Mud (Ed-Damazin Sample).* B.Sc. Dissertation, Petroleum Engineering Department, College of Petroleum Engineering and Technology, Sudan University of Science and Technology. Supervised by Eng. Fatima Ahmed Altigani. October 2016.

**Deposit/location:** Ed-Damazin area, Blue Nile State, Sudan (11°48′45.50″ N, 34°26′23.6″ E) — clay weathered from the Ethiopian highlands, sampled from an exposed quarry surface. First study of this specific locality.

**Method:** Sample prep (oven-dry 100°C, crush, grind, sieve to 75 µm per API 13A) → physical tests (Atterberg limits, particle size by sieve/hydrometer) → chemical tests (loss on ignition, moisture, XRF elemental composition, CEC by methylene blue titration) → mineralogical test (XRD) → drilling-fluid rheology and filtration testing (API-standard Fann 6-speed viscometer, gel strength, API filter press, mud balance, pH) on both non-treated and treated (Flowzan and PAC-LV, at multiple dosages) local bentonite, benchmarked against commercial bentonite treated the same way.

---

## Note on academic level / rigor relative to your other sources

This is an undergraduate (B.Sc.) dissertation, not a peer-reviewed journal article or M.Sc./Ph.D. thesis — a step down in rigor from your other benchmarking sources (Magzoub 2014/2018 are M.Sc./journal, Alshameri 2013 and Falode 2008 are journal papers). Treat its numbers as indicative/directional rather than as citation-grade as your journal sources, and note that its own literature review (Section 2.1) cites several similarly-scoped regional dissertations (Jordan, Nigeria, Iraq) that may be worth chasing if you need more African/Arab-region primary data, but aren't currently in your reference base.

## Key findings

**Chemical composition / Ca-bentonite confirmation (Section 4.2, Table 4.2):** XRF gave Al₂O₃/SiO₂ = 0.387 (stated as "typical to Wyoming bentonite," i.e., a reasonable aluminosilicate framework), but the activity ratio **{(Na₂O+K₂O)/(CaO+MgO)} = 0.11**, confirming Ed-Damazin bentonite is strongly Ca-dominant — an even more extreme Ca-skew than most of your other local-bentonite benchmarking papers report (for comparison, Magzoub 2018's purified Ca-bentonite Na/Ca by EDX was 1.97, i.e., closer to parity; this paper's combined (Na+K)/(Ca+Mg) of 0.11 indicates a much more heavily calcium-dominated clay, though note the two papers use different ratio formulas — Na/Ca alone vs. (Na+K)/(Ca+Mg) — so don't directly numerically compare without reconciling formulas, per your own Phase 1 checklist item citing Khan 2017's method for computing "Na/Ca and (Na+K)/(Ca+Mg) ratios").

Full XRF oxide breakdown (Table 4.2) is available for cross-referencing if useful: SiO₂ 46.4%, Al₂O�3 18.0%, Fe₂O₃ 12.5%, CaO 2.09%, MgO 1.91%, TiO₂ 1.80%, Na₂O only 0.32%, K₂O only 0.13% — the very low combined alkali content (Na+K ≈ 0.45% oxide) alongside the low Na/Ca math is the clearest single data point that this is a strongly non-swelling Ca-bentonite in its natural state.

**Mineralogical composition (Section 4.3, Table 4.3, XRD):** Smectite 77.19%, Kaolinite 21.51%, Illite 1.30%, no chlorite — a reasonably high smectite content (comparable to "commercial bentonites rarely contain less than 60%, usually more than 70%" benchmark cited in their own Section 2.3.1), but with a notably high kaolinite fraction (21.5%) as the main impurity, rather than the quartz/feldspar impurities more commonly reported in your other local-clay papers (e.g., Falode 2008, ElMahllawy 2013).

**Physical properties (Section 4.1, Table 4.1):** Liquid Limit 83.63%, Plastic Limit 47.8%, Plasticity Index 35.81%, clay fraction 78% (sand 3%, silt 19%, gravel 0%) — high LL/PI values consistent with montmorillonite-dominant clay and broadly in the same range as other Ca-bentonite benchmarking papers in your base (cf. Magzoub 2014's Atterberg data, if you want a direct cross-check).

**Non-treated rheology vs. commercial (Section 4.4, Table 4.4 API spec restated, Tables 4.5/4.6, Fig 4.2) — the core benchmarking result:**

| Parameter | Local bentonite (non-treated) | Commercial bentonite (non-treated) | API 13A requirement |
|---|---|---|---|
| PV (cP) | 2 | 6 | — |
| YP (lb/100ft²) | 0 | 7 | — |
| YP/PV | 0.00 | 1.17 | ≤3 (both pass) |
| Gel strength 10s/10min (lb/100ft²) | 1/1 | 4/7 | — |
| pH | 6 | (not stated, treated separately) | — |

Both non-treated samples fail to meet the practical minimum viscosity/yield needed for drilling fluid use (dial reading at 600 rpm far below the API minimum of 30 — local bentonite's untreated 600 rpm dial reading was only 4), confirming (consistent with essentially every other paper in your local_clay_benchmarking cluster) that raw, non-activated local Ca-bentonite is not usable as-is.

**Treatment trials — two different additives tested, not just soda ash:** Unlike most of your other benchmarking papers (which use Na₂CO₃ as the primary activation agent), this dissertation instead trials two viscosifying/fluid-loss polymers directly on the untreated Ca-bentonite, without first attempting Na-activation:
- **Flowzan** (a xanthan-gum-type biopolymer) at 2%, 3%, 5% — improved PV, YP, gel strength, and viscometer readings monotonically with concentration, but **filtrate volume remained >15 mL (API-failing) at all tested Flowzan concentrations**, for both local and commercial bentonite.
- **PAC-LV** (polyanionic cellulose, low viscosity) at 2–35% — dramatically more effective: at the highest tested concentration (35%), PV reached 18 cP, dial@600rpm reached 38 (vs. API min 30), **and critically, filtrate volume dropped to 0.8 mL** (vs. API max 15 mL) — the paper's headline "success" result, i.e., local Ed-Damazin bentonite meets API specifications only when treated with 35% PAC-LV.

**Important caveat on the PAC-LV result:** 35% PAC-LV (i.e., 35 wt.% relative to the 22.5 g bentonite base, per their stated API mixing procedure) is an extremely high polymer loading — far above typical field dosages for PAC-LV as a drilling-fluid additive (usually low single-digit wt.% in practice) and well outside the soda-ash-centric activation approach used elsewhere in your literature base. This paper's "success" is really a demonstration that **polymer treatment alone, without any Na-activation step, can be engineered to pass API filtration/rheology specs** — a different beneficiation strategy from the Na₂CO₃-centric approach dominant in your other sources (Hassan 1998, ElMahllawy 2013, Magzoub 2014/2018, Khan 2017, etc.). Whether 35% PAC-LV is economically or practically reasonable is not discussed by the authors — worth flagging as a limitation if you cite this "meets API spec" claim, since it's achieved through heavy polymer dosing rather than mineralogical upgrading.

**YP/PV ratio behavior is non-monotonic and sometimes goes below API requirements after treatment** (Table 4.5): e.g., local bentonite's YP/PV dropped to as low as 0.11–0.33 with PAC-LV treatment — still technically "meets" the ≤3 maximum but is far below the more stringent OCMA-type lower bounds referenced elsewhere in your base (e.g., your closed API reference thread's OCMA context); worth checking if your own thesis needs to track a YP/PV lower bound as well as upper bound, since a very low ratio indicates poor hole-cleaning/suspension capacity even if nominally "compliant."

## Numbers worth citing directly

- (Na₂O+K₂O)/(CaO+MgO) activity ratio: 0.11 → confirms Ca-bentonite
- Al₂O₃/SiO₂ ratio: 0.387 (compared favorably to Wyoming bentonite framework composition)
- Mineralogy: Smectite 77.19%, Kaolinite 21.51%, Illite 1.30%
- Atterberg limits: LL 83.63%, PL 47.8%, PI 35.81%; clay fraction 78%
- Non-treated local bentonite: PV 2 cP, YP 0 lb/100ft², dial@600rpm only 4 — API-non-compliant
- Best treatment result: 35% PAC-LV → PV 18 cP, dial@600rpm 38 (>API min 30), filtrate 0.8 mL (<API max 15 mL) — meets API 13A
- Flowzan treatment (up to 5%) never achieved API-compliant filtrate volume (remained >15 mL) despite improving rheology
- API 13A specs restated (Table 4.4, consistent with your closed reference thread): dial@600rpm min 30, YP/PV max 3, filtrate max 15.0 cm³, residue on 75 µm max 4.0 wt%

## Relevance to this thesis

- **Chapter 2 (Literature Review):** Adds a fourth Sudan/regional Ca-bentonite case study to your cluster, and is useful as a contrasting methodological example — a paper that pursued polymer-only beneficiation (Flowzan, PAC-LV) rather than the Na-activation route your own proposal and most of your other sources follow. Worth a sentence in your lit review noting that polymer-dosing and Na-activation are two distinct upgrading strategies documented in the regional literature, with your own Phase 1 protocol committing to the Na-activation route (consistent with the majority of your benchmarking cluster).
- **Chapter 3 (Methodology):** Its CEC-by-methylene-blue-titration protocol (Section 3.3.4) is a clearly documented, reproducible method you could cite or adapt if your own CEC measurement (Phase 1 checklist item) ends up using methylene blue rather than ammonium acetate or another standard method — worth comparing against whatever protocol your Faculty/external lab will actually use.
- **Chapter 5 (Discussion):** Useful cautionary data point for your own economic-feasibility section (Phase 4 checklist) — if your own Alaslaf bentonite similarly requires very high treatment-agent loading to reach API compliance, that has direct cost implications worth flagging early, exactly as this paper's 35% PAC-LV result implicitly does (though the authors themselves don't discuss cost).
- General import-substitution framing (Section 1.1, 1.3) is a close narrative parallel to your own thesis's motivation — another data point for the "many countries with untapped local Ca-bentonite import unnecessarily" argument threading through your whole local_clay_benchmarking cluster.

## Caveats / limitations

1. **B.Sc.-level rigor** — no replicate/error reporting, single-sample study (explicitly flagged as a limitation by the authors themselves in their own recommendations: "only one local bentonite sample is evaluated... we recommend to evaluate several samples"). Treat as a preliminary/exploratory data point, not a robust benchmark.
2. The authors' own conclusion recommends Na₂CO₃ activation as future work ("Ed-Damazin sample requires an activation of sodium carbonate to convert the calcium base bentonite into sodium base bentonite") — meaning **the paper's own headline "meets API spec" result (via 35% PAC-LV) is achieved without addressing the underlying Ca-dominance the authors themselves identify as the core problem.** This is worth being explicit about if you cite this paper's "success" — it's a polymer-engineering workaround, not a mineralogical upgrade, and the authors acknowledge this gap themselves.
3. No XRD basal-spacing or particle-size data reported for purification/activation effects (unlike Magzoub 2014/2018) — this paper doesn't attempt any purification step beyond simple crush/grind/sieve, so it isn't a useful methodological template for your own Phase 1 purification protocol (only for the drilling-fluid testing phase).
4. Single-deposit, first-ever study of this specific locality — no prior data to cross-check against, and no follow-up work has apparently been done (per your repo's file list, this appears to be the only paper on Ed-Damazin bentonite in your base).
5. The (Na+K)/(Ca+Mg) = 0.11 ratio isn't directly comparable to the Na/Ca-only ratios used in Magzoub 2014/2018 and reportedly in Khan 2017 — flag this if you want to build a cross-paper table of Na-activation-relevant ratios for your Chapter 2, since you'll need to either recompute a common ratio from each paper's raw elemental data or present the ratios in parallel with their differing formulas clearly labeled.
