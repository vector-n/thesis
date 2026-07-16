# API 13A (2010, 18th Ed. / ISO 13500:2009) & API 13B-1 (2024, 6th Ed. Ballot Draft) — Verified Primary-Source Benchmark Values

**Full citations:**
- API Specification 13A / ISO 13500 — *Specification for Drilling Fluids Materials.* 18th Edition, February 2010 (identical to ISO 13500:2009). American Petroleum Institute.
- API Recommended Practice 13B-1 — *Recommended Practice for Field Testing Water-based Drilling Fluids.* 6th Edition, Ballot Draft, December 2024. American Petroleum Institute. (Not yet finalized — verify current published edition before defense.)

**Purpose of this document:** resolve the filtrate-limit discrepancy between Magzoub (2014) and El-Mahllawy (2013) by checking both primary standards directly, and record the verified benchmark tables so they don't need re-extraction in a future session.

---

## The discrepancy and its resolution

Two of your secondary sources cite different API/OCMA filtrate limits for bentonite:

| Source | Cited "API" max | Cited "OCMA" max |
|---|---|---|
| Magzoub (2014) | 15 mL | 12.5 mL |
| El-Mahllawy (2013) | 13.0 mL | 16.0 mL |

**Root cause, confirmed by reading API 13A directly:** the standard defines **three separate bentonite categories**, each in its own clause/table, each with its own filtrate limit. Neither secondary source was simply "wrong" — each conflated two of these three categories:

- **Magzoub's** "API" figure (15 mL) is correct — it matches Table 8. But the number they labeled "OCMA" (12.5 mL) actually belongs to **Table 9, Non-treated bentonite** — a distinct category from Table 10's actual OCMA-grade spec.
- **El-Mahllawy's** "OCMA" figure (16.0 mL) is correct — it matches Table 10 exactly. But their "API" figure (13.0 mL) does not appear anywhere in the 2010/18th-ed. document — confirmed by full-text search of the extracted PDF text. This is very likely a transcription error or a citation from an unidentified different/older edition, not a real alternate spec in the current standard.

## Verified benchmark values (API 13A, 2010 18th Ed. / ISO 13500:2009)

### Table 8 — Bentonite (Clause 9: standard API drilling-grade bentonite)
| Requirement | Standard |
|---|---|
| Viscometer dial reading @ 600 r/min | minimum 30 |
| Yield point / plastic viscosity ratio | maximum 3 |
| **Filtrate volume** | **maximum 15.0 mL** |
| Residue > 75 µm (200 mesh) | maximum mass fraction 4.0 % |

### Table 9 — Non-treated bentonite (Clause 10)
| Requirement | Standard |
|---|---|
| Yield point / plastic viscosity ratio | maximum 1.5 |
| Dispersed plastic viscosity | minimum 10 mPa·s |
| **Dispersed filtrate volume** | **maximum 12.5 mL** |

### Table 10 — OCMA-grade bentonite (Clause 11)
Per 11.1.1: *"OCMA-grade bentonite is a montmorillonite-based clay which, by nature of its source, cannot meet all aspects of Clause 9. This bentonite may have been treated with soda ash, polymer or other chemicals to improve suspension property performance."* — i.e., OCMA-grade is explicitly the "needs-activation" category in the standard, directly relevant to your Alaslaf risk framing.

| Requirement | Standard |
|---|---|
| Viscometer dial reading @ 600 r/min | minimum 30 |
| Yield point / plastic viscosity ratio | maximum 6 |
| **Filtrate volume** | **maximum 16.0 mL** |
| Residue > 75 µm (200 mesh) | maximum mass fraction 2.5 % |

### Bonus finding — moisture spec discrepancy (not previously flagged, worth noting)
Magzoub (2014) also cites "moisture maximum 10.0 wt%" as part of the API 13A bentonite spec. **This does not appear in Table 8, 9, or 10 — bentonite has no moisture requirement in this standard at all.** A moisture spec (maximum mass fraction 16.0%) does exist, but only for **attapulgite** (Table 11/Clause 12) and **sepiolite** (Table 12/Clause 13), not bentonite. Worth a similar caveat if you cite Magzoub's "moisture ≤10.0%" figure — it doesn't check out against the primary standard for bentonite specifically.

## API 13B-1 (testing procedures) — confirmed scope

Full-text search of the 2024 6th-ed. ballot draft confirms it contains **test procedures only** (how to run the filtrate test, equipment, calculations) — **no pass/fail specification limits, no mention of OCMA, no filtrate-volume benchmark values at all.** This is expected: 13B-1 governs *how you measure*, while 13A governs *what counts as compliant*. Use 13B-1 only for your Chapter 3 test-procedure methodology (mixing, aging, HTHP/LTLP filtration protocol steps), and 13A exclusively for benchmark/spec numbers.

## Recommendation for Chapter 3

Standardize on the primary-source-verified numbers:
- **API (drilling-grade bentonite): filtrate max 15.0 mL**
- **OCMA-grade bentonite: filtrate max 16.0 mL**
- Optionally also cite **Non-treated bentonite: filtrate max 12.5 mL** as a separate, third reference category if your Alaslaf material (pre-activation) is being framed as "non-treated" rather than "OCMA-grade" — these are not interchangeable categories in the standard, so pick the one that actually matches how you're framing your material's processing state.

Don't propagate Magzoub's or El-Mahllawy's numbers as-is without this context — cite Table 8/9/10 directly from API 13A/ISO 13500 (2010/18th ed.) as your primary source, and you can footnote that two of your secondary sources state overlapping-but-distinct numbers due to the three-category structure of the standard.

## Caveats / limitations

1. The 2024 API 13B-1 is a **ballot draft, 6th edition, not yet finalized** — verify the current published edition before your defense, in case final numbers or clause numbering shift from this draft.
2. Full-text search confirms "13.0" does not appear anywhere in the 2010 API 13A document — El-Mahllawy's "API = 13.0 mL" figure could not be traced to any table in this edition; if you want to fully chase this down, it may be worth checking whether an older (pre-2010) API 13A edition or a different national/regional standard used 13.0 mL, but this is a low priority given the current edition is what you're standardizing on.
3. This document covers **bentonite-specific tables only** (Tables 8–10). API 13A also specifies attapulgite, sepiolite, CMC (technical/PAC grades), and other materials (Tables 11–18+) with their own separate filtrate/moisture/viscosity limits — not extracted here since they're not directly relevant to your bentonite-focused thesis, but flagged in case a future session needs one of those (e.g., if a CMC additive spec is needed for Chapter 3's polymer-dosing methodology).
