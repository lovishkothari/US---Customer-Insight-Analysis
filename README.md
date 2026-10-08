# US Customer Insights Analysis | Python

##  Project Overview

This project analyzes **10,675 customer records** representing approximately **1,000 unique customers** to understand customer demographics, spending behavior, engagement patterns, and relationships between customer characteristics.

The analysis uses **Python, Pandas, NumPy, Matplotlib, Seaborn, and statistical hypothesis testing** to generate data-driven business insights.

---

##  Project Objectives

- Understand customer demographics and characteristics
- Analyze monthly customer spending behavior
- Explore customer activity and engagement patterns
- Identify relationships between customer attributes
- Perform statistical hypothesis testing
- Generate actionable business insights
- Identify useful variables for customer segmentation

---

##  Dataset Information

The dataset contains the following major attributes:

- `CustomerID`
- `Name`
- `State`
- `Education`
- `Gender`
- `Age`
- `Married`
- `NumPets`
- `JoinDate`
- `TransactionDate`
- `MonthlySpend`
- `DaysSinceLastInteraction`

### Dataset Size

- **Records:** 10,675
- **Unique Customers:** Approximately 1,000
- **States:** 10
- **Gender Categories:** 3
- **Education Categories:** 5

---

##  Tools & Technologies

- **Python**
- **Pandas** – Data manipulation and analysis
- **NumPy** – Numerical analysis
- **Matplotlib** – Data visualization
- **Seaborn** – Statistical visualization
- **SciPy** – Statistical hypothesis testing
- **Google Colab / Jupyter Notebook**

---

##  Analysis Performed

### 1. Data Exploration

- Dataset loading
- Data type checking
- Unique-value analysis
- Missing-value checking
- Duplicate-value checking
- Descriptive statistics
- Distribution analysis

### 2. Exploratory Data Analysis

The project analyzes:

- Customer demographics
- Gender distribution
- Education distribution
- Marital status
- Age distribution
- State-wise customer distribution
- Monthly spending
- Customer activity
- Pet ownership patterns

### 3. Statistical Analysis

Several hypothesis tests were performed to understand relationships between customer characteristics.

| Hypothesis | Statistical Test | Result |
|---|---|---|
| Gender vs Monthly Spending | Independent T-Test | Not Significant |
| Education vs Monthly Spending | One-Way ANOVA | Not Significant |
| State vs Monthly Spending | One-Way ANOVA | Not Significant |
| Age vs Customer Activity | Pearson Correlation | Not Significant |
| Marital Status vs Pet Ownership | Chi-Square Test | Significant |

---

##  Key Statistical Findings

### Gender vs Spending

- **t-statistic:** 0.339
- **p-value:** 0.735

The result indicates no statistically significant difference in spending behavior between gender groups.

### Education vs Spending

- **F-statistic:** 0.229
- **p-value:** 0.922

Education level did not show a statistically significant influence on monthly spending.

### State vs Spending

- **F-statistic:** 1.118
- **p-value:** 0.346

Average monthly spending differences between states were not statistically significant.

### Age vs Customer Activity

- **Correlation coefficient:** -0.004
- **p-value:** 0.682

There is virtually no linear relationship between age and customer activity.

### Marital Status vs Pet Ownership

- **Chi-Square statistic:** 177.64
- **p-value:** < 0.001

A statistically significant association was found between marital status and pet ownership.

---

##  Customer Spending Insights

The analysis found:

- **Average Monthly Spend:** 331.61
- **Median Monthly Spend:** 282.11
- **Standard Deviation:** 225.80
- **Maximum Monthly Spend:** 1,740.42
- **Skewness:** 1.42

The positive skew indicates that most customers have moderate spending levels, while a smaller group of high-value customers spends considerably more.

Customers above the third quartile (**>$443.26**) represent approximately the top 25% of customers and form an important high-value segment.

---

##  Business Insights

### 1. Diverse Customer Base

The customer base is broadly distributed across gender, education, and marital-status categories.

**Recommendation:**  
Maintain inclusive marketing strategies instead of focusing on a single demographic group.

### 2. High-Value Customer Segment

A relatively small group of customers contributes substantially higher spending.

**Recommendation:**

- Premium memberships
- Loyalty programs
- Personalized offers
- Early-access promotions

### 3. Demographics Are Not Strong Spending Predictors

Gender, education, age, and state did not show statistically significant relationships with spending or activity in the tested relationships.

**Recommendation:**  
Focus more on behavioral and lifestyle characteristics for customer segmentation.

### 4. Lifestyle Factors Provide Useful Insights

Marital status and pet ownership showed a statistically significant association.

**Recommendation:**  
Use lifestyle characteristics to develop customer personas and personalized marketing strategies.

---

##  Final Conclusion

The analysis found that **only one of the five tested relationships was statistically significant:**

**Marital Status ↔ Pet Ownership**

The following relationships were not statistically significant:

- Gender ↔ Spending
- Education ↔ Spending
- State ↔ Spending
- Age ↔ Customer Activity

Overall, the findings suggest that **behavioral and lifestyle characteristics may provide more useful customer segmentation insights than traditional demographic variables** within this dataset.

The major opportunities identified are:

1. Retain high-spending customers
2. Improve customer re-engagement strategies
3. Use lifestyle variables for personalization
4. Strengthen lower-performing regions with targeted campaigns
5. Build data-driven marketing strategies

---

##  Project Files

```text
US-Customer-Insights-Analysis/
│
├── US_Customer_Insights_Analysis.ipynb
├── US_Customer_Insights_Dataset.csv
└── README.md
