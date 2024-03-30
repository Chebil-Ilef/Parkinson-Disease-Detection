
# 🧠 Parkinson's Disease Prediction Web App 

This project aims to develop a machine learning model with the capability to make accurate predictions regarding the presence of Parkinson's disease in individuals based on the analysis of their voice recordings. The model is deployed in a simple flask web app where you can enter the csv inorder to predict wether the person has PD or not.

## Problem 🎯
Parkinson's disease is a progressive neurodegenerative disorder primarily recognized for its impact on motor functions, giving rise to symptoms such as tremors, muscular rigidity, and difficulties in maintaining coordinated movements. By utilizing advanced computational techniques, this project seeks to establish a reliable tool for early detection and potential monitoring of Parkinson's disease through non-invasive voice analysis.

## Steps 📊
1. **Explore the Dataset**: Reveal the underlying trends, occurrences, and connections present in the data by identifying patterns, distributions, and relationships.
2. **Preprocessing Steps**: Remove irrelevant features, address missing values, treat outliers, encode categorical variables.
3. **Conduct Extensive Exploratory Data Analysis (EDA)**: Dive deep into bivariate relationships against the target.
4. **Model Building**: Establish pipelines for models that require scaling, implement classification models including KNN, SVM, Decision Trees and Random Forest.
5. **Evaluate and Compare Model Performance**: Utilize precision, recall,  F1-score, accuracy and cross validation score to gauge models' effectiveness.

## Requirements 📚
```bash
pip install -r requirements.txt
```

## Models 📝
Models demonstrate high accuracy and F1-scores, indicating strong performance. However, there are some differences to consider:
- Random Forest & XGBoost achieves higher metrics (BUT we might have risks of overfitting).
- K Neighbors achieves good metric less than the other two yet less risk of overfitting.
Given the performance of both models, either could be a suitable choice.

## Deployment 📲
I deployed the app as a web service using Azure free services.

Note: If the URL doesn't work, it might be due to reaching the usage limit.

## Save the Model 📦
We saved the model using pickle: parkinson-classifier-detection.pkl

## Contributions 🛠️
Feel free to fork this repository, tweak the models, or contribute to its improvement! 🌟

Any contribution or feedback is very welcome!