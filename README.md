# Black Hole Evolution — ML Forecasting (IllustrisTNG)

This repository contains a reproducible pipeline to forecast galaxy and black hole properties using sequence models (LSTM) on IllustrisTNG data.

- **Configs**: in `configs/` (features, data, hyperparams, plotting)
- **Notebooks**: run in order from `notebooks/00_project_overview.ipynb` → preprocessing → model training → post-analysis
- **Outputs**: figures in `results/figures/`, tables in `results/tables/`
- **Reproducibility**: train-only standardization, unique subhalo splits, seeds fixed
- **Plots**: consistent fonts, human-readable labels (e.g. *Star Formation Rate* instead of `sfr`)
