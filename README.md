# Loan Default Prediction

This project aims to predict the likelihood of a customer defaulting on a loan using machine learning models. The dataset includes various features such as personal information, loan details, and credit history. The goal is to build a model that accurately predicts defaults, helping financial institutions manage risk more effectively.

## Table of Contents

- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Modeling Approach](#modeling-approach)
- [Feature Engineering](#feature-engineering)
- [Evaluation](#evaluation)
- [Results](#results)
- [Conclusion](#conclusion)
- [Contributing](#contributing)
- [License](#license)

## Project Overview

The project utilizes various machine learning techniques to predict whether a customer will default on their loan. The Random Forest classifier was identified as the most effective model after comparison with logistic regression, based on performance metrics like the confusion matrix and ROC curve.

## Dataset

The dataset includes features such as:
- `person_age`: The age of the person.
- `person_income`: The income of the person.
- `person_home_ownership`: The home ownership status.
- `person_emp_length`: The length of employment.
- `loan_intent`: The intent of the loan.
- `loan_grade`: The grade assigned to the loan, encoded ordinally.
- `loan_amnt`: The amount of the loan.
- `loan_int_rate`: The interest rate of the loan.
- `loan_status`: The status of the loan (target variable).
- `loan_percent_income`: The percentage of income that the loan payment represents.
- `cb_person_default_on_file`: Whether the person has previously defaulted.
- `cb_person_cred_hist_length`: The length of the person’s credit history.

## Installation

To run this project locally, ensure you have the following dependencies installed:

```bash
pip install -r requirements.txt
