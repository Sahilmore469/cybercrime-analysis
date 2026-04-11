# 🔍 Cybercrime Motive Analysis — India 2013

<div align="center">

![Python](https://img.shields.io/badge/Python-3.13-blue?style=for-the-badge&logo=python)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?style=for-the-badge&logo=jupyter)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-ML-green?style=for-the-badge&logo=scikit-learn)
![Pandas](https://img.shields.io/badge/Pandas-Data-lightblue?style=for-the-badge&logo=pandas)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen?style=for-the-badge)

<br/>

> **Analyzing cybercrime patterns across Indian states using real government data, EDA, and Machine Learning.**

</div>

---

## 📌 Table of Contents

- [About the Project](#-about-the-project)
- [Dataset](#-dataset)
- [Project Workflow](#-project-workflow)
- [Visualizations](#-visualizations)
- [ML Models & Results](#-ml-models--results)
- [Key Findings](#-key-findings)
- [Technologies Used](#-technologies-used)
- [How to Run](#-how-to-run)
- [Author](#-author)

---

## 📖 About the Project

This project performs an end-to-end data science analysis on **cybercrime data from India (2013)**. It explores how different motives like Fraud, Harassment, Greed, and Revenge contribute to the total cybercrime count across states and union territories.

The project includes:
- 🔎 Exploratory Data Analysis (EDA)
- 📊 Rich visualizations
- 🤖 Machine Learning models for prediction and classification

---

## 📁 Dataset

| Property | Details |
|---|---|
| **Source** | [data.gov.in](https://data.gov.in) — Govt. of India Open Data |
| **File** | `IT_motives_2013.csv` |
| **Records** | 35 States / Union Territories |
| **Year** | 2013 |
| **Features** | 8 crime motives + Total |

### 📋 Feature Description

| Feature | Description |
|---|---|
| `Revenge /Settling scores` | Crimes motivated by revenge |
| `Greed/ Money` | Crimes for financial gain |
| `Extortion` | Extortion-based cybercrimes |
| `Cause Disrepute` | Crimes to damage reputation |
| `Prank/ Satisfaction of Gaining Control` | For fun or control |
| `Fraud/ Illegal Gain` | Fraudulent cybercrime |
| `Eve teasing/ Harassment` | Harassment-related crimes |
| `Others` | Other motives |
| `Total` | Total cybercrime count per state |

---

## 🔄 Project Workflow

```
Raw Dataset
    │
    ▼
Data Cleaning & Preprocessing
    │
    ▼
Exploratory Data Analysis (EDA)
    │
    ▼
Feature Engineering
    │
    ├──► Regression Models ──► Predict Total Crimes
    │
    └──► Classification Model ──► High / Low Crime State
```

---

## 📊 Visualizations

| # | Plot | Purpose |
|---|---|---|
| 1 | Distribution Histograms | Distribution of each crime motive |
| 2 | Correlation Heatmap | Relationships between features |
| 3 | Top 10 States Bar Chart | States with highest cybercrimes |
| 4 | Motive-wise Crime Distribution | Most dominant crime motives |
| 5 | Fraud vs Total Scatter Plot | Impact of fraud on total crimes |
| 6 | Pairplot | Feature relationships overview |
| 7 | Boxplot | Outlier detection |
| 8 | Feature Importance | Most influential motives (RF) |
| 9 | Actual vs Predicted | Regression performance |
| 10 | Residual Distribution | Error analysis |
| 11 | Model Comparison (R²) | Linear vs Random Forest |
| 12 | Confusion Matrix | Classification performance |

---

## 🤖 ML Models & Results

### Regression — Predicting Total Crimes

| Model | MAE | MSE | R² Score |
|---|---|---|---|
| Linear Regression | — | — | — |
| Random Forest Regressor | — | — | — |

> ✅ Random Forest outperformed Linear Regression

### Classification — High vs Low Crime State

| Model | Accuracy |
|---|---|
| Logistic Regression | **86%** |

> States above median Total Crimes → High Crime (1), below → Low Crime (0)

---

## 💡 Key Findings

```
🏆 Top State by Cybercrime     →  Maharashtra
🎯 Most Common Motive          →  Others
🔥 Most Influential Motive     →  Fraud / Illegal Gain
📊 Average Crimes per State    →  ~163
✅ Classification Accuracy     →  86%
```

---

## 💻 Technologies Used

```python
Python 3.13       # Core language
Pandas            # Data manipulation
NumPy             # Numerical computing
Matplotlib        # Plotting
Seaborn           # Statistical visualization
Scikit-learn      # Machine learning
Jupyter Notebook  # Development environment
```

---

## 🚀 How to Run

**1. Clone the repository**
```bash
git clone https://github.com/your-username/cybercrime-analysis.git
cd cybercrime-analysis
```

**2. Install dependencies**
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

**3. Download the dataset**

Get `IT_motives_2013.csv` from [data.gov.in](https://data.gov.in) and place it in the project folder

**4. Launch the notebook**
```bash
jupyter notebook cybercrimefinal.ipynb
```

---

## 👤 Author

<div align="center">

**Sahil More**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/sahilmore45)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-black?style=for-the-badge&logo=github)](https://github.com/Sahil456)

</div>

---

<div align="center">

⭐ **If you found this project helpful, please give it a star!** ⭐

</div>
