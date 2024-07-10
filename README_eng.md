# Graduation Qualification Work

## Title: Extraction and Classification of Features from a Set of Oculography Data Using Machine Learning Methods

### Author

Kolosov I.V. (UrFU RIM-220962)

### Scientific Supervisor

Dolganov A.Yu. (UrFU)

### Links

* [Author's GitHub](https://github.com/termik88)
* [Scientific Supervisor's Profile](https://urfu.ru/ru/about/personal-pages/Personal/person/anton.dolganov/)
* [Research Notebook](https://github.com/termik88/VKR_ML/blob/main/vkr_research.ipynb)
* [Dataset](https://figshare.com/collections/Screening_for_Dyslexia_Using_Eye_Tracking_During_Reading/3521379)
* [Scientific Supervisor's Review](https://github.com/termik88/VKR_ML/blob/main/review%20-%20Scientific%20Supervisor.pdf)
* [Expert Review](https://github.com/termik88/VKR_ML/blob/main/review%20-%20Expert.pdf)
* [Full Text of the Graduation Qualification Work](https://github.com/termik88/VKR_ML/blob/main/text_vkr.pdf) 

### Description

The purpose of this research is to analyze machine learning methods for extracting and classifying features from oculography data sets to improve the accuracy of dyslexia diagnosis.

The object of study is the detection of various eye movement events from oculography data, including progressive and regressive eye movements, fixations, saccades, and types of visual fields.

The research explores the use of threshold algorithms and anomaly-based clustering methods to identify these events.

The research uses stratified cross-validation and recursive feature elimination to select the most significant features for machine learning models, as well as studying the variability of recursive feature elimination based on prediction accuracy and feature extraction probability.

#### Libraries and Technologies:

1. Pandas
2. NumPy
3. Matplotlib
4. Seaborn
5. Plotly
6. SciPy
7. Statsmodels
8. Scikit-learn
9. HDSCAN
10. XGBoost

#### Models Used:

1. Logistic Regression (LogisticRegression, LogisticRegressionCV)
2. Support Vector Machine (SVC)
3. Random Forest Classifier (RandomForestClassifier)
4. Gradient Boosting Classifier (GradientBoostingClassifier)
5 DBSCAN (Density-Based Spatial Clustering of Applications with Noise)
6. Local Outlier Factor (LOF)
7. XGBoost (Extreme Gradient Boosting)

### Results

#### Average Accuracy

0.9597701149425287

#### Confidence Interval (0.95) for Accuracy

(0.91927, 1.00000)

#### Classification Report

|  | precision | recall | f1-score | support |
| --- | --- | --- | --- | --- |
| 0.0 | 1.00 | 0.90 | 0.95 | 20 |
| 1.0 | 0.89 | 1.00 | 0.94 | 17 |
| accuracy |  |  | 0.95 | 37 |
| macro avg | 0.95 | 0.95 | 0.95 | 37 |
| weighted avg | 0.95 | 0.95 | 0.95 | 37 |

### Keywords

* Oculography
* Event Detection
* Eye Movements
* Machine Learning
* Fixations
* Saccades
* Interval Threshold
* Feature Extraction
* Classification
* Anomalies
* RFE
