# ☁️ ML Workflow For Scones Unlimited On Amazon SageMaker

## Project Overview

This project focuses on developing an automated machine learning pipeline using **AWS SageMaker** to process data, train models, and deploy scalable inference solutions for **Scones Unlimited**. The primary goal was to build an end-to-end ML workflow that automates data preprocessing, model training, deployment, and monitoring. The solution integrates AWS services such as **S3, Lambda, Step Functions, and CloudWatch** to ensure efficiency, scalability, and cost-effectiveness.

This project is the fifth project of the **"AWS AI & ML Scholarship"** program.

---

## Features

- Automated data ingestion and preprocessing using AWS Lambda and Step Functions.
- Model training and hyperparameter tuning with AutoGluon in AWS SageMaker.
- Deployment of a scalable inference endpoint using AWS SageMaker.
- Continuous monitoring with AWS Model Monitor to track model performance and detect drift.
- Full automation of the ML pipeline using serverless AWS services.

---

## Project Summary

### Section 1: Data Preprocessing and Feature Engineering

#### Data Ingestion and Processing
- The dataset is sourced and stored in **AWS S3** for scalable access.
- Data preprocessing steps include:
  - Cleaning and transforming raw data into a suitable format for ML.
  - Feature engineering to extract key insights and improve predictive power.
  - Automating the entire process using **AWS Lambda** and **Step Functions**.

#### Data Exploration
- Exploratory Data Analysis (EDA) was conducted to understand trends and correlations.
- Visualizations using **Matplotlib** and **Seaborn** to analyze feature distributions.
- Categorical features were encoded, and missing values were handled effectively.

### Section 2: Model Training and Optimization

#### Training Pipeline
- Models were trained using **AutoGluon TabularPredictor**, which automates model selection and hyperparameter tuning.
- Various machine learning algorithms were evaluated to optimize performance.
- AWS SageMaker was used to train models efficiently with distributed computing.

#### Model Evaluation
- Performance was assessed using cross-validation and error metrics such as RMSE and R².
- Best-performing models were selected based on leaderboard scores.
- Multiple iterations were conducted to refine the model.

### Section 3: Deployment and Monitoring

#### Deployment
- AWS Lambda functions were used to trigger inference and serve predictions efficiently.

#### Monitoring and Maintenance
- AWS Model Monitor was implemented to track model drift and performance metrics.
- CloudWatch was used to log and visualize model performance over time.
- Retraining strategies were developed to adapt to new data patterns.

---

## Key Achievements

- Successfully developed an automated ML pipeline with minimal manual intervention.
- Achieved scalable deployment with AWS SageMaker, handling real-time inference efficiently.
- Integrated model monitoring for proactive issue detection and performance tracking.

---
