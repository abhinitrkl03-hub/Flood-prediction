# 🌊 Bihar Flood Risk & Inundation Prediction using Machine Learning

## 📌 Project Overview
This project predicts flood risk using Machine Learning by combining real rainfall data with environmental factors such as river management, drainage capacity, deforestation, and riverbed siltation. An interactive Streamlit dashboard allows users to simulate different scenarios and estimate flood probability for better disaster preparedness.

---

## 🚀 Features
- Live rainfall data integration
- Exploratory Data Analysis (EDA)
- Data preprocessing and feature engineering
- Feature scaling using StandardScaler
- Flood risk prediction using multiple regression models
- Hyperparameter tuning using GridSearchCV
- Interactive Streamlit dashboard
- Real-time flood risk simulation

---

## 📂 Dataset
The project uses **National Water Informatics Centre (NWIC)** rainfall data combined with engineered environmental features.

### Dataset Features
- Monsoon Rainfall Intensity (mm)
- River Management Score
- Drainage Capacity
- Deforestation Index
- Riverbed Siltation Level
- Flood Probability (Target Variable)

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Streamlit

---

## 📊 Exploratory Data Analysis

The project includes:

- Dataset exploration
- Missing value analysis
- Statistical summary
- Rainfall distribution visualization
- Feature relationship analysis

---

## ⚙️ Data Preprocessing

- Data cleaning
- Feature engineering
- Train-test split
- Standardization using **StandardScaler**
- Pipeline-based preprocessing

---

## 🤖 Machine Learning Models Implemented

The following regression models were implemented and compared:

- Ridge Regression
- Random Forest Regressor
- Gradient Boosting Regressor
- K-Nearest Neighbors (KNN) Regressor

---

## 🔍 Hyperparameter Tuning

Random Forest was optimized using:

- GridSearchCV
- 3-Fold Cross Validation
- R² Score as the evaluation metric

---

## 📈 Model Evaluation

Models were evaluated using:

- R² Score
- Mean Squared Error (MSE)
- Cross Validation

---

## 🌐 Streamlit Dashboard

The dashboard allows users to:

- Simulate rainfall intensity
- Adjust river management quality
- Modify drainage capacity
- Set deforestation index
- Configure riverbed siltation level
- Predict flood risk in real time
- View live rainfall dataset preview

---

## 📁 Project Structure

```
FloodRiskPrediction/
│
├── flood.py
├── README.md
└── requirements.txt
```

---

## ▶️ Installation

Clone the repository

```bash
git clone https://github.com/your-username/FloodRiskPrediction.git
```

Navigate to the project directory

```bash
cd FloodRiskPrediction
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run the Streamlit application

```bash
streamlit run flood.py
```

---

## 📌 Future Improvements

- Integration with real-time weather APIs
- GIS-based flood risk visualization
- Deep Learning (LSTM) for flood forecasting
- SMS/Email flood alert system
- Cloud deployment using Streamlit Community Cloud or AWS

---
