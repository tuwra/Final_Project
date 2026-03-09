# 🚗 Used Car Price Analysis (Craigslist Dataset)

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![Pandas](https://img.shields.io/badge/Library-Pandas-orange.svg)
![Matplotlib](https://img.shields.io/badge/Library-Matplotlib-green.svg)

## 📝 Project Overview
This project aims to analyze a massive dataset of used cars from Craigslist to understand the factors influencing vehicle prices. The analysis covers the entire data science pipeline, from cleaning and preprocessing to feature engineering and exploratory data analysis (EDA).

## 📂 Project Structure
* `01_data_cleaning.ipynb`: Handling missing values, outliers, and duplicates.
* `02_feature_engineering.ipynb`: Creating new features like "Car Age".
* `03_eda_visualization.ipynb`: Visualizing price distributions and correlations.
* `04_math_operations.ipynb`: Statistical calculations and numerical analysis.
* `report.md`: Detailed documentation of the project.

## 🛠️ Data Pipeline & Methodology

### 1. Data Cleaning
* Removed rows with missing critical values (Price, Mileage).
* Filtered out unrealistic data, such as zero-priced cars or impossible mileage.
* Ensured correct data types for mathematical operations.
* Deleted duplicate records to ensure model integrity.

### 2. Feature Engineering
* **Car Age Calculation:** Derived by subtracting the manufacture year from the current year (2026) to better understand depreciation.

### 3. Exploratory Data Analysis (EDA)
* **Price Distribution:** Used histograms to identify that most cars fall within the average price range.
* **Correlation Analysis:** Used scatter plots to confirm that higher mileage and older age directly lead to lower prices.

## 📊 Key Findings
* **Age vs. Price:** Newer cars consistently command higher prices.
* **Mileage Impact:** Increased kilometers traveled is a primary factor in price reduction.
* **Brand Value:** Certain manufacturers retain their resale value better than others over time.

## 🚀 Future Work
* Incorporate more features like car color and demand trends.
* Build a Machine Learning model to predict car prices based on input characteristics.
* Add detailed condition metrics (engine modifications, paint status, etc.).

## 🔗 Data Source
The data used in this project is sourced from [Kaggle - Craigslist Cars/Trucks Data](https://www.kaggle.com/datasets/austinreese/craigslist-carstrucks-data).

---
*Created as part of a Final Data Analysis Project.*
