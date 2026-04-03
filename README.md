https://colab.research.google.com/drive/1fpVS5fsfxMJBpqRvUYMkG8iaFRTS3NbW?usp=sharing
# Explainable AI for Liver Disease Prediction

## Overview

This project focuses on building an interpretable machine learning model to predict liver disease using clinical data. The goal is not only to achieve accurate predictions but also to understand the factors influencing model decisions.

## Dataset

* Indian Liver Patient Dataset (ILPD)
* ~580 patient records
* 10 clinical features including age, bilirubin levels, enzymes, etc.

## Methodology

* Data preprocessing (handling missing values, encoding)
* Feature engineering and normalization
* Model training using Random Forest classifier
* Model evaluation using accuracy and classification metrics

## Explainability

* Implemented SHAP (SHapley Additive Explanations)
* Identified key features contributing to predictions
* Improved transparency of model decisions for healthcare use

## Results

* Achieved ~70–75% accuracy on baseline model
* Identified important clinical indicators affecting predictions

## Deployment

The model is deployed using Streamlit for real-time predictions:

https://liver-disease-app-mus9bxy5rbklsj2lykkg4x.streamlit.app/

## Tech Stack

* Python
* Scikit-learn
* Pandas, NumPy
* SHAP
* Streamlit

## Future Work

* Improve model accuracy using advanced models
* Explore deep learning approaches
* Enhance interpretability techniques

## Author

Milan Choudhary
