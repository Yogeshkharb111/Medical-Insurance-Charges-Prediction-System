# 🏥 Medical Insurance Charges Predictor

This project builds a machine learning model to predict individual medical insurance charges using personal health and demographic data. It demonstrates data preprocessing, exploratory data analysis (EDA), model training, and evaluation.

## 📁 Dataset

The dataset used is the popular **Medical Cost Personal Dataset** from [Kaggle](https://www.kaggle.com/mirichoi0218/insurance), which contains information on:

- Age
- Gender
- Body Mass Index (BMI)
- Number of children
- Smoking status
- Region
- Medical charges (target variable)

## 🔍 Features Description

| Feature   | Description                                |
|-----------|--------------------------------------------|
| `age`     | Age of the individual                      |
| `sex`     | Gender (`male`, `female`)                  |
| `bmi`     | Body Mass Index                            |
| `children`| Number of dependents                       |
| `smoker`  | Smoking status (`yes`, `no`)               |
| `region`  | Residential region in the US               |
| `charges` | Individual medical costs billed (target)   |

## 🧪 Workflow

1. **Data Loading** – Load and explore the dataset using pandas.
2. **Data Preprocessing** – Encode categorical variables, check for missing values, and prepare data for modeling.
3. **Exploratory Data Analysis (EDA)** – Use plots and statistical summaries to understand feature relationships.
4. **Feature Engineering** – Apply one-hot encoding to categorical variables.
5. **Modeling** – Train and evaluate regression models:
   - Linear Regression
   - Decision Tree Regressor
   - Random Forest Regressor
6. **Model Evaluation** – Use metrics like R² Score and MAE to evaluate performance.

## 📈 Libraries Used

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scikit-learn`

## ⚙️ How to Run

1. Clone the repository or download the notebook.
2. Install required libraries using:

   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn
