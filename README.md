Trader Performance and Market Sentiment Analysis 📈
This project analyzes the relationship between cryptocurrency trader performance and market sentiment, using historical trade data and the Fear & Greed Index. It includes scripts for exploratory data analysis (EDA), visualization, and building a predictive model to forecast trade profitability.

📜 Overview
The primary goal is to uncover patterns in trader behavior based on market sentiment (Fear vs. Greed) and build a machine learning model to predict whether a trade will be profitable. This can help in developing smarter, data-driven trading strategies.

✨ Features
Data Preprocessing: Cleans and merges historical trader data with daily market sentiment data.

Exploratory Data Analysis (EDA): Investigates distributions and relationships in the data.

Visualization: Generates and saves plots to visualize key insights, including:

PnL distribution across different sentiment levels.

Leverage usage vs. market sentiment.

Trading volume and side (Buy/Sell) patterns.

Predictive Modeling: Implements a Logistic Regression model to predict trade profitability based on features like sentiment, leverage, and trade size.

Model Evaluation: Measures the model's performance using standard metrics like accuracy, a classification report, and a confusion matrix.

💾 Datasets
This project uses two primary datasets:

historical_data.csv: Contains anonymized historical trader data, including trade side, size, leverage, and closed Profit and Loss (PnL).

fear_greed_index.csv: Contains the daily Bitcoin Fear & Greed Index value and its classification (e.g., "Fear", "Extreme Greed").

⚙️ Setup and Installation
Follow these steps to set up your local environment.

1. Prerequisites
Python 3.7+

2. Clone the Repository (Example)
Bash

git clone https://github.com/your-username/trader-sentiment-analysis.git
cd trader-sentiment-analysis
3. Install Required Libraries
Install the necessary Python packages using the requirements.txt file.

Bash

pip install -r requirements.txt
Create a file named requirements.txt with the following content:

pandas
scikit-learn
matplotlib
seaborn
4. Place Your Data
Make sure your historical_data.csv and fear_greed_index.csv files are placed in the root directory of the project.

🚀 How to Run
The project contains two main Python scripts:

1. Exploratory Analysis (analysis.py)
This script performs the initial data cleaning, merging, and generates insightful plots.

Bash

python analysis.py
2. Predictive Modeling (prediction.py)
This script builds on the first by adding a machine learning model to predict trade outcomes.

Bash

python prediction.py
