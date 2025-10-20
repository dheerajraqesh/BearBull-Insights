# BearBull Insights 💹

[![Python](https://img.shields.io/badge/Python-3.x-blue)](https://www.python.org/)  
[![Streamlit](https://img.shields.io/badge/Streamlit-App-green)](https://streamlit.io/)  

**ML-Powered Stock Trend Predictor**  

BullBear Insights predicts **next-day stock trends (Up/Down)** using historical price data and technical indicators. Fully interactive **Streamlit dashboard** for visualization, predictions, and cumulative strategy analysis.

---

## 🔥 Features

- Predict next-day stock movement for any ticker symbol supported by Yahoo Finance.  
- Technical indicators included:
  - Moving averages (7, 14, 21-day)  
  - RSI (Relative Strength Index)  
  - MACD (Moving Average Convergence Divergence)  
  - Bollinger Bands  
  - Volume change  
- XGBoost classifier for tabular ML modeling.  
- Model performance metrics: Accuracy, Precision, Recall, F1, ROC-AUC.  
- Interactive charts:  
  - Close price trends  
  - Predicted vs actual trend  
  - Cumulative returns vs buy & hold  
- Next-day prediction with probability display.  

---

## 📂 Project Structure

bearbull-insights/
│
├── app.py # Streamlit app
├── data/ # Optional raw stock data
├── notebooks/ # Exploratory & feature engineering notebooks
├── requirements.txt # Python dependencies
└── README.md # Project overview

---

## 🚀 Installation

1. Clone the repository:

```bash
git clone https://github.com/yourusername/bullbear-insights.git
cd bullbear-insights
Install dependencies:
pip install -r requirements.txt
Run the Streamlit app:
streamlit run app.py
```
Open the app in your browser. Enter a ticker (e.g., AAPL) and select a period (3y, 5y, 10y).
📊 Example Dashboard
Model Performance Metrics:
{
  "Accuracy": 0.68,
  "Precision": 0.67,
  "Recall": 0.70,
  "F1": 0.68,
  "ROC_AUC": 0.72
}


Next-Day Prediction:
📈 UP (Prob of UP = 0.72)

(Replace screenshots with your Streamlit exports)

⚙️ Tech Stack
Python 3.x
Pandas, NumPy
Scikit-learn, XGBoost
Plotly for charts
Streamlit for interactive dashboard
yfinance for historical stock data
🛠️ Future Enhancements
Rolling retraining with latest data
Multi-stock batch predictions
Export predictions to CSV/Excel
Deploy as a public web app
