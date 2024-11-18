# **Rock vs Mine Prediction Project**

This project focuses on building a machine learning model to classify objects detected by sonar signals as either **rocks** or **mines**. Using data preprocessing, exploratory analysis, and predictive modeling, this project demonstrates how to handle binary classification tasks in Python.

## **Table of Contents**
1. [Dataset Description](#dataset-description)
2. [Technologies Used](#technologies-used)
3. [Steps Involved](#steps-involved)
4. [Results](#results)
5. [How to Run the Project](#how-to-run-the-project)
6. [Acknowledgments](#acknowledgments)

---

## **Dataset Description**
- **Name:** Sonar Data for Rock vs Mine Prediction
- **Structure:** Contains sonar signal data with features representing frequency values.
  - **Input:** 60 numeric features representing sonar frequencies.
  - **Output:** Binary label (`Rock` or `Mine`).

---

## **Technologies Used**
- **Language:** Python
- **Libraries:**
  - Pandas
  - NumPy
  - Scikit-learn

---

## **Steps Involved**
1. **Data Loading:**
   - Imported the dataset using `Pandas`.

2. **Data Preprocessing:**
   - Split the dataset into training and testing sets.

3. **Model Selection:**
   - Used classification algorithms like Logistic Regression.
   - Evaluated the performance using metrics such as accuracy.

4. **Model Training and Evaluation:**
   - Trained the model on the training set.
   - Tested the model's performance on the test set.

7. **Prediction and Conclusion:**
   - Predicted labels (`Rock` or `Mine`) for new sonar signals.

---

## **Results**
- **Accuracy:** Achieved an accuracy of around `76%` on testing data and around `83%` on training data.
- **Insights:** The model effectively classifies sonar signals, demonstrating the power of machine learning in real-world problems.

---

## **Acknowledgments**
- I would like to thank Siddhardan for his insightful YouTube tutorials.
