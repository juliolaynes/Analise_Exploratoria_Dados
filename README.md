# Credit Scoring: Exploratory Data Analysis & Preprocessing Pipeline
This project focuses on building a robust data pipeline to analyze and preprocess customer data fot a Credit Scoring system. The core objective is to evaluate credit risk, helping to determine which profiles ar eligible for higher credit limits and which presejt a higher risk of default.

## Business Problem & Objectives 
In the financial sector, accurately assessing credit risk is crucial to balance profitability and default rates. This repository contains the complete foundation od a data science project:
*Understand the socio-economic and behavioral factors that influence credit scores.
*Perform univariate and bivariate analyses to uncover hidden patterns in data distributions.
*Clean, transform and prepare the dataset addressing real-world issues like missing values and highly imbalanced classes.

## Data Pipeline & Methodology
The project is structured into two main phases using Python:

### 1. Exploratory Data Analysis (EDA)
* **Univariate Analysis:** Inspecting individual vairiables (income, age, education) to understand their distribution and detect outliers using pandas.
* **Bivariate Analysis:** Crossing applicant features with their credit history to identify strong correlations and risk indicators.
* **Interactive Data Visualization:** Utilized **Plotly** to build dynamic, interactive charts, allowing for deeper, deep-dive isnpection of specific data poits and distributions.

### 2. Data Preprocessing (Preparation for Machine Learning)
* **Data Cleaning:** Handling missing records and incosistent strutural data using Pandas and NumPy.
* **Feature Encoding & Scaling:** Preparing categorical variables and normalizing numerical scales using Scikit-Learn.
* **Class Imbalance Handling:** Addressing the natural disproportion between good and bad payers to ensure future models don't biasedly favor the majority class.
* **Train/Test Split:** Partitioned the dataset into training and testing subsets using Scikit-Learn to ensure an unbiased evaluation of future machine learning models and prevent data leakage.

## Technologies Used 
* **Python** (Core workflow)
* **Pandas** (Data manipulation, profiling and cleaning)
* **Scikit-Learn** (Preprocessing transformers, LabelEncoder, OneHotEncoder and Model Selection)
* **Plotly** (Interactive data visualization and dynamic plotting)
* **Matplotlib & Seaborn** (Static data visualization)

## Key Insights & Business Findings 
The Exploratory Data Analysis revealed critical behavioral and demographic patterns regarding credit risk:
* **Risk Indicators:** Certain features showed a strong correlation with higher credit risk, allowing the business to flag profiles that should receive conservative initial limits.
* **High-Eligibility Profiles:** Clear socio-economic indicators were identified within the "good payers" class, mapping out the ideal target audience for credit limit expansions.
* **Data Readiness:** Through the combined pipeline of 'LabelEncoder' and 'OneHotEncoder', the final dataset was completely transformed from raw, messy text into a clean, balanced and estructured format ready for Machine Learning modeling.
