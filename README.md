Striker Performance Analysis

This project analyzes football striker performance data using Python and a variety of data science techniques. The goal is to clean, explore, and model the dataset to extract meaningful insights into player performance.

Key Steps

1. Data Preparation
   i). Loaded data from Excel (Strikers_performance.xlsx).
  ii). Handled missing values using median imputation.
 iii). Encoded categorical features with LabelEncoder.
  iv). Standardized numerical features for fair comparison.

2. Exploratory Data Analysis (EDA)
   i). Used pandas, matplotlib, and seaborn for visualization.
  ii). Checked distribution, correlations and performance metrics.
 iii). Tested statistical assumptions (ANOVA, Shapiro-Wilk, Levene's test).

3. Clustering & Segmentation
   i). Applied K-Means clustering to group strikers based on performance attributes.
  ii). Standardized input features for robust clustering.
 iii). Visualized cluster groupings for interpretation.

4. Predictive Modeling
   i). Built a Logistic Regression model to predict striker poerformance outcomes.
  ii). Evaluated results with accuracy score and confusion matrix.

Tools and Libraries

1. Data Handling: pandas, numpy.
2. Visualization: matplotlib, seaborn.
3. statistics: scipy, statsmodels.
4. Machine Learning: scikit-learn.

Results

1. Identified key attributes influencing striker success.
2. Grouped players into meaningful performance clusters.
3. Built a predictive model to assess striker effectiveness.
