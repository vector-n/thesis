# M.Sc. Thesis Repository — Beneficiation and Rheological Benchmarking of Alaslaf Bentonite

**Faculty of Petroleum and Natural Gas Resources, Sana'a University**
**Program:** M.Sc. in Petroleum Engineering

## What this repo is for

This is the working repository for my M.Sc. thesis on evaluating Alaslaf bentonite (Lahij Governorate, Yemen) as a substitute for imported Wyoming bentonite in water-based drilling fluids, benchmarked against API 13A/13B-1 specifications using a Response Surface Methodology (Box-Behnken) formulation design.

## How to use this repo when working with an AI assistant (Claude)

1. Start a session by pasting the contents of `references.md` and `CHECKLIST_ROADMAP.md` so the assistant has current context.
2. Upload only the specific files relevant to the current task (not the whole repo) — e.g., a specific paper, or the current chapter draft.
3. If a file is already public on GitHub, give the assistant the **raw file URL** (raw.githubusercontent.com/...) so it can fetch it directly.
4. After each session, update `references.md`, `CHECKLIST_ROADMAP.md`, and add an entry to `05_meeting_notes/log.md` — see instructions inside each file.

## Folder structure

```
thesis-alaslaf-bentonite/
├── README.md                      ← you are here
├── references.md                  ← master index of all papers, keep updated
├── CHECKLIST_ROADMAP.md           ← thesis progress tracker, keep updated
├── 00_proposal/                   ← the approved thesis proposal
├── 01_papers/                     ← all downloaded PDFs, sorted by theme
│   ├── core_deposit/              ← Alshameri 2013 and anything directly on Alaslaf
│   ├── local_clay_benchmarking/   ← Saudi/Nigeria/Egypt/Pakistan comparator studies
│   ├── methodology_RSM/           ← Box-Behnken / RSM / DOE methodology papers
│   └── yemen_geology_context/     ← Yemen soil/geology background (FAO, Zaid, Ahmed)
├── 02_chapters_drafts/            ← thesis chapters in progress (.md or .docx)
├── 03_lab_protocols/              ← step-by-step lab procedures (e.g. purification/activation)
├── 04_data_and_results/           ← raw and processed experimental data, organized by phase
│   ├── phase0_feasibility/
│   ├── phase1_characterization/
│   ├── phase2_DOE_formulations/
│   ├── phase3_rheology_filtration/
│   └── phase4_reporting/
└── 05_meeting_notes/              ← dated log of decisions and session summaries
    └── log.md
```

## Naming convention for papers

`AuthorLastName_Year_ShortTopic.pdf`

Examples: `Alshameri_2013_YemenBentoniteCharacterization.pdf`, `AlHomadhi_2007_SaudiKhulaysBentoniteSPE.pdf`

Do not upload files with default download names (e.g. `1-s2.0-S1018363918305221-main.pdf`) — rename before adding to the repo.
# thesis
