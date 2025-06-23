
# 🧠 Health & Fitness Data Mining Project

This project applies various **machine learning and data mining techniques** to a health and fitness dataset to uncover patterns, make predictions, and cluster users based on fitness and lifestyle factors.

---

## 📊 Dataset Preview

The dataset includes attributes like:
- Demographics: Age, Gender
- Physical Stats: Weight, Height, BMI
- Workout Habits: Frequency, Duration, Type
- Health Metrics: BPM (Avg & Max), Calories Burned, Water Intake

![Dataset](screenshots/02_dataset_preview.png)

---

## 🔍 Classification – Decision Tree

Using a Decision Tree Classifier to categorize individuals based on their health/fitness level.

**Accuracy:** 90%  
**Best Class Performance:** Class 3 (F1 = 1.00)

📌 Metrics:
![Confusion Matrix Text](screenshots/03_dt_conf_matrix_text.png)  
📊 Visual:
![Confusion Matrix Plot](screenshots/04_dt_conf_matrix_plot.png)

---

## 📈 Feature Importance (Random Forest)

Top contributing features in classification:
- Fat Percentage
- Session Duration
- Workout Frequency
- Calories Burned

![Feature Importance](screenshots/05_feature_importance.png)

---

## 📉 Regression – Predicting a Continuous Outcome

### Linear Regression
- R² Score: 0.82
- MAE: 2.86
- RMSE: 3.90

### Decision Tree Regressor
- R² Score: 0.93
- MAE: 1.52
- RMSE: 2.50

📋 Metrics:
![Regression Metrics](screenshots/06_regression_metrics.png)  
📈 Linear Regression Result:
![LR Plot](screenshots/07_lr_actual_vs_pred.png)

---

## 📊 Clustering (K-Means)

### 1. Elbow Method  
![Elbow](screenshots/08_kmeans_elbow.png)

### 2. Silhouette Score  
![Silhouette](screenshots/09_kmeans_silhouette.png)

### 3. Final Clusters Visualized with PCA  
![Clusters](screenshots/10_kmeans_clusters.png)

---

## 🧰 Tech Stack

- Python
- Scikit-learn
- Pandas / NumPy / Matplotlib / Seaborn
- Jupyter Notebook

---

## 📬 Contact

[GitHub – NA7RAWY](https://github.com/NA7RAWY)
