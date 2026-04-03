https://colab.research.google.com/drive/18BOKHTDOOBTA0uDDG0_IK8q_NlBWWx5U?usp=sharing
# Explainable AI for Liver Disease Prediction

## Overview

This project focuses on building an interpretable machine learning model to predict liver disease using clinical data.

This project explores interpretable machine learning for healthcare applications, aligning with current research directions in Explainable AI (XAI) and trustworthy AI systems.

The goal is not only to achieve accurate predictions but also to improve transparency and trust in machine learning models used in sensitive domains like healthcare.

---

## Dataset

* Indian Liver Patient Dataset (ILPD)
* ~580 patient records
* 10 clinical features including age, bilirubin levels, enzymes, etc.

---

## Methodology

* Data preprocessing (handling missing values, encoding categorical variables)
* Feature engineering and normalization
* Model training using Random Forest classifier
* Model evaluation using accuracy and classification metrics

---

## Explainability

* Implemented SHAP (SHapley Additive Explanations)
* Analyzed feature importance and contribution to predictions
* Improved interpretability of model decisions for healthcare applications

---

## Results

* Achieved ~70–75% accuracy with baseline model
* Identified key clinical features influencing liver disease prediction

---

## Deployment

The model is deployed as a live web application using Streamlit:

https://liver-disease-app-mus9bxy5rbklsj2lykkg4x.streamlit.app/

---

## Tech Stack

* Python
* Scikit-learn
* Pandas, NumPy
* SHAP
* Streamlit

---

## Future Work

* Improve model performance using advanced algorithms
* Explore deep learning approaches
* Enhance explainability using advanced XAI techniques
* Integrate with real-time healthcare systems

---

## Author

Milan Choudhary

