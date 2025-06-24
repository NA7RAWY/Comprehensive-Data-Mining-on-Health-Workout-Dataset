# Health & Fitness Data Mining

This project explores various machine learning and data mining techniques on a health and fitness dataset. The analysis covers supervised learning (classification & regression), unsupervised learning (clustering), and pattern discovery (association rules), along with visualizations and evaluation metrics.

## 📊 Dataset Overview

The dataset includes features related to health, nutrition, and physical activity. A sample preview is shown below:

![Dataset Preview](screenshots1/02_dataset_preview.png)

---

## 🌳 Decision Tree Classifier

A Decision Tree model was trained to classify health conditions.

* **Accuracy:** 90%

* **Confusion Matrix:**
  ![Confusion Matrix - Plot](screenshots1/04_classification_conf_matrix_plot.png)
  ![Confusion Matrix - Text](screenshots1/03_classification_conf_matrix_text.png)

* **Classification Report:**
  ![Classification Report](screenshots1/05_classification_report.png)

---

## 📉 Feature Importance

The most impactful features were extracted using the Decision Tree model:

![Feature Importance](screenshots1/06_feature_importance.png)

---

## 📈 Regression Analysis

A regression model was used to predict a continuous health-related variable. Evaluation metrics:

* **Report:**
  ![Regression Report](screenshots1/07_regression_report.png)

* **Metrics:**
  ![Regression Metrics](screenshots1/08_regression_metrics.png)

* **Actual vs Predicted Plot:**
  ![Actual vs Predicted](screenshots1/09_regression_actual_vs_pred.png)

---

## 🔗 K-Means Clustering

K-Means clustering was applied to group users into clusters based on their health profile.

* **Elbow Method:**
  ![KMeans Elbow](screenshots1/10_kmeans_elbow.png)

* **Silhouette Scores:**
  ![KMeans Silhouette](screenshots1/11_kmeans_silhouette.png)

* **Final Clusters Visualization (with PCA):**
  ![KMeans Clusters](screenshots1/12_kmeans_clusters.png)

---

## 🧾 Association Rules

Both Apriori and FP-Growth algorithms were used for mining association rules from transactional health data.

* **Rules Output:**
  ![Output](screenshots1/13_apriori_vs_fpgrowth_output.png)

* **Support & Confidence Comparison:**
  ![Support-Confidence](screenshots1/14_apriori_fpgrowth_support_confidence.png)

* **Execution Time Comparison:**
  ![Time Comparison](screenshots1/15_apriori_fpgrowth_time_comparison.png)

---

## 📦 Tools & Technologies

* Python (Pandas, Scikit-learn, Matplotlib, Seaborn)
* Jupyter Notebook

---

## ✅ Conclusion

This project demonstrates a full machine learning pipeline including data preparation, model building, evaluation, and visualization. It highlights how data mining techniques can provide valuable insights to improve health and fitness decisions.
