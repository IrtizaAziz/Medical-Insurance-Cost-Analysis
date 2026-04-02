# 📊 Medical Insurance Cost Analysis

### 🎯 Objective
This project is a comprehensive, data-driven statistical analysis of healthcare costs. The goal was to identify and quantify the primary demographic and lifestyle factors that influence medical insurance premiums using a dataset of 1,338 individuals.

### 🛠️ Tech Stack & Methodologies
* **Tools:** Microsoft Excel (Data Analysis Toolpak), Python
* **Methodologies:** Data Cleaning, Descriptive Statistics, Probability Distribution Analysis, Hypothesis Testing (t-tests, z-tests), Simple & Multiple Linear Regression.

### 📂 Repository Contents
* **`Report.docx`**: The full written report detailing our methodology, statistical theories, and conclusions.
* **`Analysis of Factors Influencing Medical Insurance Charges.pdf`**: The slide deck summarizing our key findings and data visualizations.
* **`Analysis of Factors Influencing Medical Insurance Charges.xlsx`**: The complete workbook containing the raw data, data dictionary, cleaned variables, and all statistical modeling outputs (Linear and Multiple Regression).

### 💡 Key Findings
1. **Smoking is the Dominant Cost Driver:** Statistical modeling proved smoking is the strongest individual predictor of high costs. Being a smoker is associated with medical charges that are roughly 4.5 times higher than non-smokers.
2. **The Compound Effect of BMI:** While BMI alone has a weak positive relationship with charges, the interaction between smoking and obesity (BMI > 30) creates a massive compound effect on insurance premiums.
3. **Robust Predictive Modeling:** We developed a multiple linear regression model incorporating age, BMI, smoking status, and region that successfully explains over **75% of the variation** in insurance charges (Adjusted R-Square: 0.76).

### 📈 Statistical Validation
* Conducted Chi-Square tests to evaluate discrete distributions.
* Validated continuous probability distributions (normalizing BMI).
* Performed rigorous ANOVA testing on the regression models, confirming extreme statistical significance (P-value effectively zero) with zero reliance on random luck.
