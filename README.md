# 💰 Loan Risk Analyzer
A Python-based data analysis project that explores financial and demographic patterns behind loan default risk. This project focuses on **data cleaning**, **feature engineering**, and **exploratory data analysis (EDA)** using Pandas, Seaborn, and Matplotlib.

---

## 🎯 Objective

To analyze how features like age, gender, income, credit score, education, and employment status influence an individual's loan default behavior.

---

## 🛠️ Technologies Used

- **Python 3**
- **Pandas** for data manipulation
- **Matplotlib & Seaborn** for visualization
- **Jupyter Notebook** for interactive exploration

---

## 📂 Project Files

```
├── loan_risk_analysis.ipynb       # Main Jupyter notebook for analysis
├── risk_behaviour_dataset.csv     # Dataset
├── README.md                      # Documentation
```

---

## 🔍 Features Performed

- ✅ Standardized messy fields like `Gender`, `Education`, and `Employment Status`
- ✅ Created new features like `Age Group`, `Credit Score Category`, `Income Bracket`
- ✅ Analyzed relationships between:
  - Income & Education
  - Defaults & Age Group
  - Credit Score & Income
  - DTI & Employment Status

---

## 📊 Final Insights

-  Most individuals in the dataset fall within the 30–50 age range, indicating a working-age heavy population.
-  Gender distribution is balanced, with a slightly higher representation of males.
-  Higher education levels (like Master’s and Doctorate) are associated with higher average incomes.
-  Single individuals tend to have slightly higher credit scores than married or divorced individuals.
-  Income and credit score show a positive correlation — individuals with higher incomes tend to maintain better credit scores.
-  Unemployed individuals have a higher and more variable debt-to-income (DTI) ratio, suggesting increased financial risk.
-  Younger individuals (especially under 35) and those unemployed exhibit higher average default records.
-  Debt-to-income ratio negatively impacts creditworthiness and is notably high in low-income and unemployed segments.

---

## ▶️ How to Run

1. Clone this repo or download the files  
2. Install dependencies:
   ```bash
   pip install pandas matplotlib seaborn openpyxl
   ```
3. Run the notebook:
   ```bash
   jupyter notebook loan_risk_analysis.ipynb
   ```

---

## 📬 Contact
Feel free to contribute, fork, or ask questions via Issues!

---

## 📜 License

This project is open-source and free to use under the MIT License.
