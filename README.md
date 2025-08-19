# 📈 Dogecoin Sentiment & Price Analysis

This project explores the relationship between **Dogecoin’s price movements** and the **sentiment/impact of tweets** (from random users and Elon Musk).  
It combines **financial data, text mining, and visualization** to study how public opinion and influential figures affect cryptocurrency trends.  

---

## 📂 Contents
- `dogecoin_analysis.ipynb` – Jupyter Notebook containing full code for:
  - Data preprocessing (Dogecoin price + tweets)
  - WordCloud & TF-IDF vectorization
  - Price trend visualizations (OHLC, moving averages, volatility)
  - Comparative analysis between random users’ posts vs Elon Musk’s tweets
- `dogecoin_analysis.pptx` – Presentation summarizing methodology, results, and insights

---

## ⚙️ Features & Workflow

1. **Data Collection**
   - Dogecoin historical price data (`DOGE-USD.csv`)
   - ~10,000 random Dogecoin-related tweets
   - Elon Musk’s tweets mentioning Dogecoin

2. **Text Processing**
   - Cleaning tweets (removing special characters, stopwords, stemming/lemmatization)
   - TF-IDF Vectorization
   - WordCloud generation for top terms

3. **Market Analysis**
   - Price trend visualization with OHLC charts (`plotly`)
   - Moving averages (50-day, 200-day)
   - Volatility analysis of Dogecoin prices after tweets

4. **Impact Comparison**
   - Random tweets vs Elon Musk’s tweets
   - Market capitalization comparison
   - Trading volume effects
   - Price movements before/after influential posts

---

## 📊 Example Visuals
- **Word Cloud** of Dogecoin-related tweets  
- **OHLC Candlestick Charts** for price movements  
- **Volatility & Market Cap comparisons**  
- **Maxima & Minima plots** showing turning points in price  

---

## 🚀 How to Run

### 1️⃣ Clone the repository
```bash
git clone https://github.com/your-username/dogecoin-analysis.git
cd dogecoin-analysis
2️⃣ Install dependencies

pip install pandas matplotlib wordcloud scikit-learn yfinance plotly mplfinance nltk
3️⃣ Run Jupyter Notebook
```

jupyter notebook dogecoin_analysis.ipynb
📚 Dependencies
Python 3.x

pandas, numpy

matplotlib, seaborn, mplfinance, plotly

scikit-learn

nltk

yfinance

wordcloud

glob, os

🏆 Results & Insights
Elon Musk’s tweets had a stronger correlation with sudden price spikes compared to random users.

Random users’ tweets mostly contributed to background noise, with limited impact on major price movements.

Market capitalization & volatility analysis clearly show Musk’s outsized influence on Dogecoin trading activity.

👩‍💻 Author
Ravuri Lakshmi 
