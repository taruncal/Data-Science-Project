# Data-Science-Project
End-to-End Data science project featuring data preprocessing, exploratory data analysis, and machine learning modeling using Python.


PROJECT OVERVIEW

OBJECTIVE: Analyze e-commerce stakeholder interests, identify revenue drivers in marketing acquisition channels, and use predictive machine learning models to forecast customer spend behavior.
DATASET(Source): [https://www.kaggle.com/datasets/raziehghahartars/ecommerce]
TECH STACK: Python, Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn, Jupyter Notebook




 METHODOLOGY AND OVERVIEW (needs to be overviewed)

1. DATA PREPROCESSING & CLEANING: Cleaned Source Names (e.g. corrected spelling for "Instagram Campaign" and "Facebook Campaign").
Handled Data types, There is no missing or duplicate values and Standardized date-time formats.




2. EXPLORATORY DATA ANALYSIS (EDA): 
# Central Tendencies & IQR Outlier Analysis

Distribution Symmetry: Mean and median metrics across key variables (Total Purchase Amount: ~$2,725 , Customer Age: 44, NPS: 5) are tightly aligned, indicating uniform and symmetric distributions across the dataset.


OUTLIER DETECTION: Applying the 1.5x IQR RULE revealed zero outliers across demographic and transaction metrics (Price, Quantity, Spend, Age, NPS). The only column displaying outliers is Longitude (7,480 flagged points due to wide spatial coordinates).


Visualized continuous variables using distribution HISTOGRAMS and BOX PLOTS to confirm uniform data dispersion.


Feature Relationships & Correlations: Evaluated correlation heatmaps and bivariate scatter plots between customer age, product price, and total purchase amount to determine feature collinearity and linear dependency prior to model training.



3. MODEL TRAINING AND EVALUATION: Machine Learning Evaluation & Model Insights

Applied a Random Forest Classifier to predict customer spend tiers (Low vs High spenders) using demographic (Age, Gender) and engagement features (NPS, Product Category).

MODEL PERFORMANCE: Achieved an accuracy, precision, and recall of 50% across a 50,000-sample test set.

BUSINESS TAKEAWAY: Demographic and satisfaction parameters exhibit zero predictive power over customer spending behavior in this dataset, proving that purchasing power is completely uniform across customer segments.





RESULTS AND KEY INSIGHTS

KEY INSIGHT 1

REVENUE AND SPENDING DISTRIBUTION: The Mean Total purchase amount of $2,725 and uniform spread across customer demographics indicate that spending behavior is consistent across age groups, showing no major high-value skew.

KEY INSIGHT 2

FEATURE PREDICTIBILITY: Because standard variables (price, quantity, age, NPS) displayed zero extreme outliers, machine learning regression models relied heavily on encoded categorical interactions (like product categories and channels) to predict total spend.





ACQUISITION DOMINANCE: Instagram Campaign emerged as the Top-Performing acquisition channel, generating the highest user volume (70170 users) and accounting for the majority of traffic share.

DEMOGRAPHIC & GEOGRAPHICAL CONCENTRATION: The User Base exhibits a concentrated demographic spread with key geographic hotspots heavily clustered in Top-Performing States (Such as New York(76785 Customers) and California(36518 Customers)).





CONCLUSION AND FUTURE SCOPE
SUMMARY: Successfully Cleaned 250,000+ Records, Resolved formatting errors, and extracted vital demographic and acquisition metrics but no essential insights was extracted as it was all part of the synthetic data





























