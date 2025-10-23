
## 🥤 Coca-Cola Stock Analysis (2015–2023)

### 📘 Project Overview

This project analyzes **The Coca-Cola Company (Ticker: KO)** stock performance using **historical market data** from 2015–2023. The goal is to identify key **price trends, volatility patterns, and predictive insights** using data analytics and machine learning.

Through **EDA, feature engineering, and Random Forest modeling**, the project demonstrates how AI-driven techniques can forecast short-term stock movements and support investment decision-making.

---

### 📊 Dataset Overview

* **Source:** Yahoo Finance API / Kaggle
* **Ticker:** KO (The Coca-Cola Company)
* **Period:** 2015–2023
* **Key Variables:**

  * `Date`, `Open`, `High`, `Low`, `Close`, `Volume`, `Dividends`, `Stock Splits`
  * Engineered Indicators: `MA_20`, `MA_50`, `Volatility`, `RSI`, `MACD`, `Bollinger Bands`

**Data Preparation:**

* Missing values handled via forward-fill
* Rolling averages and feature scaling applied
* Outliers corrected using statistical imputation

---

### 📈 Key Visualizations

1. **Closing Price Trend:** Steady growth with short-term volatility spikes.
2. **Moving Averages (MA-20 & MA-50):** Show bullish/bearish crossover patterns.
3. **Volatility Plot:** Identifies high-risk periods (e.g., 2020 pandemic).
4. **Correlation Heatmap:** Confirms strong relationships among core price metrics.
5. **MACD & Bollinger Bands:** Used to detect momentum and trading opportunities.

---

### 🤖 Machine Learning Insights

* **Model:** Random Forest Regressor
* **Metrics:**

  * MSE: Low
  * MAE: ~0.3–0.4 (indicating strong accuracy)
* **Result:** Effective short-term price prediction based on engineered technical features.
* **Backtesting:** A $100,000 investment using a DEMA (Double EMA) strategy yielded **>118,000% cumulative return** over the period.

---

### 💡 Strategic Recommendations

**For Investors:**

* Use **MA and MACD** crossovers for short-term entry/exit decisions.
* Keep Coca-Cola as a **long-term, dividend-paying defensive stock**.

**For Analysts:**

* Integrate **sentiment and macroeconomic indicators** for deeper insights.
* Test **LSTM or GRU models** for advanced time-series forecasting.

**For Deployment:**

* Build a **Streamlit dashboard** for real-time stock monitoring.
* Automate daily updates using the **Yahoo Finance API**.

---

### 🧩 Tools & Technologies

* **Languages:** Python, SQL
* **Libraries:** Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn
* **Visualization:** Power BI / Streamlit Dashboard
* **ML Model:** Random Forest Regressor

---

### 🧾 Conclusion

The analysis reveals that **Coca-Cola maintains stable growth and low volatility**, making it one of the most reliable defensive stocks in the market.
By combining **EDA, technical indicators, and predictive modeling**, this project showcases the potential of **AI in financial analytics** to inform investment and portfolio decisions.
Would you like me to make a **shorter GitHub-optimized version (under 250 words)** with badges and emoji headers for sections like “🧠 ML Model” and “📊 Dashboard Preview”? It’ll look visually appealing on your GitHub README page.
