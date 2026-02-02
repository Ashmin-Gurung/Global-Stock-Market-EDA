# Global Stock Market Data Analysis & Visualization

# Project Overview
This project performs a comprehensive data analysis on global stock market indicators.  
The goal is to clean, transform, explore, and visualize stock market data to uncover trends, volatility patterns, and relationships between key financial variables.

This project was completed as part of a 'Data Analysis Certification Task' and demonstrates practical skills in data preprocessing, exploratory data analysis (EDA), visualization, and documentation.

# Objectives
- Perform data cleaning and preprocessing on real-world financial data  
- Detect and handle missing values and outliers  
- Apply feature engineering to enrich the dataset  
- Conduct exploratory data analysis using visualizations  
- Extract meaningful insights to support decision-making  

# Dataset Description
**Dataset Name:** Daily_Global_Stock_Market_Indicators.csv  

**Key Columns:**
- Date – Trading date  
- Index_Name – Stock market index  
- Country – Country of the index  
- Open, High, Low, Close – Daily price indicators  
- Volume – Trading volume  
- Daily_Change_Percent – Daily percentage price change  

# Data Cleaning & Preprocessing
The following steps were applied:
- Converted the Date column to datetime format  
- Detected outliers using the **Interquartile Range (IQR) method**  
- Removed extreme outliers where appropriate  


#  Feature Engineering
Additional features were created to improve analysis:
- **Daily_Range** = High − Low (volatility indicator)  
- **Price_Change** = Close − Open (daily momentum)  
- **Direction** = Binary indicator (1 = price up, 0 = price down)  

Categorical variables were encoded using **one-hot encoding**.

## 📈 Exploratory Data Analysis (EDA)
EDA was performed using **Matplotlib** and **Seaborn**, including:
- Distribution plots for daily returns  
- Box plots for outlier detection  
- Scatter plots for price relationships  
- Country-wise performance comparisons  
- Correlation heatmap for numerical features  

# Key Insights
- Open, High, Low, and Close prices are highly correlated
- Most daily returns are centered around 0%, indicating market efficiency  
- Daily price range effectively captures market volatility 
- Trading volume shows weak correlation with daily price changes  
- Stock market behavior varies significantly across countries  

# Tools & Technologies
- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Jupyter Notebook  
- Git & GitHub  

# How to run
1. Clone the repository  
2. Install required libraries:
   pip install pandas numpy matplotlib seaborn
3. Open the Jupyter Notebook adn run the cell.
