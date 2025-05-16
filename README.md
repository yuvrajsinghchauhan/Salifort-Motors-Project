## Overview

Salifort Motors is facing a high employee turnover rate, which negatively impacts corporate culture and increases hiring and training costs. To address this issue, the company wants to predict employee attrition using self-reported survey data. By identifying key drivers behind employee departures, Salifort can develop targeted retention strategies, improve workplace satisfaction, and reduce operational disruptions.

## Business Understanding

The senior leadership at Salifort Motors wants to create a supportive corporate culture that fosters employee success and professional growth. However, due to high turnover rates, the company is facing significant challenges such as:

* Increased recruitment and training costs.

* Loss of skilled and experienced employees.

* Declining employee morale and productivity.

By using data-driven analysis, the HR team aims to identify the primary factors influencing employee turnover, predict which employees are likely to leave, and implement strategies to improve retention.

## Data Understanding

The dataset (HR_capstone_dataset.csv) contains 14,999 rows of employee self-reported information, representing various attributes that may contribute to turnover. The dataset includes 10 columns:

| **Feature**               | **Description** |
|---------------------------|----------------|
| `satisfaction_level`      | Employee satisfaction score (0-1). |
| `last_evaluation`        | Performance review score (0-1). |
| `number_project`        | Number of projects the employee contributes to. |
| `average_monthly_hours` | Average hours worked per month. |
| `time_spend_company`    | Years spent at the company. |
| `work_accident`         | Whether an accident occurred (`0 = No, 1 = Yes`). |
| `left`                 | Whether the employee left (`0 = No, 1 = Yes`). |
| `promotion_last_5years` | Promotion history (`0 = No, 1 = Yes`). |
| `department`           | Employee’s department (categorical). |
| `salary`              | Salary level (`low, medium, high`). |

Key questions to explore:

* How does satisfaction level affect retention?

* Do employees with more projects or long working hours leave more frequently?

* Does salary play a significant role in turnover?

* Does lack of promotion lead to higher attrition rates?

## Modeling and Evaluation

To predict employee attrition, we will explore multiple models:

1. Logistic Regression 🧠 (Statistical approach)
   * Simple model for understanding key predictors.
   * Provides interpretability but may not capture complex relationships.

2. Decision Tree & Random Forest 🌲 (Machine Learning approach)
   * Helps identify important features.
   * Can handle interactions between variables.
   * Random Forest improves accuracy by reducing overfitting.
     
3. XGBoost 🚀 (Advanced ML approach)
   * Optimized gradient boosting model for high accuracy.
   * Ideal for structured datasets like HR data.

## Evaluation Metrics:

* Accuracy: How well the model predicts attrition.

* Precision & Recall: Ensuring correct identification of employees likely to leave.

* ROC Curve & Feature Importance: Understanding which factors drive turnover.

## Conclusion

From the analysis, key factors contributing to employee attrition include: 

✔ Low satisfaction levels – Employees unhappy with their work environment are more likely to leave. 

✔ High work hours & project overload – Employees working longer hours and multiple projects face burnout. 

✔ Lack of promotion – Employees who haven't been promoted in the last 5 years seek opportunities elsewhere. 

✔ Salary impact – Those with low salaries are more prone to leaving, especially in demanding roles.

## Recommendations:

🔹 Improve Employee Satisfaction – Increase engagement, work-life balance, and feedback mechanisms. 

🔹 Reduce Workload Strain – Ensure fair project distribution and encourage well-being initiatives. 

🔹 Career Growth & Promotions – Offer development programs, upskilling, and internal career progression. 

🔹 Compensation Review – Align salaries with industry standards and performance metrics.

By implementing these strategies, Salifort Motors can significantly reduce employee turnover, improve workplace culture, and ensure long-term success.
