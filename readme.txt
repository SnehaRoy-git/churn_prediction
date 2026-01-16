PROJECT TITLE
-------------
Customer Churn Prediction using Recurrent Neural Network (RNN)


PROJECT DESCRIPTION
-------------------
This project aims to predict whether a customer will stay with or leave a company using a Recurrent Neural Network (RNN).  
The model is trained on a customer churn dataset and deployed using Streamlit to provide an interactive web application for real-time predictions.

RNNs are used to capture sequential patterns and dependencies in the data, helping improve churn prediction accuracy.


PROJECT STRUCTURE
-----------------
The project consists of three major components:

1. Model Training
2. Model Prediction
3. Model Deployment using Streamlit


1. MODEL TRAINING
-----------------
- The customer churn dataset is preprocessed by:
  - Handling missing values
  - Encoding categorical features
  - Scaling numerical values
- A Recurrent Neural Network (RNN) architecture is designed.
- The model is trained on historical customer data.
- Learned temporal and sequential patterns related to customer behavior.
- The trained model is saved for future predictions.


2. MODEL PREDICTION
-------------------
- The saved RNN model is loaded.
- New customer input data is provided to the model.
- The model predicts whether the customer will:
  - Stay with the company, or
  - Leave the company (Churn).
- Prediction results are clearly displayed.


3. MODEL DEPLOYMENT USING STREAMLIT
----------------------------------
- Streamlit is used to build a web-based interface.
- Users can enter customer details through interactive input fields.
- The deployed RNN model processes the input data.
- The application instantly displays churn prediction results.
- Enables easy access without technical expertise.


TECH STACK
----------
Programming Language:
- Python

Libraries & Frameworks:
- NumPy
- Pandas
- Scikit-learn
- TensorFlow / Keras
- Streamlit
- Matplotlib / Seaborn (for visualization, if used)

Tools:
- Jupyter Notebook
- VS Code


DATASET
-------
- Customer Churn Dataset
- Contains customer demographic data, service usage details, and account information.

--------------
Author Name: Sneha Roy
Gmail: sneharoy2004s@gmail.com
linkdin: https://www.linkedin.com/in/sneha-roy-00093b371
Project Title: ANN-Based Customer Churn Prediction  
Domain: Machine Learning / Deep Learning  
Deployment Tool: Streamlit  


