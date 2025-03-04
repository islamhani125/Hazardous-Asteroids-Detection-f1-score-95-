# 🚀 Hazardous Asteroids Detection 🌌

## 📌 Overview

Asteroids pose potential threats to Earth, making it crucial to classify them as **hazardous or non-hazardous** based on their physical and orbital characteristics. This project utilizes machine learning to develop a **highly accurate asteroid classification model**, achieving an **F1 Score of 95%**.

This repository contains:

- **Data preprocessing and feature engineering techniques** to enhance model performance.
- **Machine learning models** for asteroid classification.
- **Evaluation metrics**, including confusion matrices and learning curves.

## 📂 Dataset Description

The dataset consists of various features related to asteroid properties:

- **Orbital Elements:** Semi-major axis, eccentricity, inclination, etc.
- **Physical Characteristics:** Absolute magnitude, estimated diameter, albedo.
- **Close Approach Data:** Minimum orbit intersection distance (MOID), relative velocity.
- **Target Variable:**
  - `1` → **Hazardous Asteroid**
  - `0` → **Non-Hazardous Asteroid**

## 🛠 Approach & Methodology

1. **Exploratory Data Analysis (EDA):**

   - Identified key trends in asteroid characteristics.
   - Visualized class distribution and feature correlations.

2. **Feature Engineering & Selection:**

   - Removed irrelevant and redundant features.
   - Scaled numerical data for better model performance.

3. **Model Training & Evaluation:**

   - Used **Random Forest Classifier** as the primary model.
   - Tuned hyperparameters to optimize classification accuracy.
   - Evaluated results using **Confusion Matrix, F1 Score, and Learning Curve**.

## 📊 Key Findings & Insights

✅ Achieved **95% F1 Score**, balancing precision and recall effectively.\
✅ Identified **important features** affecting asteroid classification.\
✅ The **Random Forest model** outperformed other classifiers in terms of accuracy and robustness.\
✅ Learning curves indicate **minimal overfitting** and strong generalization.

## 📌 Conclusion

This project showcases the **power of machine learning** in space science and planetary defense. The high F1 score reflects the model's ability to **accurately predict hazardous asteroids**, which could aid in future space monitoring and exploration.

🌟 Feel free to contribute, raise issues, or share feedback! Let's build a safer space together. 🚀

