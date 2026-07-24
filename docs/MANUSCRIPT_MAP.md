# Manuscript-to-repository map

This repository preview corresponds to the current ICT Express manuscript, **Anatomy-Quality-Patient Reliability Auditing for Fundus-Based Glaucoma Screening Under External Domain Shift**.

| Manuscript element | Repository evidence | Status |
|---|---|---|
| Table 1: frozen AQPR assets | `results/main_tables/final_main_table_dataset_roles_and_frozen_component_development.csv` | Included |
| Table 2: HYGD quality-stratified AQPR | `results/main_tables/final_main_table_hygd_quality_proxy_patient_aqpr.csv` | Included |
| Table 3: expanded HYGD endpoints | `results/main_tables/final_main_table_expanded_model_claim_boundary.csv` and supporting `S17`–`S28` files | Included, except row-level held files |
| Table 4: SMDG transportability/calibration | `results/main_tables/final_main_table_smdg_source_transportability.csv` and `final_main_table_smdg_source_calibration_primary.csv` | Included |
| Figure 1: AQPR workflow | Exact manuscript source file not yet traced | Pending source/licence review |
| Figure 2: HYGD proxy overlays | HYGD-derived visual material | Withheld pending redistribution review |
| Figures 3–4: CDR proxy distributions | Aggregate evidence included; exact manuscript plots not yet traced | Pending controlled regeneration/source trace |
| Figure 5: expanded AQPR and SMDG calibration | Component plot outputs are under `results/reference_figures/` | Included as components; final combined panel pending trace |

## Interpretation boundary

The `notebooks/exploratory/` directory is retained for development transparency. Its models were not used to define, select, threshold, calibrate, or support the frozen external AQPR classifier-panel claims in the current manuscript.
