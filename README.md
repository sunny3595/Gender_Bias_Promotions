## Gender Bias in Employee Promotions


### Problem Statement: 
Assess whether gender impacts promotion decisions and provide actionable recommendations.

### 1. Problem Framing & Hypothesis
The objective is to analyze whether gender affects promotion decisions in a company setting. We
simulate a realistic HR dataset to mimic employee records and promotion decisions. - Hypothesis: -
Null Hypothesis (H0): Gender does not influence promotion decisions. - Alternate Hypothesis (H1):
There is a statistically significant relationship between gender and promotions. - KPIs: - Overall
promotion rate - Promotion rate by gender - Model evaluation metrics (accuracy, F1 score)

### 2. Descriptive Analysis
The dataset was examined for distributions, outliers, and key relationships. Promotion rates were
calculated by gender. As shown in the chart below, males had a significantly higher promotion rate
compared to females.
Promotion Rate by Gender (Bar Chart)
Male: 56.97% | Female: 48.69%

### 3. Diagnostic Analysis
Cross-tabulations were used to explore promotion rate variations by department and gender.
Promotions were generally higher in departments like Sales and Operations. Females had lower
promotion rates across almost all departments, even when performance scores and tenure were similar.

### 4. Predictive Modeling
We trained a logistic regression model to predict promotion likelihood based on features such as
performance score, KPI, tenure, and gender. - Model Accuracy: 58.53% - F1 Score: 0.64 - Gender
Coefficient (Male): 0.350 The positive coefficient for 'gender_Male' suggests that males are more likely to be promoted, even when controlling for other variables.

### 5. Prescriptive Insights
Based on the findings, the following recommendations are proposed to mitigate gender bias in
promotions: - Use blind evaluation techniques during promotions. - Set clearly defined, quantifiable
criteria for promotion eligibility. - Provide gender-bias training for promotion panels. - Create
dashboards to monitor promotion trends by gender quarterly.

### 6. Conclusion
Our end-to-end analysis pipeline—from problem framing, data simulation, descriptive statistics,
diagnostics, modeling, to prescriptive insights—strongly indicates the presence of gender-based
disparity in promotions. Implementing the above strategies can help organizations like Gigaversity
ensure fairer, more merit-based promotions.



### Key Findings:
- Overall promotion rate: 53.22%
- Promotion rate (Male): 56.97%
- Promotion rate (Female): 48.69%
- Logistic regression coefficient for gender (Male vs Female): 0.350
- Model F1 Score: 0.640

### Recommendations:
• Adopt blind promotion reviews to minimize unconscious bias.
• Define transparent, performance based criteria for promotion.
• Provide bias awareness training for managers.
• Track promotion KPIs and gender ratios quarterly with dashboards.

Impact: Implementing these actions could reduce promotion disparities and improve overall
employee satisfaction and retention.

