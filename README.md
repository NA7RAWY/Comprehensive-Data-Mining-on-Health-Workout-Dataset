# Health & Fitness Data Mining

This project explores various machine learning and data mining techniques on a health and fitness dataset. The analysis covers supervised learning (classification & regression) and unsupervised learning (clustering), along with visualizations and evaluation metrics.

## 📊 Dataset Overview

The dataset includes features related to health, nutrition, and physical activity. A sample preview is shown below:

![Dataset Preview](02_dataset_preview.png)

---

## 🌳 Decision Tree Classifier

A Decision Tree model was trained to classify health conditions.

* **Accuracy:** 90%

* **Confusion Matrix:**

  ![Confusion Matrix - Plot](04_dt_conf_matrix_plot.png)
  ![Confusion Matrix - Text](03_dt_conf_matrix_text.png)

* **Classification Report:**

  !\[Classification Report]\(Screenshot 2025-06-23 163851.png)

---

## 📈 Regression Analysis

A regression model was used to predict a continuous health-related variable. Evaluation metrics:

* **Metrics:**
  ![Regression Metrics](06_regression_metrics.png)

* **Actual vs Predicted Plot:**
  ![Actual vs Predicted](07_lr_actual_vs_pred.png)

---

## 🔍 Feature Importance

The most impactful features were extracted using the Decision Tree model:

![Feature Importance](05_feature_importance.png)

---

## 🔗 K-Means Clustering

K-Means clustering was applied to group users into clusters based on their health profile.

* **Elbow Method:**
  ![KMeans Elbow](08_kmeans_elbow.png)

* **Silhouette Scores:**
  ![KMeans Silhouette](09_kmeans_silhouette.png)

* **Final Clusters Visualization (with PCA):**
  ![KMeans Clusters](10_kmeans_clusters.png)

---

## 📦 Tools & Technologies

* Python (Pandas, Scikit-learn, Matplotlib, Seaborn)
* Jupyter Notebook

---

## ✅ Conclusion

This project demonstrates an end-to-end machine learning workflow including preprocessing, modeling, evaluation, and visualization for health and fitness data. It highlights how data mining techniques can extract actionable insights to improve wellness and lifestyle.
