# Pregnancy Risk Prediction System

This project aims to predict and monitor pregnancy risks  using Machine Learning (ML) and mobile technologies. The system uses physiological data to make predictions and provides alerts for high-risk pregnancy. By analyzing user-inputted physiological data and the system provides personalized risk predictions and health insights to support early intervention and safer pregnancies.

# Project Overview

This project combines Machine Learning and mobile health technology to create a real-time maternal health risk prediction and monitoring system. The ML model analyzes user-inputted physiological data such as blood pressure, heart rate, and blood glucose to predict pregnancy risk levels. The mobile application serves as the interface for data input, personalized feedback, and health guidance, empowering pregnant women to manage their health proactively and complement traditional antenatal care.

# Machine Learning (ML) Part

# Data Collection

* Dataset: The project uses this [Maternal Health Risk](https://www.kaggle.com/datasets/csafrit2/maternal-health-risk-data)
* Features: The dataset includes features like age, body temperature, blood pressure, and more.

# Model Training

* Algorithm: Random Forest Classifier
* Hyperparameters:
  1. n_estimators=300
  2. random_state=42
  3. criterion=entropy
  4. max_depth=30,
  5. min_samples_leaf=5
* Training Process: The model was trained on 80% of the dataset and evaluated on the remaining 20%.

# Model Evaluation

* Accuracy: 73%
* F1 Score: 68%
* Precision: 73%
* Recall: 72%
* Confusion Matrix: Used to visualize true positives, false positives, etc.

