# Codecheck

A codecheck tests that someone else can run the project and get the results in the report. The checker is the other pair. The checker works in a clean copy and does not ask the authors for help.

## For the authors

Keep `README.md` up to date. A reader must know three things from it: which packages to install, which scripts to run and in which order, and which file is the result. If a step is missing, the check fails. That is a finding, not a failure of the checker.

## For the checker

1. Clone the repository of the other pair to a new folder. Do not use a folder that you used before.
2. Open `iis-project.Rproj`. Follow `README.md` and nothing else.
3. Run the scripts in the order of the README. Render `report.qmd`.
4. Compare the numbers, the table and the figures of your render with the report that the authors committed.
5. Open an issue in their repository with the template "Codecheck". Write what you did, what worked, what did not, and the exact error messages.

## Record

| Item | Result |
|---|---|
| Checker (pair) | |
| Date | |
| R and Quarto versions | |
| Packages installed with no help | yes / no |
| Scripts run with no error | yes / no |
| Report renders | yes / no |
| Numbers and figures agree with the report | yes / no / partly |
| Link to the issue | |
