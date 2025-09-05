
# Artificial Intelligence & Machine Learning Training Report - Day 14
**Name:** Jeeya Thapar  
**URN:** 2303002  
**Date:** 10 July 2025  

## Overview
Today’s session introduced Logistic Regression, a machine learning algorithm used for classification tasks. Unlike linear regression, which predicts continuous values, logistic regression predicts categorical outcomes, especially binary results like Yes/No or True/False. The session also covered the sigmoid function, which converts inputs into probabilities.

## Learning Objectives
- Understand the purpose of logistic regression in classification.  
- Learn the difference between linear and logistic regression.  
- Study the sigmoid function and its role in prediction.  
- Explore how probabilities are calculated and converted into binary outputs.  

## Logistic Regression
Logistic Regression is a supervised ML algorithm used for classification.  
- Predicts probability of belonging to a class.  
- Mainly used for binary classification (0/1, Yes/No, True/False).  
- Uses the sigmoid function to map input values into a probability between 0 and 1.

  
## Types of Logistic Regression
1. **Binomial Logistic Regression** → Output has two categories (e.g., Pass/Fail, Yes/No).  
2. **Multinomial Logistic Regression** → Output has three or more unordered categories (e.g., Cat/Dog/Sheep).  
3. **Ordinal Logistic Regression** → Output has three or more categories with natural order (e.g., Low/Medium/High).  


## Sigmoid Function
The sigmoid function is used to convert real numbers into probabilities:

\[
S(x) = \frac{1}{1 + e^{-x}}
\]

- If **S(x) > 0.5** → Predict Class 1  
- If **S(x) ≤ 0.5** → Predict Class 0  

## Properties of the Sigmoid Function
1. Domain: Accepts all real numbers.  
2. Asymptotes: Approaches 1 (as x → +∞) and 0 (as x → -∞).  
3. Monotonicity: Always increasing with input.  
4. Differentiability: Differentiable, enabling gradient calculation in training.  

## Applications
- Email Spam Detection → Spam / Not Spam  
- Disease Diagnosis → Positive / Negative  
- Customer Churn Prediction → Stay / Leave  

## Conclusion
Today I learned about how Logistic Regression enables classification problems. Learning about the sigmoid function and its properties clarified how probabilities are mapped into binary outcomes. This session was very insightful, showing how ML models make yes/no decisions with confidence.
