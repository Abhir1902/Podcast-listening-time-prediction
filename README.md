# 🎧 Podcast Listening Time Prediction

This repository contains my solution for the [Kaggle Playground Series - Season 5, Episode 4](https://www.kaggle.com/competitions/playground-series-s5e4) competition.

The task is to predict **Podcast Listening Time (seconds)** based on user, episode, and show metadata. It's a regression problem scored on **Root Mean Squared Error (RMSE)**.

---

## 🏁 Competition Overview

**Goal:**  
> Predict the total listening time in seconds for a user given podcast and user features.

**Metric:**  
> Root Mean Squared Error (RMSE)

**Kaggle Link:**  
[Playground Series S5E4](https://www.kaggle.com/competitions/playground-series-s5e4)

---

## 📌 Data

**Note:** Data is **not included** in this repository due to competition rules.  

To reproduce results:

1. Download `train.csv` and `test.csv` from the [Kaggle Competition Data Page](https://www.kaggle.com/competitions/playground-series-s5e4/data).
2. Place them in your working directory (or in the Kaggle Notebook environment).

---

## 🗺️ Solution Approach

The notebook `Podcast_listening_time.ipynb` contains:

- **Exploratory Data Analysis (EDA):**
  - Summary statistics
  - Distributions
  - Correlations
  - Target variable analysis

- **Data Cleaning & Preprocessing:**
  - Handling missing values
  - Encoding categorical variables
  - Feature scaling

- **Feature Engineering:**
  - Creation of new features
  - Selection of important features

- **Modeling:**
  - Baseline Linear Regression
  - Random Forest
  - XGBoost
  - LightGBM
  - (Optional) Hyperparameter tuning

- **Evaluation:**
  - Cross-validation
  - RMSE computation
  - Feature importance analysis

- **Prediction & Submission:**
  - Test set predictions
  - Creating submission CSV

---

## 🏆 Results

| Model             | CV RMSE (Example) |
| ----------------- | ----------------- |
| Linear Regression | 13.5     |
| **XGBoost**           | **12.81**     |
| LightGBM          | 13.2     |

## 🧪 How to Run

You can run the notebook on Kaggle or locally.


### ✅ On Kaggle

- Fork the notebook
- Add the competition dataset
- Run all cells

---

### ✅ Locally

1. Clone the repository:
   ```
   git clone https://github.com/Abhir1902/Podcast-listening-time-prediction.git
   cd Podcast-listening-time-prediction
2. Install requirements:
   ```
   pip install -r requirements.txt
3. Ensure you have the train.csv and test.csv files.
4. Open the notebook:
   ```
   jupyter notebook Podcast_listening_time.ipynb
5. Run all cells.

---

### 📌 Requirements

Example requirements.txt contents:
  ```
       pandas
       numpy
       scikit-learn
       matplotlib
       seaborn
       xgboost
       lightgbm
  ```
You can install everything at once with:
   ```
   pip install -r requirements.txt
   ```
---

### 🎯 Key Learnings / Highlights

* Importance of data cleaning and feature engineering for regression tasks

* Use of tree-based models for tabular data

* Model interpretability via feature importance

* Automated hyperparameter tuning (if included)

* Generating Kaggle-ready submission CSV   

---

### 📸 Example Notebook Sections

* Notebook contains the following logical sections:

* Introduction & Problem Statement

* Exploratory Data Analysis

* Data Preprocessing

* Feature Engineering

* Model Building and Evaluation

* Submission Generation

---

### 🤝 Contributing

This is a solo competition solution notebook.
PRs are welcome for:

* Improved feature engineering

* Better model ensembling

* Cleaner notebook formatting

---

### 📬 Contact

* Author: Abhir Mirikar

* GitHub: [Abhir1902](https://github.com/Abhir1902)

* Kaggle: [Your Kaggle Profile](https://www.kaggle.com/abhirmirikar)

  
