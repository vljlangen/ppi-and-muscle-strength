# PPI and muscle strength in older adults

Analysis code for PPI use vs grip strength, walking speed, armchair test, CCI, and non-vitamin drug count.

## Files

- `ppi_vs_muscle_analysis.ipynb` — analysis (code only; no outputs committed)
- `requirements-notebook.txt` — Python dependencies
- `create_*.R` — upstream R scripts (local; not part of Zenodo)

## Data

Participant-level data are **not** in this repo or on Zenodo. For local runs only, use an analytic table from the R pipeline as `ppi_and_muscle.csv` next to the notebook.

## Setup

```bash
python3 -m venv venv
source venv/bin/activate
pip install -r requirements-notebook.txt
```

Open the notebook in VS Code or Jupyter, select `venv`, run all cells. Writes `figures/` and `table1.xlsx` locally.

Tested: Python 3.14, pandas 3.0.

## License

MIT
