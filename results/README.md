# Results

This directory contains a curated subset of derived outputs. It does not contain raw datasets, preprocessed fundus images, HYGD proxy masks, or trained checkpoints.

- `main_tables/`: compact tables directly supporting the manuscript or its minor-revision safeguards.
- `supplementary/`: aggregate calibration, robustness, perturbation, quality, and source-wise evidence.
- `reference_figures/`: plot-only outputs from the final v3.6 paper package. These do not include the manuscript's HYGD example-image panels.
- `exploratory/`: compact configurations and aggregate results for the anatomy-constrained and hybrid development branches.

Files requiring row-level identifier sanitization, absolute-path removal, or dataset-license review remain excluded. See `docs/HELD_ARTIFACTS.csv`. Internal reviewer-response, handoff, manuscript-fragment, and duplicate LaTeX files are listed in `docs/OMITTED_ARTIFACTS.csv`.

`final_v36_table_matched_random_robustness_compact.csv` was not copied because the packaged source is empty. The underlying matched-random evidence remains available in the non-empty supplementary tables.
