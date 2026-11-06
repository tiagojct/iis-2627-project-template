# Rules for an AI agent in this repository

Read this file before you change anything.

## Where you work

- Work on a new branch. Never commit to `main`.
- Do one task for each branch. Keep the change small.
- Do not push, merge or delete a branch. The human does that after reading the diff.

## What you must not do

- Do not change or delete files in `data/raw/`. They stay as received.
- Do not write passwords, tokens or keys in any file. Do not read `.Renviron`.
- Do not send any data from this repository to a web service, except what the human tells you to send.
- Do not install packages without telling the human which and why.

## How you work

- Say what you will change before you change it.
- Use `here::here()` for file paths. Do not use `setwd()` or absolute paths.
- Run the changed script or render `report.qmd` before you say that the task is done. Tell the human if it fails.
- Write a commit message that says what changed and why.
- Do not invent references. Cite only items that are in `references.bib`.

## After your work

- List the files that you changed.
- Tell the human what to check in the diff.
- The human records your work in `ai-declaration.md`.
