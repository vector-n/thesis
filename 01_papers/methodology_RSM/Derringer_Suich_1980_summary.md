# Derringer & Suich (1980) — Simultaneous Optimization of Several Response Variables

**Full citation:** Derringer, G., Suich, R. (1980). "Simultaneous Optimization of Several Response Variables." *Journal of Quality Technology*, 12(4), 214–219. DOI: 10.1080/00224065.1980.11980968. Authors affiliated with Battelle Columbus Laboratories (Derringer) and California State University, Fullerton (Suich).

**Type of paper:** Methodological/statistical — the foundational paper introducing the desirability-function approach still used today (this paper has 240+ citing articles per the journal listing, and is essentially the origin of the "desirability function" now built into Minitab's Response Optimizer, which your roadmap already names as your planned RSM software).

**Core problem addressed:** How to optimize several response variables (Y's) simultaneously, when they depend on the same set of independent variables (X's), and the X-levels that maximize one Y may not come close to maximizing another. Prior approaches (linear programming à la Hartmann & Beaumont 1968, Nicholson & Pullen 1969) optimized one response subject to constraints on the others — a philosophy the authors argue is often wrong, since the real goal is usually the *best balance* across several responses rated as equally important, not maximizing one at the expense of the rest.

---

## The method (this is the part directly reusable in your Chapter 3)

**Step 1 — Fit each response separately.** Each response variable $Y_i$ is related to independent variables $X_1, \ldots, X_p$ via an unknown function $f_i$, approximated in practice by a polynomial (typically second-order) fitted by regression: $\hat{Y}_i = b_0 + \sum b_L x_L + \sum\sum b_{Lm}x_L x_m$. This is exactly the same second-degree RSM polynomial form your thesis will use for PV, YP, AV, gel strength, and fluid loss.

**Step 2 — Transform each fitted response into a "desirability" $d_i \in [0,1]$.** Two transformation types:

- **One-sided transformation** (used when $Y_i$ is to be simply maximized or minimized): controlled by a minimum acceptable value $Y_{i*}$, a value $Y_i^*$ above which further improvement adds negligible value, and a shape exponent $r$. $d_i = 0$ below $Y_{i*}$, rises smoothly (linearly if $r=1$, slowly-then-fast if $r$ large, fast-then-slow if $r$ small) between $Y_{i*}$ and $Y_i^*$, and $d_i = 1$ above $Y_i^*$.
- **Two-sided transformation** (used when $Y_i$ has both a minimum and maximum acceptable bound, e.g. a target range): controlled by $Y_{i*}$ (min), $Y_i^*$ (max), a most-desirable interior target value $c_i$ (need not be the midpoint), and two shape exponents $s$ and $t$ governing how quickly desirability falls off on each side of $c_i$. $d_i=0$ outside $[Y_{i*}, Y_i^*]$, rises to 1 at $c_i$.

**Step 3 — Combine into a single composite desirability via the geometric mean:**
$$D = (d_1 \times d_2 \times \cdots \times d_k)^{1/k}$$
The geometric mean (not arithmetic mean) is used deliberately: if **any single** $d_i = 0$ (i.e., any one response is unacceptable), then $D = 0$ regardless of how good the other responses are — this is the key property that makes the composite desirability behave like a genuine "all constraints must be simultaneously satisfied" criterion rather than an averaging-out of one bad response against several good ones.

**Step 4 — Maximize D over the X-domain.** Since $D$ is a continuous function of the X's (via the chain of continuous transformations), standard univariate/multivariate search techniques (the paper uses a Hooke & Jeeves 1962 pattern-search algorithm) can maximize $D$ directly — this is what Minitab's Response Optimizer does today, described by the paper's authors as reducing a multivariate optimization problem to a single univariate one. An added benefit: $D$ can be plotted as a contour surface against pairs of independent variables (holding others at their optimum) to visually assess how flat/sensitive the optimum is.

## Worked example (tire tread compound) — useful as a template for your own worked example

- **Design:** 3-variable rotatable central composite design, 6 center points, 20 runs total (Table 1 in paper) — three independent variables: hydrated silica level ($X_1$), silane coupling agent level ($X_2$), sulfur level ($X_3$), each coded to $-1.633/-1/0/+1/+1.633$ (i.e. a standard CCD with axial/star points, not a Box-Behnken design — worth noting for your methodology section since your thesis specifically uses Box-Behnken, a related but distinct RSM design that omits axial points and uses only edge-midpoints + center-point replicates).
- **Four response variables**, two treated one-sided and two treated two-sided:
  - $Y_1$ = PICO Abrasion Index — one-sided, maximize; $Y_{1*}=120$, $Y_1^*=170$, $r=1$ (linear)
  - $Y_2$ = 200% Modulus — one-sided, maximize; $Y_{2*}=1000$, $Y_2^*=1300$, $r=1$
  - $Y_3$ = Elongation at Break — two-sided; $Y_{3*}=400$, $Y_3^*=600$, target $c_3=500$ (midpoint), $s=t=1$ (linear)
  - $Y_4$ = Hardness — two-sided; $Y_{4*}=60$, $Y_4^*=75$, target $c_4=67.5$ (midpoint), $s=t=1$
- Each $\hat{Y}_i$ fitted to a full second-degree polynomial (Table 2 gives all $b_0, b_1, b_2, b_3, b_{11}, b_{22}, b_{33}, b_{12}, b_{13}, b_{23}$ coefficients plus standard error for each of the 4 responses) — a clean, directly reusable template for how to present your own RSM coefficient tables in Chapter 4.
- **Result:** optimum found at $X_1=-0.050$, $X_2=0.145$, $X_3=-0.868$ (coded units), giving predicted $Y_1=129.5$ ($d_1=0.189$), $Y_2=1300$ ($d_2=1.000$), $Y_3=465.7$ ($d_3=0.656$), $Y_4=68.0$ ($d_4=0.932$), and **maximum composite desirability $\hat{D}=0.583$**.
- **Interpretation given by the authors:** $D=0.583$ has no meaningful numeric interpretation on its own — its only role is to locate the X-levels where the joint desirability is maximized. The authors also examine contour plots of $D$ against each pair of X's (Figs. 5–7) and note the desirability surface is "relatively flat" near the optimum, meaning small deviations in formulation don't appreciably hurt the outcome — a useful robustness argument they use to justify small production-driven adjustments away from the exact numerical optimum.

## Relation to prior desirability formulations (useful for a methods-history paragraph)

- Harrington (1965) originated the desirability function concept, using an exponential form $d_i = \exp(-\exp(-Y_i))$ (one-sided) and $d_i=\exp(-|Y_i|^s)$ (two-sided).
- Gatza & McMillan (1972) modified Harrington's form to allow negative $d_i$ values for unacceptable properties.
- **Derringer & Suich's contribution is a generalization**: rather than restricting to specific exponential-family forms, their piecewise power-function transformations (Eqs. 2–3) let the user set the most-desirable value $c_i$ anywhere between the bounds (not necessarily the midpoint) and independently control the desirability's rate of increase/decrease on each side via $r$ (one-sided) or $s,t$ (two-sided) — Harrington's and Gatza & McMillan's functions can be closely approximated as special cases of this more flexible framework. This generalized form is what became the standard "Derringer desirability function" now implemented in essentially all commercial DOE software including Minitab.

## Numbers/definitions worth citing directly

- Composite desirability formula: $D = (d_1 \times d_2 \times \cdots \times d_k)^{1/k}$ (geometric mean of individual desirabilities)
- Property that makes this formulation attractive: any single $d_i=0 \Rightarrow D=0$ (an unacceptable single response makes the whole formulation unacceptable, regardless of how good the others are) — this is the standard citable justification for using geometric rather than arithmetic mean
- One-sided transformation exponent $r$: large $r$ → desirability increases slowly above the minimum-acceptable value (only near-maximal $Y_i$ is truly desirable); small $r$ → any value above the minimum is nearly as good as any other
- Two-sided transformation exponents $s,t$: control desirability falloff rate on each side of the interior target $c_i$, which itself may be set anywhere between the lower and upper bounds, not necessarily the midpoint
- Worked example achieved $\hat{D}=0.583$ using linear ($r=s=t=1$) desirability transformations throughout — the authors' own choice of linear transformations (their simplest case) for all four responses is a reasonable default to cite if you don't have strong prior reasons to weight any particular response's extremes more heavily than others

## Relevance to this thesis

- **Chapter 3 (Methodology) — this is your core RSM optimization-criterion citation.** Your roadmap specifies using "Minitab Response Optimizer + independent Python cross-check" to jointly optimize PV, YP, AV, gel strength, and fluid loss against API targets — Minitab's Response Optimizer implements exactly this Derringer & Suich composite desirability approach. This paper is the primary, original source to cite when you describe your multi-response optimization criterion, rather than citing Minitab's documentation alone.
- **Chapter 3 — response-type mapping for your own five responses:** you will likely want one-sided desirability transformations (minimize) for fluid loss (lower is better, no real upper "too good" bound) and PV (generally lower preferred, within reason), and two-sided transformations (target-is-best) for YP and gel strength (both have API-specified acceptable ranges, not simply "more is better" — excessive YP or gel strength causes its own problems like poor hole cleaning/high pump pressure). This paper gives you the exact mathematical framework and terminology ($Y_{i*}$, $Y_i^*$, $c_i$, $r$/$s$/$t$) to specify and justify those choices explicitly in your methodology chapter.
- **Chapter 3 — design-type distinction:** note for your own methods section that this paper's worked example uses a **central composite design (CCD)** with axial/star points, not the **Box-Behnken design (BBD)** your thesis uses. Both are common second-order RSM designs, but BBD avoids extreme corner/axial combinations (useful when those combinations are impractical or expensive to run, which is often the case for clay/additive formulations) — worth a brief methodological note explaining why you chose BBD over CCD despite this foundational paper's example using CCD.
- **Chapter 4/5 (Results/Discussion):** the "flat near the optimum" robustness argument (contour plots showing small X-deviations don't appreciably reduce D) is directly reusable framing if your own optimum region shows similar flatness — useful for justifying any small formulation adjustments you make for practical/economic reasons (e.g., rounding a Na₂CO₃ dosage to a more convenient number).

## Caveats / limitations

1. This is a 1980 methods paper with a single illustrative example (rubber/tire tread compound) — it establishes the general mathematical framework but gives no drilling-fluid-specific guidance. You'll need your Alhajabdalla (2021), Asmungi (2021), Ossai (2025), and Satiyawira (2025) papers (still pending summary) to see how this framework has actually been applied to drilling-fluid RSM optimization specifically.
2. The paper's own example uses **linear desirability transformations throughout** ($r=s=t=1$) for simplicity — it does not provide worked guidance on how to *choose* non-linear exponents for a real application; that choice is left to user judgment/experience, so you'll need to justify your own exponent choices (or default to linear, following the authors' own precedent, if you have no strong basis for something more elaborate).
3. No discussion of how many responses is "too many" to combine via geometric mean, or how to handle correlated responses (e.g., PV, YP, and AV are mathematically related through the same viscometer readings) — a limitation worth flagging in your own methodology if you optimize responses that aren't fully independent.
4. Optimization here is a numerical search (Hooke-Jeeves pattern search or equivalent) over the fitted polynomial surface — the quality of the optimum found is entirely contingent on the quality of the underlying regression fit (same general caveat about needing an "adequate" second-degree polynomial fit that's already implicit in your own RSM/Box-Behnken planning).
