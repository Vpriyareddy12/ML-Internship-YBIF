# 🏗️ Concrete Compressive Strength Prediction

Predicting the compressive strength of concrete using **Linear Regression** based on its mix composition and age.

---

## 📌 Project Overview

Concrete compressive strength is one of the most critical parameters in civil engineering and construction. This project builds a regression model to predict the compressive strength (in MPa) of concrete based on its ingredient composition and curing age — helping engineers estimate strength without costly physical tests.

---

## 📊 Dataset

- **Source:** [YBI Foundation Dataset](https://github.com/ybifoundation/Dataset/raw/main/Concrete%20Compressive%20Strength.csv)
- **Samples:** 1030 instances
- **Features:** 8 input variables + 1 target variable

| Feature | Description | Unit |
|---|---|---|
| Cement | Cement content | kg/m³ |
| Blast Furnace Slag | Slag content | kg/m³ |
| Fly Ash | Fly ash content | kg/m³ |
| Water | Water content | kg/m³ |
| Superplasticizer | Superplasticizer content | kg/m³ |
| Coarse Aggregate | Coarse aggregate content | kg/m³ |
| Fine Aggregate | Fine aggregate content | kg/m³ |
| Age | Curing age | Days (1–365) |
| **Concrete Compressive Strength** | **Target variable** | **MPa** |

---

## 🛠️ Tech Stack

- **Language:** Python 3.x
- **Data Analysis:** Pandas, NumPy
- **Machine Learning:** Scikit-learn
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
   └── Pairplot visualization
4. Define Features (X) and Target (y)
5. Train-Test Split (70% / 30%)
6. Train Linear Regression Model
7. Predict & Evaluate
   ├── Mean Absolute Error (MAE)
   ├── Mean Absolute Percentage Error (MAPE)
   └── Mean Squared Error (MSE)
8. Visualize Actual vs Predicted values
9. Future Predictions on new samples
```

---

## 📈 Results

The model was evaluated using the following metrics:

| Metric | Description |
|---|---|
| MAE | Mean Absolute Error — average prediction error |
| MAPE | Mean Absolute Percentage Error — % deviation |
| MSE | Mean Squared Error — penalizes large errors |

A scatter plot of **Actual vs Predicted Strength** was plotted to visualize model performance.

---

## 🚀 How to Run

1. **Clone the repository**
   ```bash
   git clone https://github.com/Vpriyareddy12/concrete-compressive-strength-prediction.git
   cd concrete-compressive-strength-prediction
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

- Performed end-to-end regression pipeline from data loading to future prediction
- Understood the impact of each concrete ingredient on compressive strength
- Evaluated model performance using multiple error metrics
- Visualized actual vs predicted values to assess model fit

---


## 📄 License

This project is licensed under the [MIT License](LICENSE).