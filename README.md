# ❤️ Heart Disease Prediction using Machine Learning

A Machine Learning based web application that predicts whether a patient is likely to have heart disease based on various medical parameters. This project is built using Python, Scikit-learn, and Streamlit.

---

## 📖 Project Overview

Heart disease is one of the leading causes of death worldwide. Early prediction can help doctors and patients take preventive measures.

This project uses the K-Nearest Neighbors (KNN) Machine Learning algorithm to predict the presence of heart disease based on patient health data.

---

## 🚀 Features

- Interactive Streamlit Web App
- User-friendly Interface
- Real-time Prediction
- Data Preprocessing
- Feature Scaling
- Machine Learning Prediction using KNN
- Fast and Accurate Results

---

## 🛠️ Technologies Used

- Python
- Streamlit
- Pandas
- NumPy
- Scikit-learn
- Joblib
- Matplotlib
- Seaborn

---

## 📂 Dataset Information

Dataset Name: Heart Disease Dataset

Total Records: **918**

Features:

- Age
- Sex
- Chest Pain Type
- Resting Blood Pressure
- Cholesterol
- Fasting Blood Sugar
- Resting ECG
- Maximum Heart Rate
- Exercise Induced Angina
- Oldpeak
- ST Slope

Target:

- HeartDisease
  - 0 = No Heart Disease
  - 1 = Heart Disease

---

## 🧠 Machine Learning Algorithm

The project uses:

- K-Nearest Neighbors (KNN)

Additional preprocessing:

- Label Encoding
- Feature Scaling using StandardScaler

---

## 📁 Project Structure

```
Heart_Disease_Prediction/
│
├── app.py
├── heart.csv
├── knn_heart_model.pkl
├── heart_scaler.pkl
├── heart_columns.pkl
├── Heart_Disease_Prediction.ipynb
└── README.md
```

---

## ⚙️ Installation

Clone the repository

```bash
git clone https://github.com/12Avantika07/Heart_Disease_Prediction.git
```

Move into the project folder

```bash
cd Heart_Disease_Prediction
```

Install dependencies

```bash
pip install streamlit pandas numpy scikit-learn matplotlib seaborn joblib
```

Run the application

```bash
streamlit run app.py
```

---

## 🖥️ How It Works

1. Enter the patient's medical details.
2. Click the Predict button.
3. The trained KNN model processes the input.
4. The application displays whether the patient is likely to have heart disease.

---

## 📸 Output

(Add screenshots of your Streamlit application here.)

Example:

- Home Page
- Prediction Result
- Success/Warning Message

---

## 🔮 Future Improvements

- Deploy on Streamlit Cloud
- Improve prediction accuracy
- Add multiple ML models
- Compare different algorithms
- Better UI/UX
- Add health recommendations

---

## 👩‍💻 Author

**Avantika Shukla**

GitHub:
https://github.com/12Avantika07
