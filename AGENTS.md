# Agent Instructions

## Project

SA Road Crash Intelligence

This repository is a professional data, GIS and analytics portfolio project.

## Working Principles

- Read the relevant project documentation before making significant changes.
- Do not modify source files inside `data/raw/`.
- Store transformed or cleaned datasets inside `data/processed/`.
- Prefer reproducible workflows over undocumented manual changes.
- Verify results before treating them as correct.
- Do not fabricate missing data, assumptions or findings.
- Document important analytical or technical decisions in `docs/DECISIONS.md`.
- Update `docs/DATA_DICTIONARY.md` when important source or derived fields are introduced.
- Update `docs/WORKFLOW.md` when the project workflow materially changes.
- Keep documentation concise and useful rather than documenting trivial actions.

## Validation Principles

As relevant to the task, verify:

- row counts
- NULL or missing values
- duplicates
- field types
- joins
- CRS
- geometry validity
- unexpected data loss
- analytical assumptions
- unexpected results

## Git

- This repository belongs to the user's personal portfolio.
- Use the repository-local personal Git identity.
- Do not change the user's global Git configuration.
- Commit meaningful verified milestones rather than every trivial edit.
