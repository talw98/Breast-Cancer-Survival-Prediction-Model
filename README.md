# Breast-Cancer-Survival-Prediction-Model
Predicting whether a breast cancer patient survives after surgery using Machine Learning.

*This project was done on Google Colab and has been now uploaded here on Github.*
## Background

Accurately predicting the survival rate of breast cancer patients is a major issue for cancer researchers. Machine learning (ML) has attracted much attention with the hope that it could provide accurate results, but its modeling methods and prediction performance remain controversial, in this article published on [PubMed.](https://pubmed.ncbi.nlm.nih.gov/33861809/)

## Dataset

The dataset used for this task consists of 400 patients who underwent breast cancer surgery. The dataset contains various features such as patient ID, age, gender, protein expression levels, tumor stage, histology, ER, PR, and HER2 status, surgery type, date of surgery, date of last visit, and patient status. The dataset was obtained from [Kaggle.](https://www.kaggle.com/datasets/amandam1/breastcancerdataset)

## Data Preprocessing

To preprocess the dataset, the following steps were taken:

1. Required libraries such as Pandas, NumPy, Plotly, ScikitLearn etc. were imported.
2. Null values in each column were checked and dropped.
3. Some insights about the dataset were printed such as the number of males and females in the dataset, tumor stage, histology of patients, ER, PR, and HER2 status of the patients, and different surgery types.
4. The dataset has a lot of categorical values and categorical columns, so it needs to be converted into numerical so that the machine learning model can be trained on it.
5. The code then maps the categorical data to numerical values.

## Model Training

The SVM algorithm was used to train the model. The SVM is a supervised machine learning algorithm that is commonly used for classification problems. The SVM algorithm was trained on the preprocessed dataset to predict whether a breast cancer patient will survive or not after surgery.

## Conclusion
This project aims to predict the survival rate of breast cancer patients using machine learning. The dataset was preprocessed by dropping null values, converting categorical data to numerical values, and training the SVM algorithm. Accurately predicting the survival rate of breast cancer patients is crucial for clinical decision-making and this project provides a step towards achieving this goal.
