# WCB Injury Classification: Predicting Claim Injury Types (2020–2022)
**Academic Note**: This project was developed as part of the Master's in Data Science at NOVA IMS and received the highest possible grade (20/20).

This repository contains the implementation of a machine learning project developed as part of the Master's in Data Science and Advanced Analytics at NOVA IMS. The objective is to support the New York Workers’ Compensation Board (WCB) in automating the classification of injury types for workplace claims.

## Project Overview

The New York Workers’ Compensation Board (WCB) is responsible for administering and regulating benefits related to workers' compensation, disability, volunteer firefighters, ambulance workers, and civil defence personnel. Since 2000, the WCB has reviewed over five million claims, with each new claim requiring a classification of the injury type. The current manual review process is labor-intensive and time-consuming.

To address this challenge, the WCB provided a labeled dataset of claims submitted between 2020 and 2022. The goal is to develop a classification model capable of predicting the appropriate **Claim Injury Type** for each new claim. This system is intended to serve as a decision-support tool, improving the efficiency and consistency of the WCB’s operations.

## Objectives

- Develop an end-to-end supervised learning pipeline for injury type classification.
- Compare multiple candidate models using a consistent and rigorous model assessment strategy.
- Select the most generalizable model based on performance metrics and validation techniques.

## Methodology

The project follows a standard machine learning workflow:
- **Data Preprocessing**: Handling missing values, encoding categorical variables, and feature selection.
- **Model Training**: Implementation and tuning of various classification algorithms (e.g., logistic regression, random forests, gradient boosting).
- **Model Evaluation**: Cross-validation and performance metrics including accuracy, precision, recall, and F1-score.
- **Model Selection**: Comparison of results to identify the best-performing model for generalization.

## Technologies and Tools

- Python (Pandas, NumPy, Scikit-learn)
- Jupyter Notebooks
- Data visualization libraries (Matplotlib, Seaborn)

## Dataset

The dataset comprises all claims assembled by the WCB from 2020 to 2022, including structured features and the target variable (Claim Injury Type). Due to privacy and regulatory considerations, the dataset is not included in this repository.

## Status

This project is complete and was submitted as part of a Master's-level academic evaluation. All code and documentation refer to the project as developed and finalized during the course.


