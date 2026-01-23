# Exploratory Data Analysis of Google Play Store Apps

## 📌 Project Overview
This project analyzes the Google Play Store dataset to discover key trends in the Android app market. The goal is to provide actionable insights for developers by understanding which categories are most popular, how ratings are distributed, and what drives user installations.

## 📂 Dataset
The dataset consists of approximately 10,000 apps scraped from the Google Play Store. 
**Key Features:** `App`, `Category`, `Rating`, `Reviews`, `Size`, `Installs`, `Price`, `Content Rating`, and `Genres`.

## Technologies Used
* **Python** (Data Analysis)
* **Pandas** (Data Manipulation & Cleaning)
* **NumPy** (Numerical Operations)
* **Matplotlib & Seaborn** (Data Visualization)

## 📊 Key Steps Performed
1.  **Data Cleaning**: 
    * Removed duplicate records and erroneous rows.
    * Converted data types for `Reviews`, `Size`, `Installs`, and `Price` into numeric formats for analysis.
    * Handled special characters (e.g., converting '19M' to bytes, removing '$' and '+').
2.  **Handling Missing Values**:
    * Imputed missing `Rating` values using the median rating of each specific `Category` to ensure accuracy.
    * Dropped rows with negligible missing data (less than 1%) to keep the dataset clean.
3.  **Exploratory Data Analysis (EDA)**:
    * Identified the top categories by number of apps and installations.
    * Analyzed the correlation between user reviews and app popularity.
    * Visualized the distribution of ratings across the market.
