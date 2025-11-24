# UGP_EE496

Repository for the UGP (EE496) project experiments and results. This workspace contains notebooks, result CSVs, and generated HTML visualizations for experiments exploring noise and model-depth effects (Vision Transformer grid experiments).

## Contents

- `*.html` : Interactive 3D surface visualizations (noise variations).
- `accuracy-vs-depth-noise (7)_check.ipynb` : Notebook for accuracy vs depth/noise analysis.
- `ugp-plot.ipynb` : Notebook with plotting utilities and visualizations.
- `*.csv` : Experiment results and metrics (e.g., `best_per_noise.csv`, `vit_grid_results.csv`, `vit_grid_full_metrics.csv`).

## Quick start

1. Open notebooks in Jupyter or VS Code:

```cmd
python -m venv .venv
.venv\Scripts\activate
pip install jupyterlab notebook pandas numpy matplotlib plotly seaborn
jupyter lab
```

2. View HTML visualizations: open the `*.html` files in your browser (double-click or `File -> Open`).

3. Re-run notebooks to regenerate plots or update analyses.

## Notes

- This repository currently doesn't include a `requirements.txt`. If you want, I can generate one from the notebooks.
- If you need a short README section expanded (results summary, usage examples, or how experiments were run), tell me what to include and I'll update it.

## Contact

Maintainer: RahulMahato23
