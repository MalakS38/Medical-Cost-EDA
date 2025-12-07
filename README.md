# Medical Cost Exploratory Data Analysis (EDA)
Analyzing the Medical Cost dataset to explore factors affecting insurance charges

**Goal:**  
Explore the "Medical Cost Personal Dataset" to understand variable distributions, relationships with `charges` (medical costs billed), and prepare insights for modeling.

**Dataset:**  
[Medical Cost Personal Dataset on Kaggle](https://www.kaggle.com/datasets/mirichoi0218/insurance)

**Notebook Overview:**  
1. **Load Data & Initial Checks** – inspected columns, data types, summary statistics.  
2. **Data Cleaning & Transformations** – handled missing values, duplicates and converted categorical variables to numeric.  
3. **Exploratory Data Analysis (EDA)**  
   - Univariate analysis: distribution plots for all features.  
   - Bivariate analysis: how features relate to `charges`.  
4. **Correlation Analysis** – correlation matrix for all features.  
5. **Conclusions** – summarized findings.

**Key Insights:**  
- Major drivers of `charges`: `smoker`, `age`, `bmi`.  
- `bmi` roughly normal; `charges` is right-skewed.  
- Strong positive correlation between `smoker` status and `charges`.






**Credits:**  
- Dataset source: [Kaggle](https://www.kaggle.com/datasets/mirichoi0218/insurance)  
- Tutorial and guidance: **Data Science with Onur**
