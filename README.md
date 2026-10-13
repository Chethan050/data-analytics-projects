# Data Analytics Projects

## Project Structure

### 1. SQL Data Analysis on Civic Datasets
**File:** `01-sql-civic-data-analysis.ipynb`

Loaded Chicago census, public schools, and crime datasets into a SQLite database and wrote SQL queries to answer a series of analytical questions. Covered aggregation, filtering, sorting/ranking, and correlated subqueries — including identifying the community areas with the highest hardship index and highest crime rates.

**Tools:** Python, SQLite, SQL

### 2. Stock Data Extraction & Revenue Dashboard
**File:** `02-stock-revenue-dashboard.ipynb`

Extracted historical stock data using the `yfinance` API and web-scraped quarterly revenue data using `BeautifulSoup`. Cleaned and structured the revenue data, then built comparative visualizations plotting stock price against revenue over time for two companies.

**Tools:** Python, yfinance, BeautifulSoup, requests, Matplotlib, pandas

### 3. Classification Model Comparison
**File:** `03-classification-model-comparison.ipynb`

Completed as part of a data science course during my Master's program (Scientific Instrumentation, 2nd semester). Explored and preprocessed a dataset, checked class balance, and applied Min-Max scaling. Trained and evaluated two classification models — SVM and Decision Tree — and compared their performance using accuracy scores, classification reports, and confusion matrices.

**Tools:** Python, pandas, scikit-learn, NumPy

### 4. Automobile Sales Analysis Dashboard
**Files:** `04-automobile-sales-dashboard/automobile_sales_visualizations.ipynb`, `04-automobile-sales-dashboard/automobile_sales_dashboard.py`

Analyzed historical automobile sales data to understand how sales patterns change during economic recessions. Built static visualizations (Matplotlib, Seaborn, Folium) covering sales trends by year, advertising spend vs. sales, sales by vehicle type, GDP comparison during recession vs. non-recession, seasonality effects, consumer confidence, and a map of sales by office location. Also built an interactive Plotly Dash dashboard where the user selects "Yearly Statistics" or "Recession Period Statistics" and a year, and the relevant charts render dynamically.

**Tools:** Python, Pandas, NumPy, Matplotlib, Seaborn, Folium, Plotly, Dash

### 5. House Sales Price Prediction (King County, USA)
**File:** `05-house-price-prediction.ipynb`

Analyzed and modeled ~21,600 house sales in King County (Seattle area, 2014–2015). Cleaned missing bedroom/bathroom values, explored price correlations (waterfront view, square footage, grade), and built regression models — starting with single-feature linear regression, expanding to multi-feature regression, then a scaling + polynomial features pipeline, and finally Ridge regression with polynomial transforms, evaluated by R² on a held-out test set.

**Tools:** Python, pandas, NumPy, seaborn, scikit-learn (Linear Regression, Ridge, Pipeline, PolynomialFeatures)

### 6. Medical Insurance Cost Analysis
**File:** `06-insurance-cost-analysis.ipynb`

Analyzed a medical insurance dataset (~2,770 records) to understand what drives annual insurance charges. Cleaned missing age and smoker values, ran EDA (charges vs. BMI, smoker status, correlation matrix) and found smoking status to be the dominant factor. Built single-variable and multi-variable linear regression models, a scaling + polynomial features pipeline, and Ridge regression with polynomial transforms evaluated on a held-out test set.

**Tools:** Python, pandas, NumPy, seaborn, Matplotlib, scikit-learn (Linear Regression, Ridge, Pipeline, PolynomialFeatures)

## About

These projects were built to develop practical, applied data analysis skills — from database querying and data cleaning to visualization and predictive modeling. Each notebook includes the full workflow from raw data to final output.

**Author:** Chethan Sreekar Mandapati
[LinkedIn](https://www.linkedin.com/in/chethan-sreekar-mandapati/)
