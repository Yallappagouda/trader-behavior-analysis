# Trader Behavior Insights – Sentiment vs Trading Performance

## Project Overview
This project analyzes the relationship between **Bitcoin market sentiment (Fear & Greed Index)** and **trader behavior** using historical trading data from Hyperliquid.

The goal is to understand how market sentiment affects:
- Trader profitability
- Trading activity
- Trade size
- Buy vs Sell behavior

## Dataset
Two datasets were used in this analysis:

1. **Hyperliquid Historical Trader Data**
   - Contains trader transactions including price, trade size, profit/loss, and timestamps.

2. **Bitcoin Fear & Greed Index**
   - Provides daily market sentiment classification:
   - Extreme Fear
   - Fear
   - Neutral
   - Greed
   - Extreme Greed

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Data Analysis Steps

1. Data Cleaning
   - Converted timestamps into datetime format
   - Extracted date from trade timestamps

2. Data Merging
   - Merged trading data with sentiment data using date

3. Exploratory Data Analysis
   - Profitability analysis by market sentiment
   - Trade activity comparison
   - Buy vs Sell behavior analysis
   - Trade size analysis

4. Visualization
   - Boxplots
   - Bar charts
   - Trade distribution graphs

## Key Insights

- Traders generate **higher profits during Extreme Greed market conditions**.
- Trading activity is highest during **Fear and Greed phases**.
- Traders tend to **take larger trade sizes during Greed markets**.
- Market sentiment has a strong influence on trader behavior and risk-taking.

# Trader Behavior Insights – Sentiment vs Trading Performance

## Project Overview
This project analyzes the relationship between **Bitcoin market sentiment (Fear & Greed Index)** and **trader behavior** using historical trading data from Hyperliquid.

The goal is to understand how market sentiment affects:
- Trader profitability
- Trading activity
- Trade size
- Buy vs Sell behavior

## Dataset
Two datasets were used in this analysis:

1. **Hyperliquid Historical Trader Data**
   - Contains trader transactions including price, trade size, profit/loss, and timestamps.

2. **Bitcoin Fear & Greed Index**
   - Provides daily market sentiment classification:
   - Extreme Fear
   - Fear
   - Neutral
   - Greed
   - Extreme Greed

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Data Analysis Steps

1. Data Cleaning
   - Converted timestamps into datetime format
   - Extracted date from trade timestamps

2. Data Merging
   - Merged trading data with sentiment data using date

3. Exploratory Data Analysis
   - Profitability analysis by market sentiment
   - Trade activity comparison
   - Buy vs Sell behavior analysis
   - Trade size analysis

4. Visualization
   - Boxplots
   - Bar charts
   - Trade distribution graphs

## Key Insights

- Traders generate **higher profits during Extreme Greed market conditions**.
- Trading activity is highest during **Fear and Greed phases**.
- Traders tend to **take larger trade sizes during Greed markets**.
- Market sentiment has a strong influence on trader behavior and risk-taking.

## Project Structure

trader-behavior-analysis
│
├── trader_sentiment_analysis.ipynb
├── historical_data.csv
├── fear_greed_index.csv
├── requirements.txt
└── README.md

## How to Run the Project

1. Clone the repository


git clone <your-repo-link>


2. Install required libraries


pip install -r requirements.txt


3. Run the Jupyter notebook


jupyter notebook


Open:

trader_sentiment_analysis.ipynb


## Author

Yallappagouda Patil

GitHub: https://github.com/Yallappagouda