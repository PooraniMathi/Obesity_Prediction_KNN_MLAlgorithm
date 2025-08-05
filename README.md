# Obesity_Prediction_KNN_MLAlgorithm
To predict the obesity based on the records using K-Nearest Neighbor Machine Learning Algorithm.

Obesity Prediction using K-Nearest Neighbors (KNN)
1. Objective:
The objective of this project is to classify individuals based on obesity levels using the K-Nearest Neighbors (KNN) algorithm. This predictive model helps identify and categorize obesity-related health risks based on lifestyle and physiological attributes.
2. Dataset Description:
The dataset includes features relevant to obesity such as:
•	Age
•	Gender
•	Height
•	Weight
•	Family history of overweight
•	Physical activity
•	Daily water intake
•	Transportation mode
•	Eating habits
•	Obesity Level (Target variable)
3. Libraries Used:
The following Python libraries were used:
•	numpy
•	pandas
•	matplotlib
•	seaborn
•	scikit-learn
4. Data Preprocessing:
Preprocessing steps included handling missing values, encoding categorical features using Label Encoding or One-Hot Encoding, and normalizing the data to ensure all features contribute equally to the KNN distance metric.
5. Data Visualization:
Visualizations such as bar plots, histograms, and correlation heatmaps were used to analyze data distributions and feature relationships. This step helped in understanding class imbalance and feature importance.
6. Model Building:
The K-Nearest Neighbors algorithm was employed for classification. The dataset was split into training and testing sets. The optimal number of neighbors (k) was chosen based on accuracy and error rate evaluation. Distance-based classification was used to assign obesity levels to individuals.
7. Model Evaluation:
The performance of the KNN model was evaluated using:
•	Accuracy
•	Confusion Matrix
•	Precision
•	Recall
•	F1-Score
Cross-validation may also have been used to ensure model robustness.
8. Conclusion:
The KNN-based obesity prediction model accurately classifies individuals into obesity levels based on various health and lifestyle features. The simplicity and effectiveness of KNN make it suitable for medical classification problems where interpretability and accuracy are essential.

