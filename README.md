# EPL Quantitative Probability Model ⚽📊
A machine learning pipeline built to backtest English Premier League match probabilities, engineered to bridge process logic with financial market data.

### The Architecture:
* **Language/Environment:** Python 3.13 (Local Miniconda setup)
* **Data Ingestion:** `pandas` (Processed raw CSV datasets of 380 matches, pivoting around Cloudflare web-scraping blocks).
* **Model:** Logistic Regression (`scikit-learn`) using an 80/20 train/test split.
* **Features:** Engineered a binary target variable mapped against historical bookmaker market odds.
* **Baseline Accuracy:** 72.37% on out-of-sample testing.

*Next Phase:* Engineering complex features (rolling averages, xG) to manage multicollinearity and attempt to break the bookmaker overround.
