### "Impact of Financial Satisfaction on Overall Happiness: An Analysis Using World Values Survey (WVS) Data"

## **1. Project Overview**
This project investigates the relationship between **financial satisfaction** and **overall happiness** using data from the **World Values Survey (WVS) Wave 7 (2017-2022)**. The study aims to determine whether financial stability significantly impacts subjective well-being while controlling for other socio-economic and demographic factors.

## **2. Dataset Description**
The dataset used in this analysis is a subset of the **World Values Survey (WVS) Wave 7**, which consists of survey responses collected from multiple countries worldwide between **2017 and 2022**.

- **Source:** World Values Survey (www.worldvaluessurvey.org)
- **Years Covered:** 2017-2022
- **File Format:** CSV
- **Number of Respondents:** 97,220
- **Survey Method:** Face-to-face and online interviews

### **Dataset Files**
- **`WVS_subset.csv`** → Contains survey responses.
- **`WVS_codebook.pdf`** → Provides variable definitions and coding structure.

## **3. Research Question**
> **How does financial satisfaction impact overall happiness?**

To answer this question, we analyze self-reported happiness and financial satisfaction while accounting for additional socio-economic variables that may influence happiness.

## **4. Key Variables**
This analysis primarily focuses on **Q46 (Happiness) and Q50 (Financial Satisfaction)** but includes additional variables for a more comprehensive understanding.

### **Main Variables**
- **Q46 - Happiness:** Measures subjective happiness (Scale: 1 = Very happy, 4 = Not at all happy).
- **Q50 - Financial Satisfaction:** Measures financial well-being (Scale: 1 = Completely dissatisfied, 10 = Completely satisfied).

### **Additional Control Variables**
To improve the accuracy of our analysis, we include variables such as:
- **Q49 - Life Satisfaction** (1-10 scale)
- **Q47 - Subjective Health** (1-5 scale)
- **Q48 - Freedom of Choice and Control** (1-10 scale)
- **Q260 - Age** (Numeric)
- **Q261 - Gender** (1 = Male, 2 = Female)
- **Q262 - Marital Status** (1-5 categories)
- **Q263 - Education Level** (1-8 scale)
- **Q264 - Employment Status** (1-6 categories)
- **Q265 - Household Income** (1-10 scale)

## **5. Descriptive Statistics**
To understand the dataset, we computed descriptive statistics for the five most important variables.

| Variable | Count | Mean | Std Dev | Min | 25% | Median | 75% | Max |
|----------|--------|------|---------|-----|-----|--------|-----|-----|
| **Q46 - Happiness** | 97,220 | 1.83 | 0.78 | -5 | 1 | 2 | 2 | 4 |
| **Q50 - Financial Satisfaction** | 97,220 | 6.16 | 2.51 | -5 | 5 | 6 | 8 | 10 |
| **Q49 - Life Satisfaction** | 97,220 | 7.01 | 2.34 | -5 | 6 | 7 | 9 | 10 |
| **Q47 - Health Status** | 97,220 | 2.18 | 0.92 | -5 | 2 | 2 | 3 | 5 |
| **Q48 - Freedom of Choice** | 97,220 | 7.13 | 2.41 | -5 | 6 | 7 | 9 | 10 |

> **Note:** Negative values (-5) likely indicate missing or non-applicable responses.

## **6. Methodology**
### **Step 1: Data Cleaning & Preprocessing**
- Handle missing values (-5 values will be treated as NaN).
- Convert categorical variables into numerical formats where necessary.

### **Step 2: Exploratory Data Analysis (EDA)**
- Compute correlations between **financial satisfaction (Q50) and happiness (Q46)**.
- Generate visualizations (scatter plots, box plots) to understand distributions and patterns.

### **Step 3: Regression Analysis**
- **Linear Regression:** Examine the direct effect of financial satisfaction on happiness.
- **Multivariate Regression:** Control for demographic factors (age, gender, employment, etc.) to check robustness.
- **Categorical Analysis:** Compare happiness across different financial satisfaction levels.

### **Step 4: Visualization**
- **Scatter Plot:** Show the relationship between Q50 (financial satisfaction) and Q46 (happiness).
- **Box Plot:** Compare happiness levels across financial satisfaction categories.
- **Bar Charts:** Display distributions of key variables.

## **7. Expected Findings & Hypothesis**
We expect a **positive correlation** between financial satisfaction and happiness, meaning:
- Higher financial satisfaction (Q50) should be associated with higher happiness levels (Q46).
- Other factors like health, employment, and personal freedom may moderate this relationship.

## **8. Next Steps**
✅ **1. Data Cleaning & Handling Missing Values**  
✅ **2. Exploratory Data Analysis (EDA) & Visualizations**  
✅ **3. Correlation & Regression Analysis**  
✅ **4. Interpretation of Results & Hypothesis Testing**  
✅ **5. Documentation & Reporting**  

## **9. Technologies Used**
- **Programming Language:** Python (pandas, matplotlib, seaborn, statsmodels, scikit-learn)
- **Data Processing:** NumPy, pandas
- **Statistical Analysis:** SciPy, Statsmodels
- **Visualization:** Matplotlib, Seaborn

## **10. Author & Contact Information**
- **Author:** [Your Name]
- **Email:** [Your Email]
- **Institution:** [Your Organization/University]

## **11. Acknowledgments**
Special thanks to the **World Values Survey Association** for providing this valuable dataset.

---

### 🎯 **Goal: Understand how financial satisfaction influences happiness and what other factors play a role in shaping subjective well-being.**

**📌 If you have any questions or suggestions, feel free to reach out! 🚀**


