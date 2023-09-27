# Heart Disease Prediction Project

## Overview
This project aims to predict the likelihood of heart disease in individuals using machine learning classifiers. Three classifiers were employed: K Nearest Neighbors, Logistic Regression, and Random Forest. The Random Forest model achieved the highest accuracy of 86.88%, followed by Logistic Regression with 85.24% accuracy. After hyperparameter tuning, Logistic Regression's accuracy slightly decreased to 83.60%. K Nearest Neighbors started with an accuracy of 65.57% and improved to 70.49% after tuning.

## Models and Accuracy
- Random Forest Classifier:
  - Initial Accuracy: 86.88%
  - Hyperparameter Tuned Accuracy: 86.88%
  - Cross-Validated Accuracy Mean: 83.57%
  - Cross-Validated Precision: 82.99%
  - Cross-Validated Recall: 85.98%
  - F1 Score (Cross-Validated): 84.52%

- Logistic Regression:
  - Initial Accuracy: 85.24%
  - Hyperparameter Tuned Accuracy: 83.60%

- K Nearest Neighbors:
  - Initial Accuracy: 65.57%
  - Hyperparameter Tuned Accuracy: 70.49%

## Confusion Matrix
The confusion matrix for the Random Forest model showed:
- True Positives: 28
- False Positives: 4
- True Negatives: 4
- False Negatives: 25

## Dataset
The data set used was UCLA heart disease dataset `https://archive.ics.uci.edu/dataset/45/heart+disease`
#### Features of data set include
* age (Age of the patient in years)
* sex (Male/Female)
* cp chest pain type ([typical angina, atypical angina, non-anginal, asymptomatic])* trestbps resting blood pressure (resting blood pressure (in mm Hg on admission to the hospital))
* chol (serum cholesterol in mg/dl)
* fbs (if fasting blood sugar > 120 mg/dl)
* restecg resting electrocardiographic results ([normal, stt abnormality, lv hypertrophy])
* thalach maximum heart rate achieved
* exang exercise-induced angina (True/ False)
* oldpeak ST depression induced by exercise relative to rest
* slope the slope of the peak exercise ST segment
* ca number of major vessels (0-3) colored by fluoroscopy
* thal [normal; fixed defect; reversible defect]
* target the predicted attribute



## Acknowledgments
Libaries Used:
* Sklearn
* Numpy
* Pandas
* Seaborn
* Matplotlib

## Future Improvements
The model will be improved upon by using a much better Algorithm and Collecting more Data For the model to learn upon in the nearest Future
## Author
- Okunlola Ayoola
- GitHub: Ayookuns1

#
