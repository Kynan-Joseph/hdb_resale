# HDB Resale Price Prediction Web Application

Objective:
The goal of this project is to build and deploy a web application that predicts the resale price of HDB flats in Singapore based on various input features provided by the user. The application uses a machine learning model trained on historical HDB resale data.

Steps Involved:
Data Preparation and Model Training:

Exploratory Data Analysis (EDA): Performed initial analysis to understand the data, identify patterns, and clean the data.
Model Training: A machine learning model was trained using PyCaret, focusing on regression techniques to predict the resale price. The model was saved for later use in the web application.
Setting Up the Flask Application:

Environment Setup: Created a virtual environment in VS Code, installed necessary Python packages (Flask, PyCaret, Pandas), and set up the project structure.
Flask Back-End Development: Developed the back-end using Flask. The back-end loads the pre-trained model and handles user input from the front-end, passing it through the model to generate predictions.
Model Integration: Integrated the saved machine learning model into the Flask application, enabling real-time predictions based on user inputs.
Front-End Development:

HTML Form Creation: Created an HTML form that allows users to input various features such as floor area, flat type, distance to CBD, etc.
Responsive Design: Ensured the form is user-friendly, with input fields, labels, and a submit button designed for ease of use. The design is responsive and retains input values after form submission.
Prediction Display: After form submission, the predicted resale price is displayed on the same page.
Handling Errors and Improvements:

Data Type Conversion: Addressed issues such as converting the transaction_month to a datetime format, ensuring all features are correctly processed before prediction.
Error Handling: Adjusted the Flask code to handle missing columns, incorrect data types, and prediction output issues.
