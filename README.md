# 📈 Predicting Price Moves with News Sentiment

## 🧠 Overview

This project was developed as part of the **Nova Financial Solutions Financial News Sentiment Analysis Challenge**.

The objective of this project is to analyze financial news headlines and investigate how news sentiment relates to stock market movements. By combining Natural Language Processing (NLP) techniques with quantitative stock analysis, the project aims to uncover relationships between market sentiment and stock price behavior.

The project includes:

- Exploratory Data Analysis (EDA)
- Financial news sentiment analysis
- Technical stock indicator analysis
- Correlation analysis between sentiment and stock returns
- Visualization and interpretation of financial insights

---

# 🎯 Business Objective

Nova Financial Solutions seeks to enhance predictive analytics capabilities using financial news intelligence.

The primary goals of this project are:

- Quantify sentiment expressed in financial news headlines
- Analyze stock market behavior using technical indicators
- Measure statistical relationships between news sentiment and stock price changes
- Generate actionable investment insights from financial data

This work supports data-driven investment decision-making and predictive financial analytics.

---

# 📂 Project Structure

```text
news-sentiment-analysis/

├── .github/
│   └── workflows/
│       └── unittests.yml
│
├── data/
│   └── raw/
│       ├── raw_analyst_ratings.csv
│       ├── AAPL.csv
│       ├── AMZN.csv
│       ├── GOOG.csv
│       ├── META.csv
│       └── NVDA.csv
│
├── notebooks/
│   ├── README.md
│   ├── task1_eda.ipynb
│   ├── task2_quantitative_analysis.ipynb
│   └── task3_sentiment_correlation.ipynb
│
├── src/
│   └── __init__.py
│
├── tests/
│   └── __init__.py
│
├── scripts/
│   ├── __init__.py
│   └── README.md
│
├── requirements.txt
├── .gitignore
└── README.md
```

---

# 📊 Dataset Description

This project uses two primary datasets:

## 1️⃣ Financial News Dataset

The financial news dataset contains headlines and metadata from financial news articles.

### Fields

| Column | Description |
|---|---|
| headline | Financial news headline |
| url | Article URL |
| publisher | News publisher |
| date | Publication date and time |
| stock | Stock ticker symbol |

---

## 2️⃣ Historical Stock Price Dataset

Historical stock data was collected using Yahoo Finance (YFinance).

### Fields

| Column | Description |
|---|---|
| Date | Trading day |
| Open | Opening stock price |
| High | Highest stock price |
| Low | Lowest stock price |
| Close | Closing stock price |
| Adj Close | Adjusted closing price |
| Volume | Trading volume |

---

# ⚙️ Technologies Used

This project was developed using the following technologies and libraries:

## Programming Language
- Python

## Data Analysis
- Pandas
- NumPy

## Visualization
- Matplotlib
- Seaborn

## Natural Language Processing
- Scikit-learn
- NLTK
- TextBlob
- VADER Sentiment

## Financial Analysis
- TA-Lib
- PyNance
- YFinance

## Development Tools
- Git
- GitHub
- Jupyter Notebook
- GitHub Actions

---

# 📌 Task 1 — Exploratory Data Analysis

## Objectives

- Understand the structure of the financial news dataset
- Analyze publication trends and publisher activity
- Identify recurring keywords and financial topics
- Visualize publication behavior over time

## Key Analyses

- Headline length distribution
- Publisher activity analysis
- Time series publication analysis
- Publishing hour analysis
- Keyword extraction using NLP
- Topic identification

## Key Visualizations

- Headline length histogram
- Publisher frequency bar chart
- Daily publication trend graph
- Keyword frequency visualization

---

# 📌 Task 2 — Quantitative Financial Analysis

## Objectives

- Analyze historical stock price data
- Compute technical indicators
- Visualize stock market trends

## Technical Indicators

### Moving Averages
- SMA (Simple Moving Average)
- EMA (Exponential Moving Average)

### Momentum Indicators
- RSI (Relative Strength Index)
- MACD (Moving Average Convergence Divergence)

## Visualizations

- Stock closing prices
- SMA and EMA overlays
- RSI trend plots
- MACD indicator charts

---

# 📌 Task 3 — Sentiment and Correlation Analysis

## Objectives

- Assign sentiment scores to headlines
- Calculate daily stock returns
- Measure relationships between sentiment and market movement

## Key Steps

- Date normalization
- Sentiment scoring
- Daily return computation
- Correlation analysis
- Statistical interpretation

## Analytical Methods

- Pearson Correlation
- Sentiment classification
- Scatter plot visualization
- Comparative sentiment analysis

---

# 📈 Key Insights

Several important findings emerged during this analysis:

- Financial news volume varies significantly across time periods.
- Certain publishers dominate financial reporting activity.
- Financial headlines commonly focus on earnings, analyst ratings, and stock movement.
- Technical indicators reveal periods of strong market momentum and volatility.
- Sentiment scores show measurable relationships with stock price changes.

---

# 🚀 Installation and Setup

## 1️⃣ Clone Repository

```bash
git clone < https://github.com/Benareyo/news-sentiment-analysis.git>
```

---

## 2️⃣ Create Virtual Environment

```bash
python -m venv venv
```

---

## 3️⃣ Activate Environment

### Windows

```bash
venv\Scripts\activate
```

### Linux / Mac

```bash
source venv/bin/activate
```

---

## 4️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

---

# ▶️ Running the Project

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open notebooks inside the `notebooks/` directory.

---

# 📌 Future Improvements

Future enhancements may include:

- Deep learning sentiment models
- Real-time financial news streaming
- Predictive stock forecasting models
- Portfolio optimization strategies
- Advanced NLP transformers (BERT, FinBERT)

---

# ⚠️ Limitations

Some limitations of this project include:

- Sentiment does not always directly cause stock movement
- Financial markets are influenced by multiple external factors
- Headlines alone may not fully represent article sentiment
- Time lag effects may impact correlation strength

---

# 👩‍💻 Author

**Betel Yohannes**

---

# 📜 License

This project was developed for educational and research purposes as part of the Nova Financial Solutions challenge.