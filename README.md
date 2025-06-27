# multiple-disease-prediction-streamlit-app

Live : https://multiples-disease-prediction.streamlit.app/

---

# 🏥 Multiple Disease Prediction – Machine Learning Project

## 📘 Overview

**Multiple Disease Prediction** is a machine learning-based healthcare application that predicts the likelihood of various diseases based on patient health inputs. It aims to support early diagnosis and preventive healthcare by analyzing medical symptoms and parameters using trained models.

---

## 🚀 Features

* Predicts multiple diseases from user health data
* Uses classification models trained on medical datasets
* Simple and fast predictions for early diagnosis
* User-friendly interface web-based
* Can be extended with more diseases or data

---

## 🛠️ Technologies Used

* **Python 3.10+**
* **Scikit-learn**
* **Pandas, NumPy**
* **Streamlit**
* **Jupyter Notebook** (for model training and testing)

---

## 📁 Project Structure

```
multiple-disease-prediction/
│
├── data/                    # Datasets (CSV files)
├── notebooks/               # Model training and EDA notebooks
├── model/                   # Saved model files
├── app.py                   # Prediction script or Streamlit app
├── requirements.txt         # Python dependencies
└── README.md                # Project documentation
```

---

## ⚙️ Installation

1. **Clone the Repository**

```bash
git clone https://github.com/rajahassan38201/multiple-disease-prediction-streamlit-app.git
cd multiple-disease-prediction-streamlit-app
```

2. **Create Virtual Environment (Optional)**

```bash
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate
```

3. **Install Dependencies**

```bash
pip install -r requirements.txt
```

---

## ▶️ Usage

1. Run the app:

```bash
streamlit run app.py
```

2. Enter patient details such as:

   * Age, gender, weight
   * Blood pressure, glucose level
   * Symptoms or test results

3. View disease prediction results instantly

---

## 🧠 Model Details

* **Algorithms Used**: Decision Tree, Random Forest, Logistic Regression
* **Type**: Multi-label Classification
* **Evaluation Metrics**: Accuracy, Precision, Recall, F1-Score
* **Data Source**: Open medical datasets

---

## 📌 Use Cases

* Online medical consultation platforms
* Health monitoring tools for early alerts
* Supporting diagnostic tools for healthcare providers

---

## 🤝 Contributing

Pull requests and suggestions are welcome. Please ensure code quality and testing before submitting.

---
