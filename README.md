# Medical Cost Exploratory Data Analysis (EDA)
Analyzing the Medical Cost dataset to explore factors affecting insurance charges


**Dataset:**  
[Medical Cost Personal Dataset on Kaggle](https://www.kaggle.com/datasets/mirichoi0218/insurance)

---

## Project Overview

The goal of this project is to **analyze and prepare the dataset for high-quality insights** by:

- Checking and cleaning the data  
- Converting categorical features to numeric for analysis  
- Exploring variable distributions and relationships with `charges`  
- Identifying correlations and key drivers of medical costs  
- Preparing the dataset for potential modeling  

---
## Tasks Performed

### 1. Loaded and inspected the dataset
Checked the first rows, column names, data types, and summary statistics to understand the structure.

### 2. Checked for missing values and duplicates
Verified whether any columns contained null values and decided how to handle them.

### 3. Cleaned and transformed data
- Converted categorical columns (`sex`, `smoker`, `region`) to numeric using label encoding  
- Standardized formats and ensured data consistency  

### 4. Univariate analysis
Plotted distributions of numeric and categorical variables to check skewness, outliers, and patterns.

### 5. Bivariate analysis
Compared features with `charges` to identify relationships using boxplots and scatterplots.

### 6. Correlation analysis
Calculated pairwise correlations to see which features are strongly related to `charges` and to each other.



---

## Key Insights

- **Major drivers of charges:** `smoker`, `age`, `bmi`  
- **Distributions:** `bmi` is roughly normal; `charges` is right-skewed  
- Correlation analysis helps identify which variables may be most useful in predictive modeling  

---


.

**Credits:**  
- Dataset source: [Kaggle](https://www.kaggle.com/datasets/mirichoi0218/insurance)  
- Guidance: **Data Science with Onur**
