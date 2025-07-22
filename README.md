# 📈 ANFIS-Based Stock Price Prediction

This project trains an Adaptive Neuro-Fuzzy Inference System (ANFIS) to predict the next day's closing stock price using historical stock market data.

## 🚀 Overview

We apply a fuzzy inference layer and rule-based ANFIS model to learn from key market indicators and forecast the `nextclose` value, i.e., the closing price of the following trading day.

## 🧠 Model

- **Model Type:** Adaptive Neuro-Fuzzy Inference System
- **Label:** `nextclose` (next-day closing price)
- **Features:** Open, High, Low, Close, Volume

## 🛠 Tech Stack

- Python 3.x
- NumPy
- Pandas
- Scikit-learn
- Matplotlib

## 📁 Dataset

- `dataset.csv` is the input file
- A processed version with the `nextclose` column is saved as `updated_dataset.csv` during preprocessing

## 📦 Installation

```bash
git clone https://github.com/yourusername/anfis-stock-price-prediction.git
cd anfis-stock-price-prediction
pip install -r requirements.txt
```

## ▶️ How to Run

Run the notebook:

```bash
jupyter notebook notebooks/ANFIS_stock_prediction.ipynb
```

(OR)

Convert your logic into a script in `src/train.py` and run:

```bash
python src/train.py
```

## 📊 Output

- Visual comparison between predicted and actual `nextclose` values
- Basic statistics and evaluation results
