# PUBG Winner Prediction 🎮

## Project Overview

This project focuses on predicting the **win placement percentage (winPlacePerc)** of players in PUBG matches using machine learning techniques.
By analyzing player performance metrics such as movement distance, combat activity, and survival strategies, the model predicts how well a player will rank in a match.

The project includes **data analysis, feature engineering, and model comparison** to determine the best predictive model.

---

## Objectives

* Perform **Exploratory Data Analysis (EDA)** on PUBG match data
* Identify key factors affecting player survival and ranking
* Build machine learning models to predict **winPlacePerc**
* Compare model performance to select the best model

---

## Dataset

Dataset used: **PUBG Finish Placement Prediction Dataset**

Features include:

* Player kills
* Damage dealt
* Walking distance
* Healing items used
* Boost items used
* Match duration
* Match type

Target variable:

* `winPlacePerc` – Final placement percentile in the match.

---

## Exploratory Data Analysis

The analysis includes:

* Correlation heatmap of features
* Movement vs survival analysis
* Combat performance analysis
* Match type analysis
* Outlier detection
* Target distribution visualization

These insights help understand **which factors influence player ranking the most**.

---

## Machine Learning Models

The following models were trained and evaluated:

* Linear Regression
* Random Forest
* Gradient Boosting
* XGBoost
* LightGBM

### Best Performing Model

**LightGBM (Tuned)**

Performance:

* R² Score: **0.9342**
* MAE: **0.0561**
* RMSE: **0.0788**

LightGBM achieved the best balance between **accuracy and training speed**.

---

## Key Insights

* **Movement distance** strongly influences survival and final ranking.
* Players who use **healing and boost items strategically** tend to finish higher.
* Aggressive combat alone does not guarantee better placement.
* **Balanced gameplay (movement + survival strategy)** leads to better outcomes.

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* XGBoost
* LightGBM
* Jupyter Notebook

---

