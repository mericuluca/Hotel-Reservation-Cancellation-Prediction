# **Hotel Reservation Cancellation Prediction**

## **Project Overview**

This project focuses on building and evaluating various Machine Learning models to predict the cancellation behavior of hotel guests. By accurately forecasting which reservations are likely to be canceled, hotels can optimize revenue management, minimize budget shortfalls, and improve resource allocation.

The core objective is a binary classification task: predicting the value of the is\_canceled target variable using historical booking features.

## **🎯 Problem Definition and Goal**

### **The Business Challenge**

Hotel reservation cancellations create significant operational issues:

1. **Revenue Loss:** Unexpected vacant rooms lead to unrealized revenue.  
2. **Room Mismanagement:** Occupancy charts may reflect reservations that will ultimately not materialize, preventing new bookings and frustrating potential guests.  
3. **Budgeting Uncertainty:** Managers struggle to accurately forecast short-term revenue and occupancy rates.

### **Project Goal**

This system aims to guide hotel management by providing timely and accurate cancellation predictions. This allows hotels to proactively manage overbooking strategies, re-market rooms, and prepare financial budgets with greater certainty, minimizing the grievance for both managers and potential guests.

## **🛠️ Methodology and Algorithms**

The project employed a comparative approach, training and evaluating several robust classification algorithms to determine the most effective predictive model for this dataset.

| Algorithm | Type | Purpose |
| :---- | :---- | :---- |
| **K-Nearest Neighbors (KNN)** | Instance-based | Evaluated effectiveness based on proximity of features. |
| **Support Vector Machine (SVM)** | Discriminative Classifier | Tested performance using different kernel functions for complex boundaries. |
| **Logistic Regression** | Linear Classifier | Established a fast baseline model for probability estimation. |
| **Random Forest** | Ensemble Learning | Utilized for robust performance, feature importance, and reducing overfitting. |
| **Neural Network (NN)** | Deep Learning | Explored non-linear relationships using a multi-layer perceptron architecture. |

Metrics such as accuracy, precision, recall, and F1-score were used to benchmark model performance, with a specific focus on **resilience** and generalization capability.

## **📊 Dataset Description**

The analysis utilizes a public dataset containing real-world hotel booking information.

### **Key Statistics**

* **Samples (Reservations):** 119,390  
* **Features:** 35 (including numerical and categorical data)  
* **Observation Period:** July 1, 2015, to August 31, 2017  
* **Hotel Types:** Data covers two distinct types: City Hotel and Resort Hotel.  
* **Target Variable:** is\_canceled (Binary: 1 for canceled, 0 for arrived).

### **Data Preparation**

All categorical features were processed using **One-Hot Encoding** to convert them into a format suitable for the tested machine learning models.

## **🚀 Getting Started**

*(Since code was not provided, this section offers general instructions. Please replace this with actual setup steps.)*

1. **Clone the Repository:**  
   git clone \[repository\_link\]  
   cd hotel-cancellation-prediction

2. Install Dependencies:  
   This project requires Python and common data science libraries.  
   pip install \-r requirements.txt

3. Run the Analysis:  
   The core analysis and model training are executed in prediction\_notebook.ipynb.  
   jupyter notebook  
