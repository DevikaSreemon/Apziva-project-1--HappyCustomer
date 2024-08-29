**Project Summary: Customer Happiness Prediction**

**Project Overview:**
This project aims to predict customer happiness based on survey responses collected from a cohort of customers. The survey includes questions about various aspects of the customer's experience, such as delivery times, order accuracy, pricing, courier service, and ease of use of the ordering app. The goal is to build a predictive model that can classify whether a customer is happy or unhappy based on their survey responses. Achieving this goal will enable the company to take proactive measures to enhance customer satisfaction and improve overall operations.

**Objective:**
Predict customer happiness based on survey responses to identify key factors influencing satisfaction and recommend actionable improvements.

Data:
Target Variable (Y): Customer happiness (0 = unhappy, 1 = happy)
Features:
X1: Delivery timeliness
X2: Order contents
X3: Order completeness
X4: Price paid
X5: Courier satisfaction
X6: App usability

**Methodology:**
Data Preparation: Loaded the dataset and performed preprocessing, including handling missing values and encoding features.
Feature Analysis: Evaluated feature importance using a leave-one-feature-out method to assess the impact of each feature on model performance.

**Modeling:**
Nearest Centroid Model: Trained and tested with the dataset.
Feature Exclusion: Tested model performance by removing individual features to gauge their impact on accuracy.
Evaluation: Achieved an accuracy of 84.6% and a recall of 89% for unhappy customers with the Nearest Centroid model.


**Findings:**
Best Model: Nearest Centroid with 84.6% accuracy.
Feature Impact: Features X2, X3, and X4 were found to have minimal impact, with their removal improving accuracy.
Hyperparameter Tuning: Did not result in significant accuracy improvements.


**Recommendations:**
Expand Data Collection: Improve model accuracy with a larger dataset.
Optimize Survey: Focus on key questions about delivery timeliness, courier satisfaction, and app usability.
Enhance Service: Improve delivery and courier performance to boost satisfaction.

