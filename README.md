# Loan Prediction Project
Currently working on it

## Overview
This project aims to develop a predictive model for determining loan eligibility based on various factors such as applicant details, credit history, and demographic information. By analyzing historical loan data, we provide insights and predictions on loan approvals.

## Features
- Predicts loan approval status: approved or not approved.
- User-friendly interface for applicants to enter their details.
- Comprehensive analysis of factors affecting loan approvals.

## Project Structure
```
Loan-Prediction/
├── data/                # Contains datasets
├── notebooks/           # Jupyter notebooks for exploratory data analysis
├── src/                # Source code for the models and predictions
├── README.md           # The documentation file
└── requirements.txt     # List of dependencies
```

## Installation Instructions
1. Clone the repository:
   ```bash
   git clone https://github.com/surendra-59/Loan-Prediction.git
   cd Loan-Prediction
   ```
2. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
- Run the main application: 
   ```bash
   python src/main.py
   ```
- Input your details in the provided form, and receive predictions on your loan status.

## Models Used
- Logistic Regression
- Decision Trees
- Random Forest
- Gradient Boosting

## Results
Our model achieved an accuracy of 85% on the validation set. The Cat boost model performed the best, delivering high precision and recall rates. 

## License
