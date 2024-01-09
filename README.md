## Breast-Cancer-Prediction
Breast cancer is a common and serious health concern for women globally. It is crucial to detect and diagnose breast cancer early to improve treatment outcomes. This project focuses on predicting breast cancer diagnosis using a dataset from Kaggle.

**About the Dataset**

The dataset includes ten real-valued features related to breast cancer, such as mean, standard error, and the "worst" or largest of these features. Diagnosis results, indicating whether a detected lump is cancerous, serve as the target variable for our predictive models.

Data: https://archive.ics.uci.edu/ml/machine-learning-databases/breast-cancer-wisconsin/wdbc.data 

Description: https://archive.ics.uci.edu/ml/machine-learning-databases/breast-cancer-wisconsin/wdbc.names


**Predictive Models**

I developed three predictive models: Decision Tree, Logistic Regression, and k-Nearest Neighbors (KNN). These models analyze the features to predict whether a detected lump is cancerous. To enhance model performance, I fine-tuned each model by experimenting with different hyperparameter values.

**Model Evaluation**

Model performance is crucial for reliable predictions. Using accuracy as the evaluation metric, I discovered that the Logistic Regression model outperformed the Decision Tree and KNN models.

- Decision Tree Accuracy: 95.32%
- KNN Accuracy: 95.91%
- Logistic Regression Accuracy: 97.66%

These accuracy scores highlight the effectiveness of the Logistic Regression model in predicting breast cancer diagnosis within the context of this project.
