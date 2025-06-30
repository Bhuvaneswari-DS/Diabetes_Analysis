# Diabetes_Analysis

## 📁 Dataset Description

The model was trained on a structured dataset with the following features:

| Feature           | Description |
|------------------|-------------|
| `Gender`          | Categorical: Male, Female, Other |
| `Age`             | Numeric: Age of the individual |
| `Hypertension`    | Binary: 0 = No, 1 = Yes |
| `Heart Disease`   | Binary: 0 = No, 1 = Yes |
| `Smoking History` | Categorical: current, former, never, etc. |
| `BMI`             | Numeric: Body Mass Index |
| `HbA1c Level`     | Numeric: Hemoglobin A1c level (glycated hemoglobin) |
| `Blood Glucose`   | Numeric: Glucose concentration in the blood |

The target variable is **Diabetes**: 1 (Positive) or 0 (Negative).

---

## 🎯 Project Goals

- ✅ Train a classification model for predicting diabetes.
- 🧼 Preprocess categorical and numerical features.
- 🧪 Evaluate model performance.
- 🌐 Build an interactive web app using Streamlit for real-time predictions.

---

## 📊 Features

- Clean UI built with Streamlit
- Dropdown and number input fields for user data entry
- Binary classification output (Diabetes / No Diabetes)
- Pre-trained model loaded from a `.pkl` file
- Caching used to optimize performance

---

## 🚀 Getting Started

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/diabetes-prediction-app.git
cd diabetes-prediction-app
2. Install Required Libraries
bash
Copy
Edit
pip install -r requirements.txt
3. Add Model File
Place your model.pkl (the trained ML model) in the root directory of the project.

4. Run the Streamlit App
bash
Copy
Edit
streamlit run DiabetesPrediction.py
📂 Project Structure
bash
Copy
Edit
diabetes-prediction-app/
│
├── DiabetesPrediction.py    # Streamlit App
├── model.pkl                # Trained Machine Learning model
├── requirements.txt         # Python dependencies
└── README.md                # Project documentation
