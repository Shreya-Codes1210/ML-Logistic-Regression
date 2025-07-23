# Logistic Regression: Diabetes Prediction

This project uses logistic regression to predict whether a patient has diabetes based on health-related attributes.

## 📁 Files Included

- `logistic_regression.ipynb` – Jupyter Notebook containing the full code.
- `diabetes2.csv` – Dataset used for training and testing the model.
- `logistic_regression.py` *(optional)* – Python script version of the notebook.
- `README.md` – This documentation file.

## 📊 Dataset Information (`diabetes2.csv`)

The dataset contains the following columns:

- Pregnancies
- Glucose
- BloodPressure
- SkinThickness
- Insulin
- BMI
- DiabetesPedigreeFunction
- Age
- Outcome (Target: 0 = No Diabetes, 1 = Diabetes)

## ⚙️ Model Used

- **Logistic Regression**
- Library: `sklearn.linear_model.LogisticRegression`
- Accuracy achieved: ~75%

## 📈 Visualization

The scatter plot compares:
- **Actual Outcomes** (yellow)
- **Predicted Outcomes** (red)

against the **Glucose level** for test data.

## 🚀 How to Run

1. Clone or download this repository.
2. Open `logistic_regression.ipynb` in Jupyter Notebook or Jupyter Lab.
3. Run all cells to train the model and view accuracy and plots.

## 📦 Requirements

Install the following Python libraries:

```bash
pip install pandas scikit-learn matplotlib numpy
```

## 📧 Author

Shreya Gupta  
Biomedical Engineering   
