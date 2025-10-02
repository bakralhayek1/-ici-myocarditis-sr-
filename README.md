# ICI-Myocarditis Systematic Review (Phenotype-First, Negation-Aware)

**Goal:** PRISMA-compliant systematic review that *adds new value* via (1) standardized phenotypes (Triad, Arrhythmic/Conduction, Severe), (2) negation-aware outcome derivation (death), and (3) a Red-Flag score with adjusted models + decision curve analysis.

## Repo layout
/code/analysis/        # R scripts for models, calibration, DCA
/code/nlp/             # keyword/negation helpers (optional)
/dictionaries/         # phenotype & negation lists (CSV)
/manuscript/           # abstract.md, methods, results, discussion, captions

*Data, PDFs, figures, and tables live in **Google Drive** (not in git).*

## Connectors
Google Drive (data & outputs), GitHub (this repo), Notion (optional screening DB), Gmail/Calendar (optional).

## How to run
1) Use ChatGPT with connectors to collect/screen studies and populate a Google Sheet extraction grid.
2) Export analysis-ready CSVs to Drive.
3) Run the R scripts in `/code/analysis/` locally or in your preferred environment.

## Data policy
No PHI. Cite all sources. Keep large PDFs/supplements in Drive only.

.gitignore
.DS_Store
.env*
__pycache__/
*.py[cod]
.ipynb_checkpoints/
.Rhistory
.Rproj.user/
.RData
.Ruserdata
build/
dist/
# Keep data & outputs out of git (use Drive)
data/
outputs/
pdfs/


