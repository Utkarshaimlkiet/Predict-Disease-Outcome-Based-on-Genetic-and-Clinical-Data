# Predict-Disease-Outcome-Based-on-Genetic-and-Clinical-Data
This project focused on predicting disease outcomes using tumor-related genetic and clinical data. We built a Logistic Regression classifier to differentiate between benign and malignant cases and evaluated the model’s performance using key metrics. Additionally, we performed K-Means clustering to segment data patterns and visualized clusters using PCA.

Key Steps & Findings:
Data Preprocessing:

Removed unnecessary columns and handled missing values using median imputation.

Scaled features using StandardScaler for better model performance.

Classification Model (Logistic Regression):

Split data into training & testing sets (80/20 split).

Trained the model using logistic regression and made predictions.

Evaluated performance using the following metrics:

Accuracy: Measures overall correctness

Precision: How many predicted malignant cases were actually malignant

Recall: Ability to detect malignant cases correctly

F1 Score: Balances precision & recall

Confusion Matrix Visualization:

Displayed model’s classification results using a heatmap to observe true positives, true negatives, false positives, and false negatives.

Clustering & Segmentation (K-Means):

Used K-Means clustering (k=2) to segment tumor samples.

Computed Silhouette Score to measure clustering quality.

PCA Visualization:

Reduced dimensionality and plotted clusters for better understanding of the dataset’s structure.

Final Insights:
✅ The classification model successfully predicts disease outcomes with high accuracy 
✅ Heatmap visualization helps analyze classification mistakes 
✅ K-Means clustering provides useful segmentation insights 
✅ PCA visualization allows for better understanding of data distribution

This project demonstrates how machine learning can be leveraged for medical diagnosis and predictive analysis. 

