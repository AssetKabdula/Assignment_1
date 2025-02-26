## **1. Key Information on the Dataset**
The dataset used is from the **World Values Survey (WVS) Wave 7 (2017-2022)**, which includes responses from individuals across multiple countries on various socio-economic and cultural topics between **2017 and 2022**. The survey is designed to provide insights into people's beliefs, values, economic conditions, and overall well-being.

- **Source:** World Values Survey (www.worldvaluessurvey.org)
- **Years Covered:** 2017-2022
- **File Format:** CSV
- **Number of Respondents:** 97,220
- **Survey Method:** Face-to-face and online interviews

### **2. Dataset Files**
- **`WVS_subset.csv`** → Contains survey responses.
- **`WVS_codebook.pdf`** → Provides variable definitions and coding structure.

## **Research Question**
> **How does financial satisfaction impact overall happiness?**

To answer this question, we analyze self-reported happiness and financial satisfaction while accounting for additional socio-economic variables that may influence happiness.

### **3. Main Variables**
This analysis primarily focuses on **Q46 (Happiness) and Q50 (Financial Satisfaction)** but includes additional variables for a more comprehensive understanding.

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

## **4. Descriptive Statistics**
To understand the dataset, we computed descriptive statistics for the five most important variables.

| Variable | Count | Mean | Std Dev | Min | 25% | Median | 75% | Max |
|----------|--------|------|---------|-----|-----|--------|-----|-----|
| **Q46 - Happiness** | 97,220 | 1.83 | 0.78 | -5 | 1 | 2 | 2 | 4 |
| **Q50 - Financial Satisfaction** | 97,220 | 6.16 | 2.51 | -5 | 5 | 6 | 8 | 10 |
| **Q49 - Life Satisfaction** | 97,220 | 7.01 | 2.34 | -5 | 6 | 7 | 9 | 10 |
| **Q47 - Health Status** | 97,220 | 2.18 | 0.92 | -5 | 2 | 2 | 3 | 5 |
| **Q48 - Freedom of Choice** | 97,220 | 7.13 | 2.41 | -5 | 6 | 7 | 9 | 10 |


