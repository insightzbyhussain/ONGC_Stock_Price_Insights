##🔖 Project Title: Analyzing ONGC Stocks Trends with Python and Data Visualization

#🔖 Project Overview

This project explores the historical stock data of Oil and Natural Gas Corporation (ONGC) to extract meaningful insights into stock trends, volume patterns, and correlations.
Using Python (Pandas, NumPy, Matplotlib, Seaborn), the dataset is cleaned, processed, and visualized to reveal hidden trends in ONGC’s market performance. This project demonstrates real-world data wrangling, EDA, and visualization skills—crucial for Data Analyst & Data Scientist roles.

# 📌 Objective:
To analyze and visualize ONGC’s stock data using Python libraries like Pandas, Seaborn, and Matplotlib.

# The analysis includes:
-> Trend exploration through time-series plots
-> Calculation of moving averages
-> Volatility detection
-> Distribution of returns

# The goal is to transform raw financial data into clear, compelling insights that support smarter decision-making.
-------------------------------------------------------------------------------------------------------------------------------------------

## 📁 Dataset
- **Source**: [Kaggle – ONGC Stock Performance Dataset](https://www.kaggle.com/datasets/nitirajkulkarni/ongc-ns-stock-performance)  
- **Ticker**: `ONGC.NS`  
- **Fields Used**: `Date`, `Open`, `High`, `Low`, `Close`, `Adj Close`, `Volume`

-------------------------------------------------------------------------------------------------------------------------------------------

## 🛠️ Tools & Libraries Used
-> Programming Language: Python 
-> Libraries Used: Pandas, NumPy, Matplotlib, Seaborn
-> Dataset: ONGC Historical Stock Price Data (CSV) 
-> Platformed IDE: Jupyter Notebook

-------------------------------------------------------------------------------------------------------------------------------------------

🚀 Key Features

✅ Data Cleaning & Preprocessing
Removed null values, duplicates, and irrelevant columns
Handled missing data using forward/backward fill techniques
Converted dates into proper datetime format

✅ Exploratory Data Analysis (EDA)
Summary statistics & distribution analysis
Correlation heatmaps to identify feature relationships
Insights on stock movement patterns

✅ Data Visualization
Stock trends (Open, High, Low, Close, Adjusted Close)
Volume fluctuations over time
Correlation matrix with intuitive heatmaps

✅ Business Insights
Strong positive correlation between Open vs Close prices
Weak correlation between Volume and Prices
Clean dataset ready for further modeling (ML, forecasting, etc.)

-------------------------------------------------------------------------------------------------------------------------------------------

## 📈 Sample Visualizations

All plots are auto-generated and saved under the `Plots/` directory:

- ![Correlation Matrix](Python_Project/Plots/Correlation_matrix_plot.png)
- ![Histogram+KDE](Python_Project/Plots/Distribution_of_Open.png)
- ![Histogram+KDE](Python_Project/Plots/Distribution_of_High.png)
- ![Histogram+KDE](Python_Project/Plots/Distribution_of_Low.png)
- ![Histogram+KDE](Python_Project/Plots/Distribution_of_Close.png)
- ![Histogram+KDE](Python_Project/Plots/Distribution_of_Adjclose.png)
- ![Histogram+KDE](Python_Project/Plots/Distribution_of_Volume.png)
- ![Line Chart](Python_Project/Plots/Moving_Average_(20,50))
- ![Line Chart](Python_Project/Plots/Volatility(10)(Rolling SD))
- ![Lollipop+Line Chart](Python_Project/Plots/Volume_&_spikes)

-------------------------------------------------------------------------------------------------------------------------------------------

🎯 Why This Project Stands Out

This project is not just data analysis—it highlights practical problem-solving, attention to data quality, and insightful visualization, which are core skills recruiters look for in:

📌 Data Analyst
📌 Business Analyst
📌 Data Scientist (Entry-level / Fresher)

-------------------------------------------------------------------------------------------------------------------------------------------

## 🗂️ Project Structure

```bash
📁 Python_Project
│
├── ONGC_Historical_Data.csv			# Raw CSV file (Downloaded)
├── ONGC_Stock_CleanedData.csv			# Cleaned CSV file (Exported)
├── ONGC_Stock_Price_Insight.ipynb			# Python jupyter notebook 
├── Plots					# All graph  
└── README.md					# This file 

-------------------------------------------------------------------------------------------------------------------------------------------

## 🚀 How to Run

1. Clone or download this repository  
2. Install the required Python libraries:
   ```bash
   pip install pandas matplotlib seaborn

-------------------------------------------------------------------------------------------------------------------------------------------

## 📌 Future Scope

- Add stock price forecasting using Linear Regression or ARIMA
- Deploy as an interactive dashboard with Streamlit
- Integrate live stock data using the Yahoo Finance API
- Export insights as automated reports

-------------------------------------------------------------------------------------------------------------------------------------------

## 🧠 Learnings

- Data cleaning and preprocessing techniques
- How to handle stock time-series data
- Importance of correlation analysis in finance
- Moving Average
- Volatility
- Volume and Spikes
- Visual analytics for financial datasets

-------------------------------------------------------------------------------------------------------------------------------------------

## 👤 Author
**Mohd Hussain Khan**  
📌 MSc Data Science (Final Year) | SIES College of Arts, Science & Commerce
💼 Aspiring Data Scientist / Data Analyst
[LinkedIn](www.linkedin.com/in/insightzbyhussain) | [GitHub](https://github.com/insightzbyhussain)

## 📌 License
This project is open-source and available for learning, research, and academic demonstration purposes.

## 👉 If you like this project, don’t forget to ⭐ the repo!
