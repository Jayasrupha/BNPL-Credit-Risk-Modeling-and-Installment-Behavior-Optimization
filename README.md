# BNPL-Credit-Risk-Modeling-and-Installment-Behavior-Optimization
This project analyzes Buy Now Pay Later (BNPL) customer data to understand credit risk behavior and repayment patterns. It combines machine learning and statistical analysis to predict default risk and evaluate how installment structure affects borrower repayment behavior.

Business Problem

BNPL platforms face a core trade-off:

1. Short installment plans → higher monthly burden → potential repayment stress
2. Long installment plans → lower burden → higher chances of delayed or missed payments

This creates uncertainty in designing installment offerings that are both customer-friendly and financially safe.

Objective

The main goal of this project is to:
Predict whether a customer is likely to default on a BNPL payment
Understand key factors driving repayment risk
Analyze how installment duration impacts financial burden and repayment behavior
Identify an optimal installment structure that balances risk and repayment performance

Dataset Description
The dataset contains anonymized BNPL customer data such as age, income, credit score, purchase behavior, installment details, and repayment outcomes like delays, missed payments, and default status (target variable).

What This Project Does
This project solves the problem in two layers:
1. Credit Risk Prediction (Machine Learning)
Builds models to predict Probability of Default (PD)
Uses customer financial and behavioral data
Identifies high-risk users before lending decisions
2. Installment Plan Analysis
Studies how installment duration affects:
Default rate
Repayment delays
Missed payments
Repayment success
Financial burden on users
Uses statistical testing (ANOVA) to validate differences

The project helps answer:
“What is the optimal installment duration that minimizes default risk while maintaining healthy repayment behavior?”

Insight
The analysis shows that installment structure significantly impacts borrower behavior, and there exists an optimal balance between repayment success and credit risk exposure.
