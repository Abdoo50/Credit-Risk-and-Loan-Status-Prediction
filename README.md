# Credit Risk and Loan Status Prediction

## Overview
This repository contains the code and dataset for a machine learning project focused on Credit Risk Analysis and Loan Status Prediction. The primary objective is to build a model that can accurately predict the likelihood of loan default based on various financial indicators.

<p style="text-align: center;">
    <img src="https://github.com/Abdoo50/Credit-Risk-and-Loan-Status-Prediction/raw/main/Financial%20Services%20Logo.png" alt="Financial Services Project"/>
</p>

## **Context of the Problem**

One of the leading banks would like to predict bad customer while customer applying for loan. This model also called as PD Models (Probability of Default)

Credit scoring is perhaps one of the most "classic" applications for predictive modeling, to predict whether or not credit extended to an applicant will likely result in profit or losses for the lending institution. There are many variations and complexities regarding how exactly credit is extended to individuals, businesses, and other organizations for various purposes (purchasing equipment, real estate, consumer items, and so on), and using various methods of credit (credit card, loan, delayed payment plan). But in all cases, a lender provides money to an individual or institution, and expects to be paid back in time with interest commensurate with the risk of default. Credit scoring is the set of decision models and their underlying techniques that aid lenders in the granting of consumer credit. These techniques determine who will get credit, how much credit they should get, and what operational strategies will enhance the profitability of the borrowers to the lenders. Further, they help to assess the risk in lending. Credit scoring is a dependable assessment of a person’s credit worthiness since it is based on actual data.

A lender commonly makes two types of decisions: first, whether to grant credit to a new applicant, and second, how to deal with existing applicants, including whether to increase their credit limits. In both cases, whatever the techniques used, it is critical that there is a large sample of previous customers with their application details, behavioral patterns, and subsequent credit history available. Most of the techniques use this sample to identify the connection between the characteristics of the consumers (annual income, age, number of years in employment with their current employer, etc.) and their subsequent history.

Typical application areas in the consumer market include: credit cards, auto loans, home mortgages, home equity loans, mail catalog orders, and a wide variety of personal loan products.

## Features
- Analysis of financial data related to loan applications.
- Data preprocessing and feature engineering techniques.
- Implementation of machine learning models for classification.
- Evaluation of model performance using metrics such as accuracy, precision, and recall.

## Dataset
The dataset used in this project includes various financial attributes such as age, education, employment history, income, debt, credit history, and loan default status.

The dataset contains the following columns:

1. **age**: Age of the individual.
2. **ed**: Education level.
3. **employ**: Years of employment.
4. **address**: Years at the current address.
5. **income**: Annual income.
6. **debtinc**: Debt-to-income ratio.
7. **creddebt**: Credit card debt.
8. **othdebt**: Other debts.
9. **default**: Indicates if the individual has defaulted on a loan (1 for default, 0 for no default).

## Requirements
- Python 3.x
- Pandas
- NumPy
- scikit-learn
- matplotlib
- seaborn
- [Other dependencies as required by the project]

## Installation
To set up the project environment, follow these steps:
1. Clone the repository:
   ```bash
   git clone https://github.com/Abdoo50/Credit-Risk-and-Loan-Status-Prediction.git
   ```
2. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
Navigate to the Jupyter notebook `credit-risk-analysis-and-classification.ipynb` to view the analysis and model implementation. You can run the notebook to train the model and evaluate its performance.

## Contributing
Contributions to this project are welcome. Please fork the repository and submit a pull request with your proposed changes.

## License
[Specify the license or state 'This project is licensed under the MIT License - see the LICENSE.md file for details']

## Contact
For any queries or discussions related to this project, please contact:
- Abdelrahman Ashour
- [LinkedIn](https://www.linkedin.com/in/abdo-ashour-9467b623a/)

