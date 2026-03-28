# 📊 A/B Testing Analysis — Bank Marketing Dataset

## 🚀 Project Overview

This project performs a complete **A/B Testing analysis** to evaluate the effectiveness of different customer contact methods used in a bank marketing campaign.

The main goal is to determine whether **cellular contact** leads to higher customer conversion compared to **telephone contact**.

---

## 📂 Dataset

* Source: Kaggle (Bank Marketing Dataset)
* Records: 40,000+ customers
* Features include:

  * Demographics (age, job, education)
  * Campaign details (contact type, duration)
  * Outcome (conversion: yes/no)

---

## 🎯 Objective

To compare two groups:

* **Control Group:** Telephone contact
* **Variant Group:** Cellular contact

And determine:
✔ Which method performs better
✔ Whether the difference is statistically significant

---

## 🧹 Data Preprocessing

* Replaced `"unknown"` values with `NaN`
* Removed missing values
* Converted target variable (`y`) into binary (`converted`)

  * Yes → 1
  * No → 0

---

## 📊 Exploratory Data Analysis

* Checked distribution of categorical variables
* Calculated overall conversion rate
* Identified missing and unknown values

---

## 🧪 A/B Testing Methodology

### 🔹 1. Conversion Rate

Conversion rate is calculated as:

Conversion Rate = Converted Users / Total Users

---

### 🔹 2. Statistical Tests Used

#### ✅ Z-Test (Proportions Test)

* Used to compare conversion rates between two groups
* Determines whether the difference is statistically significant

#### ✅ Chi-Square Test

* Tests independence between categorical variables
* Validates relationship between contact method and conversion

---

### 🔹 3. Confidence Interval (95%)

* Provides a range where the true conversion rate lies
* Also calculated for the difference between groups

---

## 📈 Results

| Metric          | Telephone (Control) | Cellular (Variant) |
| --------------- | ------------------- | ------------------ |
| Users           | 10,045              | 20,443             |
| Conversions     | 586                 | 3,273              |
| Conversion Rate | 5.83%               | 16.01%             |

---

## 🚀 Performance Improvement

* **Absolute Lift:** +10.18%
* **Relative Lift:** 2.74x increase

---

## 📊 Statistical Significance

| Test       | Result      |
| ---------- | ----------- |
| Z-Test     | Significant |
| P-Value    | ~0.000000   |
| Chi-Square | Significant |

✔ The difference is **highly statistically significant**

---

## 📉 Visualizations

* Conversion Rate Comparison
* Confidence Intervals (Error Bars)
* Converted vs Not Converted (Stacked Bar Chart)

---

## 🧾 Final Conclusion

✅ Cellular contact significantly outperforms telephone contact
✅ Results are statistically significant
✅ Strong recommendation to adopt **cellular strategy**

---

## 🛠️ Tech Stack

* Python
* Pandas, NumPy
* Matplotlib, Seaborn
* SciPy, Statsmodels

---

## 💡 Key Learnings

* A/B Testing in real-world scenarios
* Hypothesis testing using Z-test and Chi-square
* Importance of data cleaning
* Making data-driven business decisions

---

## 🔗 Dataset Link

https://www.kaggle.com/datasets/uciml/bank-marketing

---

## ⭐ Future Improvements

* Apply Logistic Regression for prediction
* Feature importance analysis
* Build an interactive dashboard (Streamlit)

---

## 🙌 Author

**Aman Shah Masood**
Aspiring Data Scientist | Python Developer | ML Enthusiast
