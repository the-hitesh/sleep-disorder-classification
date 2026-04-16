# Sleep Pattern Classification using Hidden Markov Model

## 📌 Project Overview
This project uses a Hidden Markov Model (HMM) to classify sleep disorder patterns such as:
- Normal Sleep
- Insomnia
- Sleep Apnea

The model analyzes physiological data like heart rate, stress level, sleep duration, and blood pressure to infer hidden sleep states probabilistically.

---

## ⚙️ Requirements
Make sure Python 3 is installed on your system.

---

## 📥 Installation Steps (On a New PC)

### 1. Clone or Download the Project

Download the Project and move into the project folder from terminal.
cd SleepPatternProject

---

### 2. Create Virtual Environment (Recommended)

python3 -m venv sleep_env
source sleep_env/bin/activate   # Linux/Mac

# For Windows:
sleep_env\Scripts\activate

---

### 3. Install Required Libraries

pip install -r requirements.txt

---

## ▶️ Running the Project

### 4. Start Jupyter Notebook

jupyter notebook

This will open a browser.

---

### 5. Open the Notebook

Navigate to the notebook/ folder and open:
Sleep_HMM_Final.ipynb

---

### 6. Run All Cells

Click: Kernel → Restart & Run All

---

##Alternate Method:
You can upload the notebook file and the csv file to Google Collab and run it from there.

## 📊 Features

- Data preprocessing and cleaning
- Exploratory Data Analysis (EDA)
- Hidden Markov Model implementation
- Transition probability visualization
- Statistical evaluation (Log Likelihood, BIC)
- Sleep disorder prediction

---

## 🧠 Model Details

- Model: Gaussian Hidden Markov Model
- Hidden States: 3
- Covariance Type: Diagonal
- Learning Method: Maximum Likelihood Estimation

---

## 📁 Project Structure

SleepPatternProject/
│
├── notebook/
├── requirements.txt
└── README.md

---

## 🎯 Conclusion

This project demonstrates how probabilistic models like Hidden Markov Models can be used to infer hidden health conditions from observable data.

---
