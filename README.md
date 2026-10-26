# Birth Weight Prediction Using Linear Regression

Compares maternal weight, gestation, and smoking status using linear regression; includes Cook’s distance and residual diagnostics.

Original results: maternal-weight R² ≈ 0.024; gestation R² ≈ 0.166; gestation plus smoking R² ≈ 0.226 after excluding two influential cases as a sensitivity analysis.

## Run

Requires Python 3 and the original dataset.

```sh
python -m venv .venv
source .venv/bin/activate
python -m pip install -r requirements.txt
python -m jupyter lab
```

Place `babies_data.csv` in `data/`, then open `birth_weight_analysis.ipynb` and run cells in order from the repository root. Dependencies are unpinned; saved results reflect the original environment, and numerical details may vary by version.

## Scope and provenance

Adapted from the author’s original birth-weight analysis notebook. Original modelling steps, statistical summaries, figures, and interpretations are preserved; added headings explain the workflow and limitations. Machine paths, installation logs, raw-row saved previews, empty cells were removed.

Influential-case exclusions are exploratory; associations do not establish causality. No held-out evaluation or clinical validation was performed.

## Data and rights

Datasets are not included: no redistribution license was found alongside the local data files. Obtain data from an authorized source. Saved derived statistical outputs are retained; source CSVs and raw-row previews are excluded. No license is granted for third-party materials.
