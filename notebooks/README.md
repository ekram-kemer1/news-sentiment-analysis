
# Financial News Sentiment Analysis

## Project Overview

This project analyzes financial news headlines and stock market data to explore the relationship between news sentiment and stock price movements.

The project includes:
- Exploratory Data Analysis (EDA)
- Technical Indicator Analysis
- Sentiment Analysis
- Correlation Analysis between sentiment and stock returns

---

## Dataset

### Financial News Dataset
- Source: FNSPID Financial News Dataset
- Contains:
  - headline
  - publisher
  - date
  - stock ticker
  - article URL

### Stock Price Dataset
Historical stock price data for:
- AAPL
- AMZN
- GOOG
- META
- NVDA

Downloaded using Yahoo Finance.

---

## Project Structure

```text
news-sentiment-analysis/
│
├── data/raw/
├── notebooks/
├── src/
├── scripts/
├── tests/
├── requirements.txt
├── README.md
└── .gitignore
```

---

## Setup Instructions

### 1. Clone Repository

```bash
git clone <repository-url>
```

### 2. Navigate to Project

```bash
cd news-sentiment-analysis
```

### 3. Create Virtual Environment

```bash
python -m venv venv
```

### 4. Activate Virtual Environment

#### Windows

```bash
venv\Scripts\activate
```

### 5. Install Dependencies

```bash
pip install -r requirements.txt
```

### 6. Launch Jupyter Notebook

```bash
jupyter notebook
```

---

## Technologies Used

- Python
- Pandas
- Matplotlib
- Seaborn
- NLTK
- TA-Lib
- PyNance
- Scikit-learn

---

## Tasks Completed

### Task 1
- EDA on news dataset
- Publisher analysis
- Time-series analysis
- Keyword analysis

### Task 2
- Technical indicators
- SMA
- EMA
- RSI
- MACD

### Task 3
- Sentiment analysis
- Daily returns
- Correlation analysis

---

## Author

Ekram Kemer