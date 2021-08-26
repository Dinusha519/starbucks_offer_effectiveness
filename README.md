# Evaluation of Offers' Effectiveness

This repository contains an end to end project analysing Starbucks Offers and finding what type of customers respond best to what type of offers. This article has a project walk through.

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
- data/ : data from Starbucks
- Project_dataprep_utils.ipynb.ipynb: functions for the project analysis in 

### Summary
There were 3 json input files to satrt with profile, portfolio and transcript. These datsets were preprocessed and master table was created with customer level granularity. Then an step by step development was carried out till 2 classification models were built to identify the most important features customers should have have a successful offer. As they are black box models shap analysis was used to interpret the models. Few more improvements which could be tried are also have identified. For a detailed walthrough of the project, please checkout the article mentioned above. 

### Acknowledgements

Starbucks, for providing the data based on simulations of real environment.
