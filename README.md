---

### 🪙 3️⃣ Daily Gold Prices — Time Series Forecasting
```markdown
# 🪙 Daily Gold Prices — Time Series Forecasting

![Python](https://img.shields.io/badge/Python-3.10-blue?style=for-the-badge)
![LSTM](https://img.shields.io/badge/Model-LSTM-orange?style=for-the-badge)
![Gold](https://img.shields.io/badge/Asset-Gold%20Prices-yellow?style=for-the-badge)

## 📘 Overview
Predicts **next-day gold prices** using LSTM for trend-aware forecasting.  
Evaluates the model’s stability across volatile and calm market periods.

---

## 📊 Dataset
**Attributes:** Date, Open, High, Low, Close  
**Goal:** Predict next-day Close  
📁 *Path:* `Datasets/Main 3.csv`

---

## 🧠 Model
LSTM(64) → Dropout(0.3) → LSTM(32) → Dense(1)

yaml
Copy code
**Metrics:** RMSE, MAE, MAPE  
**Baselines:** Naive, ARIMA, GRU  

---

## 🚀 Run the Project
```bash
git clone https://github.com/pranaychowdary765/-Daily-Gold-Prices-.git
cd Daily-Gold-Prices
pip install -r requirements.txt
python main.py
📈 Result Summary
Model tracks medium-term trends well but lags slightly during sudden price surges.
