[README.md](https://github.com/user-attachments/files/21919806/README.md)
# Volatility & Risk Engine — FTSE 100 ETFs (ISF.L, VUKE.L)

**Status:** learning project (in progress) 

This repo contains a Python toolkit for **volatility forecasting** and **risk measurement** on FTSE 100 ETFs.



> Educational only — **not** financial advice.

---

## Quickstart

```bash
# 1) Clone & create a virtual environment (recommended)
python -m venv .venv
# Windows: .\.venv\Scripts\activate
# macOS/Linux:
source .venv/bin/activate

# 2) Install
pip install -r requirements.txt

# 3) Run tests (optional)
pytest -q

# 4) Launch Streamlit app
streamlit run app/streamlit_app.py
```

The app and data loader fetch prices from Yahoo Finance for `ISF.L` and `VUKE.L`.
You can change tickers in the sidebar.

---

## Repository layout

```
.
├─ app/                   # Streamlit UI (placeholder)
├─ data/                  # Raw/processed data (empty; tracked via .gitkeep)
├─ notebooks/             # Explanatory notebooks (skeleton)
├─ src/                   # Python package code (stubs & pseudocode)
├─ tests/                 # Test placeholders
├─ .gitignore             # Standard ignores
├─ LICENSE                # No license
├─ README.md              # This file
└─ requirements.txt       # Will be refined as features are added

```

---

## How it works


---

