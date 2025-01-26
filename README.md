# Loan Approval System  

## Overview  
The Loan Approval System is a machine learning-powered application that predicts the approval status of a loan based on user inputs. It leverages a trained neural network model and provides a secure backend using Django Rest Framework (DRF). This system ensures robust user input handling, SQL query protection, and a seamless prediction process.  

## Features  
- **Data Preprocessing**:  
  - Data cleaning and feature engineering to improve model performance.  
  - Exploratory Data Analysis (EDA) for insights into loan data.  

- **Machine Learning Model**:  
  - Neural network trained on loan data with loan approval status as the target variable.  
  - Model serialized into a `.pkl` file for deployment.  

- **Backend**:  
  - Built using Django Rest Framework for seamless integration and API creation.  
  - Security APIs implemented for SQL injection protection.  

- **Database**:  
  - SQL database for storing user inputs and loan application details.  

- **User-Friendly Design**:  
  - Inputs collected via APIs or forms.  
  - Real-time prediction of loan approval status based on user inputs.  

## How It Works  
1. **User Input**:  
   - The user provides loan-related information such as income, loan amount, credit history, etc.  

2. **Data Processing**:  
   - Input data is validated and preprocessed using the same steps applied during training.  

3. **Prediction**:  
   - The trained neural network model predicts whether the loan will be approved or not.  

4. **Database Storage**:  
   - User data and prediction results are securely stored in the SQL database.  

## Technology Stack  
- **Backend**: Django Rest Framework (DRF)  
- **Database**: SQL 
- **Machine Learning**: Neural Network, Python, Tensorflow, Jupyter notebook 
- **Frontend**: Django templates   

## Installation and Setup  
1. Clone the repository:  
   ```bash  
   git clone https://github.com/your-username/loan-approval-system.git  
   cd loan-approval-system  
