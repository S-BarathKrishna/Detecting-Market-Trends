# **Detecting Market Trends via Financial and Economic Indicators**

This project explores the detection of market trends using key macroeconomic indicators and financial performance data. By analyzing time-series data like GDP growth, interest rates, inflation, and market indices, we extract insights to support decision-making in finance and economics.

**📊 Project Objectives**

Analyze financial reports and economic indicators over time

Identify leading indicators of market trends

Correlate macroeconomic events with market performance

Deliver actionable insights for investors and analysts

**🗂 Dataset Description**

File: marketdata.csv

Source: Kaggle / Financial APIs / Economic Databases

Columns include:

Date

GDP Growth

Inflation Rate

Interest Rate

Market Index

Sector Performance (A, B, etc.)

**🔧 Tools & Technologies**

Python 3.x

pandas, numpy

seaborn, matplotlib

scikit-learn (for modeling)

Jupyter Notebook

Power BI (for optional dashboard)

**🔍 Key Insights**

GDP growth strongly correlates with market index performance (r ≈ 0.76)

Inflation and interest rates negatively affect market returns

Certain sectors outperform others during high-growth or low-inflation periods

Predictive trend modeling shows effectiveness with lagging indicators

**📈 Sample Visualizations**

Time-series plots of GDP vs. Market Index

Heatmaps showing correlations between indicators

Sectoral bar charts per quarter

Rolling averages and economic trend overlays

**🚀 How to Run**

Clone the repository:
git clone https://github.com/Barath20-05/Detecting-Market-Trends

Install required libraries:
pip install -r requirements.txt

Open the notebook:

jupyter notebook market_trends_analysis.ipynb

Run cells to process, visualize, and analyze the dataset

**📂 Repository Structure**

├── marketdata.csv

├── market_trends_analysis.ipynb

└── README.md

**📌 Future Enhancements**

Integrate real-time economic APIs

Apply LSTM or ARIMA models for forecasting

Use NLP to include central bank announcements and news headlines

Build web dashboard with live data updates

**🤝 Contributors**

S.Barathkrishna— Data collection Data Preprocessing, EDA

M.Abubakkar Sithik— Trends ,Correlation Analysis ,Visualization

B.Rajumenan — Modeling,Presentation, Documentation
