# 📊 Financial News Exploratory Data Analysis (EDA)

## 🧠 Project Overview

This project focuses on exploring and understanding a large-scale financial news dataset as part of the **Nova Financial Solutions Predicting Price Moves with News Sentiment Challenge**.

The objective of this analysis is to investigate patterns in financial news headlines, publication behavior, publisher activity, and recurring market-related topics that may influence stock market movements.

This notebook forms the foundation for later stages involving:

- Sentiment Analysis
- Technical Indicator Analysis
- Correlation between News Sentiment and Stock Price Movements

---

# 🎯 Business Objective

Nova Financial Solutions aims to improve predictive financial analytics by understanding how financial news impacts stock market behavior.

This exploratory analysis helps answer important questions such as:

- Which publishers contribute the most financial news?
- When is financial news most frequently published?
- What are the most common financial topics and keywords?
- Are there noticeable spikes in publication activity?
- How can financial headlines support future stock movement prediction?

The insights discovered in this notebook will support future sentiment analysis and investment strategy development.

---

# 📂 Dataset Description

The dataset used in this analysis contains financial news headlines and related metadata.

## Dataset Fields

| Column | Description |
|---|---|
| headline | Financial news headline |
| url | Link to the article |
| publisher | News publisher or author |
| date | Publication date and time |
| stock | Stock ticker symbol |

---

# ⚙️ Technologies and Libraries Used

The following Python libraries were used throughout this analysis:

- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

These libraries support:

- Data manipulation
- Statistical analysis
- Visualization
- Keyword extraction
- Exploratory data analysis

---

# 📈 Exploratory Data Analysis Performed

This notebook includes several analytical steps:

## 1️⃣ Data Loading and Inspection

- Loaded the raw financial news dataset
- Inspected dataset dimensions and structure
- Checked data types and missing values

---

## 2️⃣ Headline Length Analysis

The length of financial headlines was analyzed to understand the structure and complexity of news reporting.

### Key Activities
- Calculated headline character counts
- Generated descriptive statistics
- Visualized headline length distribution

---

## 3️⃣ Publisher Analysis

Publisher activity was explored to identify the most active contributors to financial news reporting.

### Key Activities
- Counted articles per publisher
- Ranked top publishers
- Visualized publisher frequency

---

## 4️⃣ Time Series Analysis of News Volume

Publication trends over time were analyzed to identify spikes in news activity and periods of intense market reporting.

### Key Activities
- Converted publication timestamps
- Grouped articles by publication date
- Visualized daily news frequency

---

## 5️⃣ Publishing Time Analysis

The hourly distribution of financial news publications was analyzed to determine when news is most frequently released.

### Key Activities
- Extracted publication hours
- Counted hourly article frequency
- Visualized publication behavior by hour

---

## 6️⃣ Keyword and Topic Analysis

Natural Language Processing techniques were applied to identify common keywords and recurring financial themes.

### Key Activities
- Applied CountVectorizer
- Removed stopwords
- Extracted high-frequency financial terms
- Visualized keyword frequency

---

# 📊 Key Insights

Several important observations were discovered during the exploratory analysis:

- Financial news activity fluctuates significantly over time.
- Certain publishers dominate the financial news ecosystem.
- Most financial articles are published during active market hours.
- Headlines frequently focus on earnings, ratings, stock performance, and market movement.
- The dataset contains rich textual information suitable for sentiment analysis and predictive modeling.

---

# 🚀 Importance of This Analysis

This exploratory analysis provides a strong foundation for future tasks including:

- Sentiment scoring of headlines
- Technical stock indicator analysis
- Correlation analysis between news and stock returns
- Predictive investment strategy development

The findings from this notebook help transform raw financial news into actionable financial intelligence.

---

# ✅ Conclusion

This notebook successfully explored the structure, trends, and characteristics of the financial news dataset.

The analysis demonstrates how exploratory data analysis can uncover meaningful patterns in financial reporting behavior and prepare data for advanced NLP and quantitative financial analysis.

Future stages of the project will combine these insights with historical stock price data to evaluate how news sentiment influences stock market performance.