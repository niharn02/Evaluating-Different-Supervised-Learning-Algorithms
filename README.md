# Evaluating Different Supervised Learning Algorithms

## About the Project

In this project, I compared six commonly used supervised learning algorithms on two different classification problems: **Heart Disease Prediction** and **Loan Approval Prediction**.

The main idea was to see how different machine learning algorithms perform on different datasets and whether tuning their parameters can improve their performance.

For each dataset, I trained the models with their default parameters first and then used **GridSearchCV** to find better hyperparameter combinations. I then compared the results using different evaluation metrics.

## Algorithms Used

The following six algorithms were used in this project:

* Logistic Regression
* Decision Tree
* Random Forest
* Support Vector Machine (SVM)
* K-Nearest Neighbors (KNN)
* AdaBoost

## Datasets

### Heart Disease Dataset

The Heart Disease dataset is used to predict whether a person has heart disease based on different medical and clinical features.

Dataset: [Heart Disease Prediction – Kaggle](https://www.kaggle.com/datasets/rishidamarla/heart-disease-prediction/data)

### Loan Approval Dataset

The Loan Approval dataset is used to predict whether a loan application will be approved based on information about the applicant.

Dataset: [Loan Status Prediction – Kaggle](https://www.kaggle.com/datasets/bhavikjikadara/loan-status-prediction)

## What I Did

For both datasets, I followed a similar process:

1. Loaded and explored the dataset.
2. Cleaned and prepared the data for modelling.
3. Encoded categorical variables where necessary.
4. Scaled the features where required.
5. Split the data into training and testing sets.
6. Trained six different classification models using their default parameters.
7. Evaluated the models using Accuracy, Precision, Recall and F1-Score.
8. Used GridSearchCV for hyperparameter tuning.
9. Trained the models again using the best parameters.
10. Compared the default and tuned models to see how their performance changed.

## Evaluation Metrics

I used the following metrics to compare the models:

* **Accuracy** – How many predictions were correct overall.
* **Precision** – How many of the predicted positive cases were actually positive.
* **Recall** – How many of the actual positive cases were correctly identified.
* **F1-Score** – A combined measure of precision and recall.

Looking at multiple metrics helped me understand the models better instead of judging them only by their accuracy.

## Tools & Libraries

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn
* Jupyter Notebook

## Project Files

The repository contains separate notebooks for the two datasets:

* `Heart Disease Dataset.ipynb`
* `Loan Approval Dataset.ipynb`

The datasets used in the analysis are also included in the repository.

## Conclusion

This project helped me understand how different classification algorithms behave when applied to different datasets. It also gave me practical experience with data preprocessing, model evaluation and hyperparameter tuning using GridSearchCV.

One of the main things I learned from the comparison is that there isn't necessarily one algorithm that works best for every dataset. The performance can change depending on the dataset and the way the model is configured.


## License

The code in this repository was developed as part of my MSc Computer Science project at the University of Liverpool and is licensed under the MIT License.

The datasets used in this project are sourced from Kaggle and remain subject to their respective licenses and terms of use.
