# building-a-bitcoin-volatility-surface-from-a-real-time-market-snapshot
A Jupyter Notebook that builds and calibrates a Stochastic Volatility Inspired (SVI) model using a real-time snapshot of Bitcoin options from Binance, showing the full process from data collection to volatility surface visualization

## Running the Notebook

It is recommended to run this project inside a **virtual environment** to keep dependencies isolated and clean.
A `requirements.txt` file is included, so you can easily install everything needed.

### Steps

1. **Create and activate a virtual environment**

```bash
python -m venv .venv
source .venv/bin/activate       # On macOS or Linux
.venv\Scripts\activate          # On Windows