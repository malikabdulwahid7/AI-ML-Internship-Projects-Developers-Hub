# AI/ML Internship Tasks

This repository contains AI/ML internship tasks completed as part of my training. Each task demonstrates data handling, visualization, and modeling skills using Python and popular libraries like pandas, seaborn, matplotlib, scikit-learn, and yfinance.

---

## Task 1: Exploring and Visualizing a Simple Dataset

**Objective:**  
Learn how to load, inspect, and visualize a dataset to understand data trends and distributions.

**Dataset:**  
[Iris Dataset](https://archive.ics.uci.edu/ml/datasets/iris) (CSV format, can be loaded via seaborn or downloaded)

**Instructions / Approach:**  
- Load the dataset using pandas.  
- Print the shape, column names, and the first few rows using `.head()`.  
- Use `.info()` and `.describe()` for summary statistics.  
- Visualize the dataset:  
  - Scatter plots to show relationships between features  
  - Histograms for value distributions  
  - Box plots to identify outliers  
- Libraries used: `matplotlib`, `seaborn`

**Skills Developed:**  
- Data loading and inspection using pandas  
- Descriptive statistics and data exploration  
- Basic plotting and visualization

---

## Task 2: Predict Future Stock Prices (Short-Term)

**Objective:**  
Use historical stock data to predict the next day's closing price.

**Dataset:**  
Stock market data from Yahoo Finance (retrieved using the `yfinance` Python library)

**Instructions / Approach:**  
- Select a stock (e.g., Apple, Tesla)  
- Load historical data using `yfinance`  
- Use features like Open, High, Low, and Volume to predict the next Close price  
- Train a **Linear Regression** or **Random Forest** model  
- Plot actual vs predicted closing prices for comparison

**Skills Developed:**  
- Time series data handling  
- Regression modeling  
- Data fetching using APIs (`yfinance`)  
- Plotting predictions vs real data

---

## Task 3: Heart Disease Prediction

**Objective:**  
Build a model to predict whether a person is at risk of heart disease based on their health data.

**Dataset:**  
[Heart Disease UCI Dataset](https://www.kaggle.com/datasets/ronitf/heart-disease-uci)

**Instructions / Approach:**  
- Clean the dataset (handle missing values if any)  
- Perform Exploratory Data Analysis (EDA) to understand trends  
- Train a classification model (**Logistic Regression** or **Decision Tree**)  
- Evaluate using metrics: accuracy, ROC curve, confusion matrix  
- Highlight important features affecting prediction

**Skills Developed:**  
- Binary classification  
- Medical data understanding and interpretation  
- Model evaluation using ROC-AUC and confusion matrix  
- Feature importance analysis

---

## Tools & Libraries Used
- Python 3.x  
- pandas, numpy  
- matplotlib, seaborn  
- scikit-learn  
- yfinance (for stock data)  

---

## Key Results & Findings
- **Task 1:** Explored Iris dataset; identified feature distributions and relationships between flower types.  
- **Task 2:** Achieved accurate short-term stock price predictions using regression models; visualized predictions vs actual prices.  
- **Task 3:** Built a predictive model for heart disease with evaluation metrics; identified key features impacting heart disease risk.
