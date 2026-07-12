# How to merge this into your existing repo

This package adds a new subfolder, `01_papers/api_standards/`, which wasn't in the
original structure — I created it because these two documents are foundational
standards, not comparator studies, so they deserve their own category rather than
being squeezed into `local_clay_benchmarking/` or `methodology_RSM/`.

## Steps

1. Unzip this package.
2. Copy the folder `01_papers/api_standards/` into your repo at the same path
   (`thesis-alaslaf-bentonite/01_papers/api_standards/`).
3. Replace your existing `references.md` with the updated one included here
   (or manually merge the new rows — see diff notes below).
4. Update `README.md`'s folder-structure diagram to add the new subfolder line
   (also included here, already updated).
5. Commit and push.

## What changed in references.md

- Added a new section: **"API Standards (foundational)"** with two rows:
  - `API_2010_13A_SpecificationDrillingFluidsMaterials.pdf`
  - `API_2024_13B1_TestingWaterBasedDrillingFluids_6thEdBallotDraft.pdf`
- Removed these two items from the "Papers still needed" gap list, since they're
  now in hand.
- Marked both 🟢 (verified — titles and editions confirmed directly from the PDFs).

## Note on the 13B-1 document

The file you provided is labeled "SIXTH EDITION, Ballot Draft" — this means it is
a **draft under balloting**, not yet a finalized published edition. Worth flagging:
when you cite this in your thesis, either (a) note it's a draft/ballot version and
check API's site for the final published 6th edition before your defense, or
(b) if the final version isn't out yet, cite the currently-in-force edition
(5th edition, or whichever is officially active) alongside this draft, and note
the draft as a forthcoming revision. I'd recommend checking api.org directly
closer to your defense date to confirm which edition is authoritative at that time.
