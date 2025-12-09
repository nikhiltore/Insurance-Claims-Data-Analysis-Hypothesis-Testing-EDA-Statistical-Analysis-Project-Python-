**📌 Insurance Claims Analysis:**
This project performs a complete Exploratory Data Analysis (EDA) and Hypothesis Testing on insurance claim datasets. It covers data cleaning, feature engineering, visual analytics, and statistical validation.

**🔍 Project Overview**
Insurance companies process thousands of claims each month. This case study aims to analyze customer demographics, claim patterns, fraudulent behavior, and factors influencing the claim amount.
This project answers 20+ business and statistical questions including:
•	Which customer segments claim the most?
•	Is there a relationship between age group and segment?
•	Are claim amounts different for males vs. females?
•	Which age group has the highest fraudulent claims?
•	What is the month-wise trend of claims?
•	Do current claim amounts exceed the historical benchmark?

**🧹 Key Steps Performed**
**1. Data Cleaning & Preparation:**
•	Combined two datasets into a 360° customer-claim table
•	Audited datatypes and corrected mismatches
•	Converted claim amounts (removed $ and commas)
•	Imputed missing values using mean (numeric) and mode (categorical)
•	Removed duplicate customer entries (kept latest claim)
**2. Feature Engineering:**
•	Created police-report alert flag for unreported injury claims
•	Calculated customer age
•	Categorized customers into:
o	Children
o	Youth
o	Adults
o	Seniors
•	Extracted claim month and created trend variables
**3. Exploratory Data Analysis:**
•	Average claim by segment
•	Driver-related issues by state and age group
•	Fraud detection patterns
•	Monthly claim trends
•	Gender-wise and segment-wise claim distribution
**4. Visualization:**
Using Matplotlib and Seaborn:
•	Pie charts
•	Bar charts
•	Facet charts
•	Line charts (monthly trends)
**5. Statistical Hypothesis Testing:**
Performed using SciPy:
•	Two-sample t-test (male vs female claim amounts)
•	Chi-square test (age group vs segment)
•	One-sample t-test (current year claims vs 10,000 benchmark)
•	ANOVA (age groups vs claim amounts)
•	Correlation test (policies vs claim amount)

**📈 Key Insights**
•	Adults form the largest claimant group.
•	Driver-related issues vary by state and gender.
•	Fraudulent claims are highest among adults.
•	Monthly trend shows non-linear fluctuations in total claim amount.
•	Claim amounts differ statistically between age groups.

**🛠️ Tech Stack**
•	Python
•	NumPy
•	Pandas
•	Matplotlib
•	Seaborn
•	Scikit-Learn
•	SciPy

