# My-Projects
Stroke Prediction Model
This repository contains an end-to-end R project for building, evaluating, and deploying a machine learning model to predict stroke risk based on healthcare data.

Project Overview
Stroke is a serious medical condition and early prediction can help in prevention and treatment. This project uses a dataset with patient demographic and health features to train models that classify the likelihood of stroke occurrence.

Key tasks include:

Data cleaning and preprocessing

Exploratory data analysis (EDA)

Building classification models: Logistic Regression, Random Forest, and SVM

Evaluating model performance

Saving the best model for deployment

Dataset
The dataset includes features such as:

Gender

Age

Hypertension

Heart disease

Ever married

Work type

Residence type

Average glucose level

BMI

Smoking status

Stroke occurrence (target variable)

Usage
Clone the repository:

bash
Copy
Edit
git clone https://github.com/yourusername/stroke-prediction.git
cd stroke-prediction
Open the R project or R Markdown file (Build-deploy-stroke-prediction-model-R.Rmd) in RStudio.

Make sure to have the dataset CSV file in the project directory or update the path in the script accordingly.

Run or knit the R Markdown file to reproduce the analysis and model training.

The trained model object is saved as stroke_rf_model.rds (Random Forest model).

Requirements
R (version >= 4.0)

R packages:

caret

randomForest

e1071 (for SVM)

dplyr

ggplot2

knitr

rmarkdown

Install packages via:

r
Copy
Edit
install.packages(c("caret", "randomForest", "e1071", "dplyr", "ggplot2", "knitr", "rmarkdown"))
Findings and Conclusions
The dataset showed an imbalance in stroke occurrence, requiring careful evaluation of models.

Random Forest performed better than Logistic Regression and SVM for this classification task.

The model achieved an accuracy around 95%, but sensitivity for detecting stroke cases was low due to class imbalance.

Further improvement could be achieved by applying techniques such as SMOTE for oversampling, hyperparameter tuning, or using ensemble methods.

License
This project is licensed under the MIT License.

