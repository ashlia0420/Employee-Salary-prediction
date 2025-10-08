
# 💼 Salary Classification App using Streamlit

A **Streamlit web app** that predicts whether an employee earns **>50K or ≤50K** based on demographic and work-related features.
Built using a **Logistic Regression model** trained on the **Adult dataset**.


## 🚀 Overview

This project demonstrates how machine learning can classify income levels using features like:

* Age, Education, Occupation
* Hours per week, Gender, Marital status
* Capital gain/loss, etc.

The app provides a simple interface for both single and batch predictions.

---

## ⚙️ Features

* Interactive Streamlit UI
* 13 input features from the Adult dataset
* Logistic Regression-based prediction
* Handles encoding and scaling
* Option for manual or batch input

---

## 🧩 How to Run

1️⃣ Clone the repo:

```bash
git clone https://github.com/<your-username>/Salary-Classification-App.git
cd Salary-Classification-App
```

2️⃣ Install dependencies:

```bash
pip install streamlit scikit-learn pandas numpy joblib
```

3️⃣ Open and run all cells in the notebook:

```bash
jupyter notebook salary_classification.ipynb
```

4️⃣ The Streamlit app will launch automatically, or run manually with:

```bash
streamlit run salary_classification.ipynb
```

---

## 🛠️ Tech Stack

* Python
* Streamlit
* scikit-learn
* pandas, numpy
* joblib

---

## 📊 Dataset

**UCI Adult Dataset**

* Instances: 48,842
* Features: 13
* Target: Income >50K or ≤50K


<img width="1920" height="1080" alt="Screenshot (160)" src="https://github.com/user-attachments/assets/853601f6-53b2-4185-afa7-e56b72dcd787" />
