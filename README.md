# Laptop Inventory Dashboard

A small data-analysis exercise: read an Excel laptop inventory, clean the data, and produce a dashboard showing brand and RAM-capacity distribution.

## Files

- **`laptop_dashboard.ipynb`** — Jupyter notebook walking through the analysis end-to-end (load -> clean -> visualize -> summarize).
- **`laptop_dashboard.html`** — Self-contained HTML/CSS dashboard. Open in any browser; no dependencies.

## Running the notebook

Requires Python 3.13 with `pandas`, `openpyxl`, `matplotlib`, and `ipykernel` installed:

```powershell
pip install pandas openpyxl matplotlib ipykernel
```

The source `.xlsx` file is intentionally not committed (see `.gitignore`). Update the `FILE_PATH` variable in the notebook to point at your own copy.

## Dashboard preview

The HTML dashboard shows:

- KPI cards (total laptops, count per brand)
- Brand-distribution bar + donut charts
- RAM-capacity distribution
- Status breakdown
- Brand x RAM matrix (heat-mapped)
