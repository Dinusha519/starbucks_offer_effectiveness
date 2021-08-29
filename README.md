# Evaluation of Offers' Effectiveness

This repository contains an end to end project analysing Starbucks Offers and finding what type of customers respond best to what type of offers. This repo has a pdf with the detailed walk through of the project

## Project Overview
Starbucks is a well-known coffee shop with locations all over the world. Starbucks, like most other stores, has a mobile app via which users can receive special discounts from time to time. An offer might be as simple as a drink commercial or as complex as a discount or a BOGO deal (buy one get one free). Every offer has a time limit before it expires, and some, such as discounts and BOGO, require a minimum purchase to be eligible.
The most important question to address is which customer groupings respond well to whatever offer type. As a result, this challenge might be framed as a classification problem, with the goal of determining which types of people respond best to which types of offers.

### Pre-requistes
The project was developed using python 3.6.7 with the following packages.
 - types
 - pandas
 - numpy
 - math
 - json
 - matplotlib.pyplot
 - seaborn
 - shap
 - warnings

### Files

- Starbucks_Capstone_notebook.ipynb : Jupyter Notebook with the analysis
- starbucks_report : Article with.a walls through of the project
- data/ : data from Starbucks
- images/: images used for report
- Project_dataprep_utils.ipynb.ipynb: functions for the project analysis in 

### Summary
To begin, there were three json input files: profile, portfolio, and transcript. These data sets were preprocessed, and a master table with customer-level granularity was generated. Then, step by step, two categorization models were created to identify the most significant traits customers should have in order to make a successful offer. Shap analysis was utilized to interpret the models because they were black box models. Please see the page linked above for a complete walkthrough of the project.

### Acknowledgements

Starbucks, for providing the data based on simulations of real environment.
