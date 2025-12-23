<img width="1904" height="926" alt="image" src="https://github.com/user-attachments/assets/27ce7de5-f334-417c-8f38-ac3762e04ff1" />




Heart Disease Prediction via Random Forest Classifier
This repository contains a machine learning application designed to analyze clinical patient data and predict the probability of heart disease. The system leverages the Random Forest algorithm to ensure high classification accuracy and provides a user-friendly interface for real-time diagnostics.

Project Overview
The primary objective of this project is to implement a robust predictive model that evaluates 13 distinct clinical features—including age, cholesterol levels, and maximum heart rate—to determine cardiac risk. The application is integrated with a Gradio web interface, allowing medical professionals or researchers to input patient metrics and receive immediate analytical feedback.

Technical Architecture
Algorithm: Random Forest Classifier with an ensemble of 100 decision trees.

Data Processing: Automated feature mapping and data split (80% training, 20% testing).

Evaluation: Performance is assessed through accuracy scoring and confidence intervals.

Interface: Interactive deployment via the Gradio framework for local and shared environments.

Clinical Features Analyzed
The model utilizes the following medical parameters for inference:

Demographics: Age and Sex.

Symptomatology: Chest pain type and exercise-induced angina.

Vitals: Resting blood pressure (BP), serum cholesterol, and fasting blood sugar (FBS).

Cardiac Tests: EKG results, maximum heart rate (Max HR), and ST segment analysis (Depression and Slope).

Specialized Tests: Number of major vessels (Fluoroscopy) and Thallium stress test results.

Installation and Usage
Clone the Repository:

Bash

git clone https://github.com/yourusername/heart-disease-prediction-random-forest.git
Install Dependencies:

Bash

pip install pandas scikit-learn numpy gradio
Execute the Application:

Bash

python main_script.py
License
This project is distributed under the MIT License.
