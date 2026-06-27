# Data Science Projects

Welcome to the **Data Science Projects** repository! This collection showcases various data science projects demonstrating practical applications of machine learning, statistical analysis, data vis[...] 

## 📚 Repository Overview

This repository contains a curated set of data science projects built using Python and Jupyter Notebooks. Each project focuses on solving real-world problems through data analysis, exploratory data[...] 

## 🎯 What You'll Find Here

- **Exploratory Data Analysis (EDA)** - Comprehensive data exploration and visualization
- **Data Preprocessing** - Cleaning, transformation, and preparation techniques
- **Machine Learning Models** - Classification, regression, clustering, and more
- **Statistical Analysis** - Hypothesis testing and statistical inference
- **Data Visualization** - Interactive and informative visualizations
- **Real-world Datasets** - Projects using authentic, practical data
- **Time Series Forecasting** - Stock price prediction and trend analysis

## 💻 Tech Stack

- **Language**: Python 3
- **Notebooks**: Jupyter Notebook
- **Libraries**:
  - `pandas` - Data manipulation and analysis
  - `numpy` - Numerical computing
  - `scikit-learn` - Machine learning
  - `matplotlib` & `seaborn` - Data visualization
  - `plotly` - Interactive visualizations
  - `xgboost` - Gradient boosting models
  - `statsmodels` - Time series analysis and ARIMA
  - `yfinance` - Financial data retrieval

## 📁 Project Structure

```
Data-Science-Projects/
├── README.md
├── Analysing-pharmaceutical-sales-data/
│   ├── analysing_pharmaceutical_sales.ipynb
│   └── data/
├── Microsoft_Stock_prediction.ipynb
├── corporate _ai_adoption (3).ipynb
└── ...
```

## 🚀 Getting Started

### Prerequisites

Ensure you have Python installed. You'll need:
- Python 3.7+
- Jupyter Notebook or JupyterLab

### Installation

1. Clone this repository:
```bash
git clone https://github.com/Narendr1a/Data-Science-Projects.git
cd Data-Science-Projects
```

2. Install required packages:
```bash
pip install pandas numpy scikit-learn matplotlib seaborn plotly statsmodels yfinance
```

3. Launch Jupyter Notebook:
```bash
jupyter notebook
```

## 📖 How to Use

1. Navigate to any project folder or open a notebook in the repository root
2. Open the `.ipynb` file in Jupyter Notebook
3. Run cells sequentially to see the analysis and results
4. Modify and experiment with the code as needed

## 📊 Projects

### 1. **Corporate AI Adoption & Revenue Impact Prediction**

An end-to-end data science project evaluating organizational AI readiness and predicting its direct impact on corporate revenue.

**Key Features:**
- Data Ingestion and cleaning
- Exploratory Data Analysis (EDA) with visualizations
- Feature Preprocessing and scaling
- Multiple regression algorithms (Linear Regression, XGBoost, Gradient Boosting)
- Hyperparameter optimization
- Model evaluation and comparison

**Tech Stack:** Pandas, NumPy, Scikit-learn, XGBoost, Matplotlib, Seaborn

**Insights:**
- Identified top 3 factors driving AI-related revenue growth
- Compared performance between linear and non-linear models

---

### 2. **Microsoft Stock Price Prediction** 📈

A time series forecasting project to predict Microsoft (MSFT) stock prices using ARIMA (AutoRegressive Integrated Moving Average) models.

**Project Overview:**
This project analyzes Microsoft's historical stock data and builds an ARIMA model to forecast future stock prices. The project demonstrates the application of statistical time series methods in f[...]

**Key Features:**
- **Data Collection:** Fetching historical MSFT stock data using yfinance
- **Exploratory Data Analysis:** Analyzing price trends, volatility, and temporal patterns
- **Data Preprocessing:** 
  - Time series decomposition
  - Stationarity testing (ADF test)
  - Differencing for stationarity
- **ARIMA Model Development:**
  - Parameter tuning (p, d, q)
  - Model fitting on historical data
  - Forecasting future stock prices
- **Evaluation Metrics:**
  - **RMSE (Root Mean Square Error)** - Measures prediction accuracy with emphasis on larger errors
  - **MAE (Mean Absolute Error)** - Average absolute deviation of predictions from actual values
- **Visualization:** 
  - Historical price trends
  - Forecasted vs actual prices
  - Residual analysis
  - ACF/PACF plots for parameter identification

**Tech Stack:** Pandas, NumPy, Scikit-learn, statsmodels, yfinance, Matplotlib, Seaborn

**Key Insights:**
- Identified seasonal patterns in Microsoft stock prices
- ARIMA model captures temporal dependencies for stock price forecasting
- Evaluated model performance using RMSE and MAE metrics
- Residual analysis confirms model adequacy

---

### 3. **Analysing Pharmaceutical Sales Data** 💊

A data analysis project focused on pharmaceutical sales data to uncover sales patterns, top-selling products, and regional performance. The notebook provides EDA, data cleaning, feature engineeri[...]

**Project Overview:**
This project analyzes historical pharmaceutical sales data (sales by product, region, and time) and provides insights into drivers of sales, seasonality, and product performance. It includes repr[...]

**Key Features:**
- Data ingestion and cleaning (handling missing values, data types)
- Exploratory Data Analysis (sales distribution, top products, regional breakdown)
- Time series decomposition to identify seasonality/trends
- Feature engineering (rolling averages, lag features, promotion flags)
- Baseline forecasting models (moving average, simple regressors)
- Visualizations: sales trends, heatmaps, product comparisons

**Tech Stack:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn

**How to run:**
1. Open `Analysing-pharmaceutical-sales-data/analysing_pharmaceutical_sales.ipynb` in Jupyter
2. Place dataset files (if any) inside the `Analysing-pharmaceutical-sales-data/data/` folder
3. Run cells sequentially; adjust file paths as necessary

**Insights (example):**
- Top 5 products contributing to X% of revenue
- Regional sales concentration and opportunities for growth
- Seasonal patterns and recommended inventory adjustments

---

## 📈 Data Science Workflow

Each project follows a structured, step-by-step analytical approach:

1. **Data Collection/Ingestion** - Acquiring and loading datasets
2. **Exploratory Data Analysis (EDA)** - Understanding data patterns and distributions
3. **Data Preprocessing** - Cleaning, handling missing values, transformations
4. **Feature Engineering** - Creating and selecting relevant features
5. **Model Training** - Implementing and fitting models
6. **Model Evaluation** - Assessing performance metrics (RMSE, MAE, R², etc.)
7. **Visualization & Insights** - Creating interpretable visualizations
8. **Forecasting/Prediction** - Making predictions on new data

## 🤝 Contributing

Contributions are welcome! To contribute:

1. Fork the repository
2. Create a new branch (`git checkout -b feature/new-project`)
3. Add your project or improvements
4. Commit your changes (`git commit -m 'Add new project'`)
5. Push to the branch (`git push origin feature/new-project`)
6. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 🤵 Author

**Narendr1a**

## 📧 Contact & Support

For questions, suggestions, or collaborations, feel free to:
- Open an issue on GitHub
- Reach out via email
- Check out my GitHub profile for more projects

## 🔗 Resources

- [Scikit-learn Documentation](https://scikit-learn.org/)
- [Pandas Documentation](https://pandas.pydata.org/)
- [Jupyter Notebook Guide](https://jupyter.org/)
- [Statsmodels Documentation](https://www.statsmodels.org/)
- [ARIMA Time Series Forecasting](https://www.statsmodels.org/stable/tsa.html)
- [yfinance Documentation](https://github.com/ranaroussi/yfinance)
- [Data Science Best Practices](https://www.kaggle.com/)
- [Time Series Analysis Guide](https://machinelearningmastery.com/)

---

**Happy Learning and Exploring Data! 🎓📊**
