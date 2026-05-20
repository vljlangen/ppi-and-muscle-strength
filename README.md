# PPI and muscle strength in older adults

Analysis code for PPI use vs grip strength, walking speed, armchair test, CCI, and non-vitamin drug count.

## Files

- `ppi_vs_muscle_analysis.ipynb` — main analysis notebook.
- `requirements-notebook.txt` — pinned Python packages for this notebook.

## Environment (Python 3.9.6)

Dependencies are managed in a **virtual environment** (`.venv`) so that package versions remain isolated from the system Python stack. After one-time configuration, the notebook is executed under that environment’s interpreter.

Original data are not distributed with this repository; the documented workflow applies equally to externally supplied analytic tables or to synthetic inputs used for verification or instruction.

In the directory that contains the notebook and `requirements-notebook.txt`:

```bash
/usr/bin/python3 -m venv .venv
.venv/bin/python -m pip install -U pip setuptools wheel
.venv/bin/pip install -r requirements-notebook.txt
```

## License

MIT
