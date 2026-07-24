# AQPR Glaucoma

Public reproducibility repository for **Anatomy-Quality-Patient Reliability Auditing for Fundus-Based Glaucoma Screening Under External Domain Shift**.

AQPR is a post-hoc audit workflow for frozen fundus-based glaucoma classifiers. The repository is organized around Google Colab notebooks and derived audit outputs rather than a production software stack.

## Public notebook scope

The required article-reproduction sequence is:

`01 -> 02 -> 03 -> 04 -> 05 -> 06 -> 07 -> 08 -> 09 -> 12 -> 13 -> 14 -> 15 -> 16`

Notebooks 10 and 11 are retained under `notebooks/exploratory/` for research transparency. They contain HYGD-based exploratory anatomy-constrained and hybrid model-development experiments. They are **not** part of the final article protocol and were not used to select, threshold, calibrate, or define the frozen classifier panel reported in the manuscript.

Notebook 00 is an internal legacy setup audit and is intentionally excluded.

## Reproduction levels

- **Results-level reproduction:** use the distributed aggregate tables and figure data to inspect the numerical evidence without retraining.
- **Notebook-level reproduction:** configure dataset paths and execute the relevant Colab notebooks.
- **Full training reproduction:** requires the original public datasets, GPU resources, and any redistributable model assets.

## Paths

Set two environment variables before execution:

- `AQPR_PROJECT_ROOT`: working root containing `project_data/`, `models/`, and `results/`.
- `AQPR_DATA_ROOT`: external dataset root.

See `configs/paths.example.env`.

## Data and model availability

Raw datasets, trained checkpoints, HYGD-derived proxy masks, and derived fundus images are not committed automatically. Redistribution is conditional on the licenses and access terms of the original datasets. Aggregate audit tables and plot-only reference outputs are prioritized for GitHub.

## Curation status

The public notebook copies have been mechanically curated: local path definitions are configurable, stored outputs and execution counters are removed, and explanatory headers are added. They were not re-executed after curation. Original SHA-256 hashes and source-to-public mappings are recorded in `docs/FILE_MAP.csv`.
