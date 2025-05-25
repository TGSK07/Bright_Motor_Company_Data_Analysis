# Bright Motor Company – Data Analysis

## 📊 Overview

This project explores and analyzes a dataset from Bright Motor Company to extract insights about employee salary, loan status, etc. It also applies Ridge Regression to predict salary based on key features. The notebook includes data preprocessing, exploratory data analysis (EDA), data visualization, and model evaluation.
---

## 🔍 Key Insights
- Total salary is strongly influenced by Partner Salary **(0.80)** and Salary **(0.60)**. Age is highly correlated with both Price (0.78) and Salary **(0.57)**. Number of dependents shows **weak or negative** impact on features.

- Post Graduate Individuals earn **38.8%** more than a Graduate Individuals. 

- Among all individuals, the count of male individuals taking personal loans are **3.34 times** the female individuals.

- There is **negligible amount** of difference between average salary of individuals with or without working partner.

- Business Individuals taken slightly less house loan than Salaried Individuals.

- Individuals **without personal loans** have a **median salary of around ₹60,000**, while those **with personal loans** have a slightly lower **median salary of around ₹58,000**. The **salary range** for both groups spans from approximately **₹30,000 to ₹90,000**, indicating similar overall distribution. This suggests that **personal loan status has minimal impact on salary levels**, with only a slight difference in median values.

- There is linearity relationship between Service Price and Total Salary. **It show, that as the individuals total salary increases, they goes toward luxuriers automobile which make the Service Price to be increased**. 

- Married individuals takes 8.9 times Personal Loans then Single individuals.

- **Females generally have a higher median salary** than male , indicating a possible gender pay gap. There is also **greater salary variability among females**, with wider interquartile ranges. This suggests that female salaries are more dispersed, while male salaries are relatively clustered in a narrower range.

- Individuals with a working partner generally have higher total salaries, regardless of their personal loan status. **Personal loan status shows minimal impact on total salary**.

- The **distribution of total salary**, which is **right-skewed**, indicating more individuals earn **between ₹55,000 and ₹85,000**, with the **peak frequency around ₹60,000–₹65,000**. Salaries gradually decrease beyond ₹100,000, with fewer individuals earning above ₹120,000. 

---

## 🤖 Model: Ridge Regression

* **Input Features**: `Age`, `Education`, and `No_of_Dependents`
* **Target Variable**: `Salary`
* **Model Used**: Ridge Regression (`alpha=0.4`)

### 🔢 Model Results:

* **RMSE (Root Mean Squared Error)**: 7165.657
* **Normalized RMSE**: 0.121

### 📌 Insight:

* The normalized RMSE of 0.121 indicates the model performs **reasonably well** in predicting salaries based on the provided features, with relatively low error compared to the salary range.


---

## ✅ Conclusion

The analysis provided actionable insights into salary distributions and factors like marital status, loan presence, etc. Ridge Regression gave a reliable predictive baseline. These findings can guide HR or financial decisions within the company.
