# A-Comparative-Study-Of-Classification-Models-SVM-D-Tree-KNN

This repository presents a comparative study of three widely used classification algorithms: **Support Vector Machine (SVM)**, **Decision Tree**, and **K-Nearest Neighbors (KNN)**. The study uses the dataset `diabetes_binary_health_indicators_BRFSS2015.csv`, which contains health indicators related to diabetes, to evaluate and compare the performance of each algorithm in predicting diabetes.

## Dataset

The dataset used for this project is **"diabetes_binary_health_indicators_BRFSS2015.csv"**, which contains health-related data collected from the 2015 Behavioral Risk Factor Surveillance System (BRFSS). The dataset is labeled for binary classification, with the target variable indicating whether an individual has been diagnosed with diabetes or not.

### Features in the dataset include:
- **Physical health indicators** (e.g., BMI, physical activity, sleep)
- **Demographic information** (e.g., age, gender)
- **Health conditions** (e.g., high blood pressure, high cholesterol)
- **Behavioral habits** (e.g., smoking, alcohol consumption)

The primary goal of this study is to determine which classification algorithm performs best in predicting diabetes based on these health indicators.

## Algorithms Compared

### 1. **Support Vector Machine (SVM)**
SVM is a supervised learning model used for classification tasks. It works by finding the hyperplane that best separates the data points into different classes.

### 2. **Decision Tree**
A Decision Tree is a non-parametric supervised learning method that partitions the data into subsets based on the most significant features for prediction.

### 3. **K-Nearest Neighbors (KNN)**
KNN is a simple, instance-based learning algorithm that classifies a data point based on the majority class of its nearest neighbors.

### Files:
- `diabetes_binary_health_indicators_BRFSS2015.csv`: The dataset used in this study.
- `code.ipynb`: This ipynb file contains Python scripts for implementing each classification algorithm.
- `project report.docx`: The word file contains the extensive report of xploratory data analysis (EDA), model training, evaluation, and comparison of the classification algorithms.

## Evaluation Metrics

The models are evaluated using the following performance metrics:
- **Accuracy**: Overall performance of the model in correctly classifying instances.
- **Precision**: The accuracy of the positive predictions.
- **Recall**: The ability of the model to find all the positive instances.
- **F1 Score**: A balance between precision and recall.
- **Confusion Matrix**: Visualization of the true positives, true negatives, false positives, and false negatives.

## Results

The comparative analysis provides insights into the strengths and weaknesses of each algorithm when applied to the diabetes dataset. This study aims to guide the selection of appropriate models for similar classification tasks.

## Conclusion

This project demonstrates a thorough comparison of three classification models in the context of diabetes prediction. By examining performance metrics, users can gain a better understanding of which algorithm suits their specific needs for binary classification problems.

Thank You!
