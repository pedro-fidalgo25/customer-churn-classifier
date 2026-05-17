# Global Initiative to Understand Worldwide Lifestyle Patterns (WHO-LIFE)

## 📌 Project Overview
This repository contains an end-to-end Machine Learning pipeline built on the World Health Organization (WHO-LIFE) dataset. The project aims to analyze, segment, and predict global citizen profiles based on behavioral, financial, and health characteristics. By uncovering geographic and social lifestyle trends, this pipeline helps design data-driven, culturally-aware public health and wellness interventions.

## 📊 Methodology & Key Highlights
1. **Robust Data Engineering:** Conducted Exploratory Data Analysis (EDA), managed structural missing values, performed outlier detection, and executed strategic feature engineering.
2. **Descriptive Modeling (Clustering):** Implemented **K-Means (3 distinct clusters)** and **Self-Organizing Maps (SOM - 6 sub-profiles)** to discover latent lifestyle archetypes, such as *“Digital Socialites”*.
3. **Predictive Modeling & Optimization:** Built multi-class classification frameworks to predict citizen segments. Benchmarked several architectures:
   * **Gradient Boosting Classifiers** (Optimized via **Optuna** hyperparameter tuning)
   * **Random Forest**
   * **Multi-Layer Perceptron (MLP)** with custom activation tuning
   * **Logistic Regression**

## 📈 Results & Performance
* **Best Model:** Gradient Boosting with hyperparameter tuning.
* **Evaluation Score:** Achieved a peak **Kaggle Score of 0.82079**, demonstrating low overfit risk and robust generalization boundaries.
* **Strategic Outcome:** Developed a data-driven action plan recommending targeted digital media marketing, regional financial wellness bundling, and dynamic dashboards for public healthcare deployment.

## 🛠️ Tech Stack & Libraries
* **Language:** Python
* **Data Pipelines & Visualization:** Pandas, NumPy, Matplotlib, Seaborn
* **Machine Learning Frameworks:** Scikit-Learn, LightGBM, GradientBoosting
* **Optimization:** Optuna
