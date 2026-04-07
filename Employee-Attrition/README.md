# 👥 Employee Attrition Prediction

Identifying employee attrition using a **Random Forest Classifier** based on employee demographics and work-related factors.

---

## 📌 Project Overview

Employee attrition is a major challenge for organizations, leading to high recruitment and training costs. This project builds a classification model to predict whether an employee is likely to leave the company based on various HR metrics — helping organizations take proactive retention measures.

---

## 📊 Dataset

- **Source:** [YBI Foundation Dataset](https://github.com/ybifoundation/Dataset/raw/main/EmployeeAttrition.csv)
- **Target Variable:** `Attrition` (Yes / No)
- **Features:** 26 input variables

| Feature | Description |
|---|---|
| Age | Employee age |
| DailyRate | Daily rate of pay |
| DistanceFromHome | Distance from home to office |
| Education | Education level |
| EnvironmentSatisfaction | Satisfaction with work environment |
| JobInvolvement | Level of job involvement |
| JobLevel | Job level in organization |
| JobSatisfaction | Job satisfaction rating |
| MonthlyIncome | Monthly income |
| NumCompaniesWorked | Number of companies worked at |
| PercentSalaryHike | Salary hike percentage |
| PerformanceRating | Performance rating |
| TotalWorkingYears | Total years of work experience |
| WorkLifeBalance | Work-life balance rating |
| YearsAtCompany | Years at current company |
| YearsInCurrentRole | Years in current role |
| YearsSinceLastPromotion | Years since last promotion |
| YearsWithCurrManager | Years with current manager |

---

## 🛠️ Tech Stack

- **Language:** Python 3.x
- **Data Analysis:** Pandas, NumPy
- **Machine Learning:** Scikit-learn (Random Forest Classifier)
- **Visualization:** Matplotlib, Seaborn
- **Environment:** Jupyter Notebook

---

## 🔄 Project Workflow

```
1. Import Libraries
2. Load Dataset
3. Exploratory Data Analysis (EDA)
   ├── View data structure (head, info, describe)
   ├── Check for missing values
   ├── Correlation analysis
   └── Pairplot visualization
4. Define Features (X) and Target (y)
5. Train-Test Split (70% / 30%)
6. Train Random Forest Classifier
7. Predict & Evaluate
   ├── Accuracy Score
   ├── Confusion Matrix
   └── Classification Report
8. Future Predictions on new samples
```

---

## 📈 Results

The model was evaluated using the following metrics:

| Metric | Description |
|---|---|
| Accuracy Score | Overall correct predictions |
| Confusion Matrix | True vs predicted classifications |
| Classification Report | Precision, Recall, F1-score per class |

---

## 🚀 How to Run

1. **Clone the repository**
   ```bash
   git clone https://github.com/Snig17/ml-internship-ybif.git
   cd ml-internship-ybif/employee-attrition
   ```

2. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

3. **Open the notebook**
   ```bash
   jupyter notebook Classification_Model_to_Identify_Employee_Attrition.ipynb
   ```

---

## 📦 Requirements

```
pandas
numpy
scikit-learn
matplotlib
seaborn
jupyter
```

---

## 🧠 Key Learnings

- Built an end-to-end classification pipeline for HR analytics
- Used Random Forest Classifier for predicting employee attrition
- Evaluated model using accuracy score, confusion matrix, and classification report
- Understood key factors contributing to employee attrition

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).