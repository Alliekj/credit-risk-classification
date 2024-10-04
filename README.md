
# Credit Risk Classification

This is a machine learning model to predict the credit risk of a loan based on the borrower's financial data. The objective is to help financial institutions assess credit risk more effectively and make informed lending decisions.

## Overview of the Analysis

The purpose of this analysis is to evaluate the performance of a logistic regression model in predicting credit risk. The model uses various features such as loan size, interest rate, borrower income, and more to classify loans as either healthy (low risk) or high-risk (likely to default). This analysis aims to determine whether the logistic regression model is a suitable tool for assessing credit risk in a real-world scenario.

## How to Use This Project

### Prerequisites

- Python 3.x
- Jupyter Notebook
- Required Python libraries (install using the provided `requirements.txt` or the instructions below)

### Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/credit-risk-classification.git
   cd credit-risk-classification

2. **Run the Jupyter Notebook**:
   jupyter notebook Credit_Risk/credit_risk_classification.ipynb

## Running the Analysis
1. Open the notebook and run the cells in sequence. The notebook will guide you through loading the dataset, preprocessing the data, training the logistic regression model, and evaluating its performance.

## Credit Analysis Report 

**Overview of the Analysis**
This analysis focuses on using a logistic regression model to predict whether a loan is likely to be high-risk or healthy. The model is trained on a dataset that includes various financial metrics such as loan size, interest rate, borrower income, and debt-to-income ratio.

**Results**: 
Accuracy Score: 99%
Precision Score:
Healthy Loans (0): 100%
High-Risk Loans (1): 86%
Recall Score:
Healthy Loans (0): 100%
High-Risk Loans (1): 91%

**Summary**:
The logistic regression model performs well in predicting healthy loans, with an accuracy of 99% and perfect precision and recall for this class. The model is also quite effective at predicting high-risk loans, achieving a precision of 86% and a recall of 91%. This indicates that the model is highly reliable for identifying healthy loans and reasonably effective at detecting high-risk loans.

**Recommendation**: 
Based on the results, I recommend using this logistic regression model for credit risk assessment. The model’s high accuracy and strong performance in both precision and recall make it a valuable tool for financial institutions to identify risky loans and take appropriate actions. However, further improvements could be made to enhance the detection of high-risk loans, possibly by exploring additional features or more complex models.

