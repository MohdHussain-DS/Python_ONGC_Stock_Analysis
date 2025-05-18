
# Title:- 📈ONGC Stock price analysis using python programming

# About this project:- 🔍This project analyzes the historical stock data of **ONGC (Oil and Natural Gas Corporation)**
using Python and popular data analysis libraries. It provides insights into stock price trends, Volatility, trading volumes, and feature correlations.

# Aim - 🎯To derive insights from the past data of ONGC using python-based data analysis techniques like time series plotting, rolling average and return distribution

---------------------------------------------------------------------------------------------------------

## 📁 Dataset
- **Source**: [Kaggle] ["https://www.kaggle.com/datasets/nitirajkulkarni/ongc-ns-stock-performance"]
- **Ticker**: ONGC.NS
- **Fields Used**: Date, Open, High, Low, Close, adjclose ,Volume

---------------------------------------------------------------------------------------------------------
## 🛠️ Tools & Libraries Used
- Python (Pandas, Matplotlib, Seaborn)
- Jupyter Notebook
- CSV File Handling

---------------------------------------------------------------------------------------------------------
## 📌 Objectives

- Fetch ONGC stock data from Kaggle
- Clean and preprocess the dataset
- Analyze trends in Open, High, Low, Close ,adjclose ,and Volume
- Plot various graphs to visualize insights
- Create a correlation heatmap between numerical features

---------------------------------------------------------------------------------------------------------
## 📊 Key Features

- ✔ Data cleaning using forward-fill and backward-fill techniques
- ✔ Dropping irrelevant or highly-null columns
- ✔ Handling missing values
- ✔ Visualizing histogram + kde for stock price movement
- ✔ Heatmap to understand correlation between features

---------------------------------------------------------------------------------------------------------
## 📈 Sample Visualizations

- ![Heatmap](ONGC_Stock_price_analysis_project_by_python/Plots/Correlation_matrix.png)
- ![Histogram + kde](ONGC_Stock_price_analysis_project_by_python/Plots/open_distribution.png)
- ![Histogram + kde](ONGC_Stock_price_analysis_project_by_python/Plots/High_distribution.png)
- ![Histogram + kde](ONGC_Stock_price_analysis_project_by_python/Plots/low_distribution.png)
- ![Histogram + kde](ONGC_Stock_price_analysis_project_by_python/Plots/Close_distribution.png)
- ![Histogram + kde](ONGC_Stock_price_analysis_project_by_python/Plots/adjclose_distribution.png)
- ![Histogram + kde](ONGC_Stock_price_analysis_project_by_python/Plots/volume_distribution.png)

---------------------------------------------------------------------------------------------------------
## 🗂️ Project Structure

```bash
📁 ONGC_Stock_price_analysis_project_by_python
│
├── ONGC_NS_Stock_Raw_Data.csv			# Raw CSV file (Downloaded)
├── ONGC Stock price analysis project.ipynb	# Python jupyter notebook 
├── ONGC_NS_Stock_Cleaned_Data.csv		# Cleaned CSV file (Exported)
├── Plots					# All graph  
└── README.md					# This file 

---------------------------------------------------------------------------------------------------------
## 🚀 How to Run

1. Install dependencies:
   ```bash
   pip install pandas matplotlib seaborn 
   

2. Run the Jupyter Notebook:
   ```bash
   jupyter notebook
   

3. Open the "ONGC Stock price analysis project.ipynb" file.

---------------------------------------------------------------------------------------------------------
## 📌 Future Scope

- Add predictive modeling (e.g., Linear Regression, ARIMA)
- Build interactive dashboards using Power BI or Tableau
- Automate the data fetch to analyze real-time trends

---------------------------------------------------------------------------------------------------------
## 🧠 Learnings

- Data cleaning and preprocessing techniques
- How to handle stock time-series data
- Visual analytics for financial datasets
- Importance of correlation analysis in finance

---------------------------------------------------------------------------------------------------------
## 👤 Author
**Mohd Hussain Khan**  
MSc. Data Science | Data Nerd | Data Scientist, Data Analyst, ML, AI in progress

## 📌 License
This project is open for learning and demonstration purposes only.
