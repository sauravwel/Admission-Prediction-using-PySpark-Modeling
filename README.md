# PySpark Admission Predictor using GRE Score, TOEFL Score, University Rating, SOP, LOR, CGPA, Research

This repository contains code for predicting the likelihood of admission using PySpark, a powerful framework for distributed data processing. The solution leverages machine learning algorithms, specifically linear regression, to train a model on several key input variables, including GRE Score, TOEFL Score, University Rating, SOP, LOR, CGPA, Research, and Chance of Admit. The repository also includes the code and data necessary to replicate the analysis and make predictions.

## Overview
The PySpark Admission Predictor is designed to provide a scalable, high-performance solution for predicting the likelihood of admission based on various input variables. PySpark is used to process large data sets and train a machine learning model that can predict the chances of admission based on the input variables.

The input variables used to train the model include:

GRE Score: The Graduate Record Examination (GRE) score is a standardized test that measures quantitative reasoning, verbal reasoning, and analytical writing skills.

TOEFL Score: The Test of English as a Foreign Language (TOEFL) score measures English language proficiency.

University Rating: The university rating is a measure of the quality of the university where the student received their undergraduate degree.

SOP: The Statement of Purpose (SOP) is a written essay that describes the student's goals, aspirations, and motivation for pursuing graduate studies.

LOR: The Letter of Recommendation (LOR) is a written statement from a professor or supervisor that provides insight into the student's academic abilities and potential.

CGPA: The Cumulative Grade Point Average (CGPA) is a measure of the student's academic performance throughout their undergraduate studies.

Research: A binary variable that indicates whether the student has prior research experience.

Chance of Admit: The probability of the student being admitted to the graduate program.

The model was trained using Linear Regression algorithm and the model achieved a root mean squared error (RMSE) of 0.05 and an R-squared (R2) value of 0.82 on the test data.

### Getting Started
To get started with the PySpark Admission Predictor, follow these steps:

Clone the repository to your local machine: git clone https://github.com/<username>/<repo-name>.git

Install PySpark and other dependencies.

Run the admission_predictor.py script to train the machine learning model and make predictions.

Files
The repository contains the following files:

README.md: This file, which provides an overview of the repository and instructions for getting started.

Admission....py: The Python script that trains the machine learning model and makes predictions.

admission_data.csv: The data file used to train the model. It contains information on several key input variables and the corresponding chance of admission.


## Usage

To use the PySpark Admission Predictor, run the admission_predictor.py script. The script reads in the admission_data.csv file, processes the data using PySpark, and trains a machine learning model on the input variables. The script then outputs the predictions for the chance of admission for the test set.

Conclusion
The PySpark Admission Predictor is a powerful solution for predicting the likelihood of admission using several key input variables. With its focus on PySpark, machine learning, and linear regression
