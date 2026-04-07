# 🏥 Multiple Disease Prediction

Identifying multiple diseases using a **Random Forest Classifier** based on patient symptoms and medical indicators.

---

## 📌 Project Overview

Early and accurate disease identification is critical in healthcare. This project builds a multi-class classification model to predict multiple diseases based on patient symptoms — enabling faster diagnosis and better medical decision-making.

---

## 📊 Dataset

- **Source:** [YBI Foundation Dataset](https://github.com/ybifoundation/Dataset/raw/main/MultipleDiseasePrediction.csv)
- **Target Variable:** `prognosis` (type of disease)
- **Features:** Symptom-based input variables
- **Task:** Multi-class Classification

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
5. Train-Test Split (75% / 25%)
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
| Classification Report | Precision, Recall, F1-score per disease class |

> Further performance improvements can be achieved by tuning hyperparameters using Grid Search.

---

## 🚀 How to Run

1. **Clone the repository**
   ```bash
   git clone https://github.com/Vpriyareddy12/ml-internship-ybif.git
   cd ml-internship-ybif/Multiple-Disease-Prediction
   ```

2. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

3. **Open the notebook**
   ```bash
   jupyter notebook Notebook.ipynb
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

- Built a multi-class classification pipeline for healthcare data
- Used Random Forest Classifier to predict multiple diseases from symptoms
- Evaluated model using accuracy score, confusion matrix, and classification report
- Identified scope for further improvement through hyperparameter tuning with Grid Search

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).