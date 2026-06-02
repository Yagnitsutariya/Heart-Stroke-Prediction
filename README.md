# ❤️ Heart Stroke Prediction

A Machine Learning web application that predicts the likelihood of heart disease/stroke based on patient health parameters. The project uses data preprocessing, exploratory data analysis, model training, and deployment through a user-friendly interface.

## 📌 Project Overview

Heart disease and stroke are among the leading causes of death worldwide. Early prediction can help individuals seek timely medical attention and adopt preventive measures.

This project leverages Machine Learning algorithms to analyze patient health data and predict whether a person is at risk of heart disease/stroke.

---

## 🚀 Features

* User-friendly web interface
* Real-time prediction
* Data preprocessing and feature engineering
* Machine Learning model training and evaluation
* Model serialization using Joblib
* Easy deployment with Flask/Streamlit
* Responsive design

---

## 🛠️ Tech Stack

### Programming Language

* Python

### Libraries

* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn
* Joblib

### Web Framework

* Flask / Streamlit

---

## 📂 Project Structure

```text
Heart-Stroke-Prediction/
│
├── app.py                 # Main application file
├── heart.csv              # Dataset
├── KNN_heart.pkl          # Trained ML model
├── requirements.txt       # Dependencies
├── templates/             # HTML templates
├── static/                # CSS, JS, Images
└── README.md
```

---

## 📊 Dataset

The dataset contains medical attributes such as:

* Age
* Sex
* Chest Pain Type
* Resting Blood Pressure
* Cholesterol
* Fasting Blood Sugar
* Resting ECG
* Maximum Heart Rate
* Exercise Induced Angina
* Old Peak
* Slope
* Number of Major Vessels
* Thalassemia

Target Variable:

* 0 → No Heart Disease
* 1 → Heart Disease Present

---

## 🤖 Machine Learning Model

The project uses the **K-Nearest Neighbors (KNN)** algorithm for prediction.

### Workflow

1. Data Collection
2. Data Cleaning
3. Exploratory Data Analysis (EDA)
4. Feature Selection
5. Train-Test Split
6. Model Training
7. Model Evaluation
8. Model Deployment

---

## 📈 Model Performance

| Metric    | Score |
| --------- | ----- |
| Accuracy  | XX%   |
| Precision | XX%   |
| Recall    | XX%   |
| F1 Score  | XX%   |

> Replace the values above with your actual model performance.

---

## ⚙️ Installation

### Clone Repository

```bash
git clone https://github.com/Yagnitsutariya/Heart-Stroke-Prediction.git
```

### Navigate to Project Directory

```bash
cd Heart-Stroke-Prediction
```

### Create Virtual Environment

```bash
python -m venv .venv
```

### Activate Virtual Environment

Windows:

```bash
.venv\Scripts\activate
```

Linux/Mac:

```bash
source .venv/bin/activate
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

---

## ▶️ Run the Application

```bash
python app.py
```

Open your browser and visit:

```text
http://127.0.0.1:5000
```

---

## 📷 Application Screenshots

Add screenshots here:

```markdown
![Home Page](screenshots/home.png)
![Prediction Page](screenshots/predict.png)
```

---

## 🔮 Future Improvements

* Deploy on cloud platforms
* Improve model accuracy
* Add multiple ML algorithms for comparison
* Add user authentication
* Integrate real-time healthcare APIs

---

## 👨‍💻 Author

**Yagnit Sutariya**

* GitHub: https://github.com/Yagnitsutariya
* LinkedIn: Add your LinkedIn profile here

---

## 📜 License

This project is developed for educational and learning purposes.

Feel free to fork, improve, and contribute.
