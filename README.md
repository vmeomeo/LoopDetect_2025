# LoopDetect

Directory Map:
```
LoopDetect_2025/
├─ README.md
├─ data/                     # shared, read-only inputs for all stacks
│  ├─ raw/
│  └─ interim/               # preprocessed inputs usable by all languages
├─ results/                  # only cross-language or final deliverables here
│  ├─ aggregate/             # comparisons (tables/plots) that mix languages
│  └─ reports/               # paper-ready figures, notebooks, PDFs
├─ scripts/                  # orchestration only (no language-specific logic)
│  ├─ run_all.sh
│  ├─ collect_artifacts.py   # optional: gathers per-language outputs
│  └─ smoke_checks.sh
├─ Python/
│  ├─ src/                   # helpers specific to Python evaluations
│  ├─ tests/
│  ├─ scripts/               # Python-only CLIs, notebooks
│  └─ results/               # Python-only artifacts (logs, figs, CSV)
├─ R/
│  ├─ R/                     # helpers
│  ├─ tests/testthat/
│  ├─ scripts/
│  └─ results/               # R-only artifacts
├─ MATLAB/
│  ├─ project.prj
│  ├─ tests/
│  ├─ scripts/
│  └─ results/               # MATLAB-only artifacts
└─ env/
   ├─ python.lock / conda-lock files
   ├─ renv.lock
   └─ matlab-version.txt
```
