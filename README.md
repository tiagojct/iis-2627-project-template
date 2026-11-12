# [Title of the project]

Pair: [Name 1], [Name 2] (a group of three adds [Name 3]). Topic: [topic]. IIS 2026/27, MEDS, FMUP.

All data are synthetic. They describe no real person.

## Files

| File or folder | What it is |
|---|---|
| `iis-project.Rproj` | The RStudio project. Open it with a double-click |
| `data/raw/` | The pair dataset and its dictionary. Never change these files |
| `data/processed/` | Clean tables. The scripts write them. Git ignores them |
| `scripts/` | The R scripts. Their names start with a number: run them in that order |
| `figures/` | Figures that the scripts save. Git ignores them |
| `dictionary.csv` | Dictionary of the variables that the pair creates or collects |
| `code-list.csv` | The code list of the case definition (session 4) |
| `report.qmd` | The report. Render it to HTML and Word |
| `presentation.qmd` | The slides of the presentation |
| `references.bib`, `vancouver.csl` | References and citation style |
| `questionnaire/` | The LimeSurvey form of session 4 (`.lss`) and its export |
| `ai-declaration.md` | Use of AI in the project |
| `AGENTS.md` | Rules for an AI agent in this repository |
| `opencode.json` | Permission rules for OpenCode: it asks before each edit and each command, and it cannot push |
| `CODECHECK.md` | How another pair tests this project |

## How to run

1. Install the R packages: [list the packages].
2. Open `iis-project.Rproj` in RStudio.
3. Run the scripts in `scripts/` in the order of their numbers: [list the scripts].
4. Render `report.qmd`. The result is `report.html` and `report.docx`.

Write the steps so that someone who did not work on the project can follow them.

## Expected results

Git ignores the rendered report. The checker compares the render with this section. Keep it up to date.

- Number of patients in the analysis: [number]
- Main result: [one sentence with the number that answers the question]
- Table: [name or caption of the table in the report]
- Figures: [name or caption of each figure in the report]

## Licence

[Write your choice: licence of the code, licence of the text.]
