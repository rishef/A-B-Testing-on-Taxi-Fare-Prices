Problem Statement:
The project aims to analyze and compare taxi fare prices using A/B testing.
The objective is to determine whether a new pricing model significantly affects fare amounts.
Objective:
Conduct exploratory data analysis (EDA) on taxi fare data.
Clean and preprocess the dataset by removing unnecessary columns, duplicates, and missing values.
Convert relevant columns into appropriate data types.
Perform A/B testing to statistically compare two groups of fare prices.
Implementation Steps:
Data Loading & Cleaning:

Load the dataset containing taxi trip fare details.
Drop unnecessary columns such as VendorID, RatecodeID, and others.
Remove duplicate records and handle missing values.
Convert categorical or numerical columns into proper data types.
Exploratory Data Analysis (EDA):

Check the distribution of fare_amount using histograms and boxplots.
Analyze passenger_count, payment_type, and other factors affecting fare pricing.
Identify anomalies or outliers in the dataset.
A/B Testing Implementation:

Define Control and Test Groups: Split the dataset into two groups based on a variable (e.g., traditional fare vs. new pricing model).
Hypothesis Testing:
Null Hypothesis (H₀): There is no significant difference in fare prices between the two groups.
Alternative Hypothesis (H₁): There is a significant difference in fare prices between the two groups.
Statistical Test Selection:
Use t-test (if the data is normally distributed) or Mann-Whitney U test (if non-normal).
Check p-value:
If p-value < 0.05, reject the null hypothesis → New pricing model has a significant effect.
If p-value ≥ 0.05, fail to reject the null hypothesis → No significant effect of the new pricing model.
Statistical Interpretation & Business Decision:

Based on the results, decide whether to adopt the new pricing model.
If the new pricing leads to increased revenue or customer affordability, implement it.
