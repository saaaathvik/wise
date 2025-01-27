# Women-targeted Abusive Comment Detection in Tamil - DravidianLangTech@NAACL 2025

## Overview
This project presents our submission for the **Women-targeted Abusive Comment Detection in Tamil** shared task at **DravidianLangTech@NAACL 2025**. The goal is to classify whether a given comment is abusive towards women.

We fine-tune **Google's MuRIL**, a transformer-based multilingual model, on the provided dataset to build the classification model. Our approach focuses on **preprocessing, tokenization, and model training**, leveraging **accuracy, F1-score, precision, and recall** as evaluation metrics.

## Approach
1. **Dataset Preprocessing**: Cleaning, tokenization, and formatting for model training.
2. **Model Fine-Tuning**: Using **MuRIL (Multilingual Representations for Indian Languages)** for Tamil text classification.
3. **Evaluation Metrics**: 
   - **Accuracy:** 77.76%
   - **F1-score:** 77.65%
   - **Precision & Recall:** Analyzed for model effectiveness.

## Challenges
- **Low-resource Language Constraints**: The limited availability of **large, high-quality datasets** impacts model performance.
- **Handling Code-Mixed Text**: Tamil-English mixed comments pose additional complexity.

## Results
Our model achieved **77.76% accuracy** and an **F1-score of 77.65%**, demonstrating strong performance on the given dataset.
