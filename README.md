# Research Abstract - Analyzing Loan Default Risk

Loan defaults create major risks for both lenders and borrowers, making precise risk prediction vital for responsible lending. This project demonstrates how machine learning can guide more personalized lending choices and how feature-level insights can help both parties lower their financial risk.

This project explores the use of supervised machine learning to predict the probability of mortgage default based on borrower and loan characteristics. This study utilizes Freddie Mac datasets. A comprehensive dataset is created by merging the Origination File and Performance File 

A machine learning model was developed to predict whether borrowers will default, estimate the probability of default, and identify key risk factors influencing these outcomes. In addition, exploratory data analysis and visualization were performed to reveal trends between loan features and default risk. 

Additionally, I developed a personalized risk assessment tool, providing targeted financial advice based on the individual’s input profile. Risk Meter leaps this study into real world application.

# Data Analysis explanation:
Default Risk is directly proportional to DTI
Default Risk is directly proportional to CLTV Score
Default Risk is inversely proportional to Credit Score
Default Risk is directly proportional to Interest Rate
Default Risk is directly proportional to Mortgage Insurance

# Methodology explanation:
Get Single Family loan datasets from Freddie Mac and merge data
Perform data engineering techniques to clean, encode and normalize data for modelling
Perform feature engineering and select features required for machine learning
Calculate delinquency flag for loan outstanding for >= 90 days
Split data into train and test datasets into 80:20 ratio
Train and Test the model and calculate accuracy matrix
Use SHAP techniques to add explanation

# Result explanation:
Default Risk High - Credit Score: 710, CLTV: 65, DTI: 50, Interest: 2.8%
Default Risk Moderate - Credit Score: 722, CLTV: 89, DTI: 40, Interest: 2.8%
Default Risk Low - Credit Score: 797, CLTV: 48, DTI: 35, Interest: 2.7%

# Control Case:
Features - Credit Score: 700, CLTV: 78, DTI: 38, Interest: 2.9%, Mortgage Insurance (MI): 20%, # of Borrowers: 2 - Default Probability: 49.85%

Default Probability decreases to 44.43% when credit score increases to 710
Default Probability increases to 57.36% when CLTV score increases to 88
Default Probability increases to 57.47% when DTI increases to 48
Default Probability increases to 64.04% when interest rate increases to 3.9%
Default Probability decreases to 49.68% when CLTV MI increases to 30%
Default Probability decreases to 25.77% when # of Borrowers increases to 3

# Technology Stack:
Jupyter Notebook version 7.2.2
Python version 3.12.7
Python library matplotlib version 3.9.2
Python library pandas version 2.2.2
Python library seaborn version 0.13.2
Python library sciket-learn version 1.5.1
GitHub and GitHub desktop version 3.5.2

# Conclusion:
A machine learning model can predict the probability of default, and identify key risk factors influencing these outcomes. In addition, exploratory data analysis and visualization can reveal trends such as how default rates vary across economic drivers and to examine relationships between loan features and default risk. These combined approaches provide valuable insights that enhance risk assessment and support better decision-making for lenders and borrowers alike.

# Mentions:
I want to thank Dr. Pradip Nandi at BMO Bank for his consistent guidance throughout the duration of this project. I would like to thank Mr. Tobin and Mrs. Pasquesi for sponsoring the SPARK internship program at Adlai E. Stevenson High School, Lincolnshire, IL.
