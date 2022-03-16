# PrivacyPreservingMachineLearning

PrivacyPreservingMachineLearning builds and tests a supervised machine learning model that uses differntial privacy. It is inspired by the PATE model 
(https://arxiv.org/abs/1802.08908) to make predictions about sensitive network traffic data, while preserving data privacy. 

The implementation uses Scikit-Learn's Random Forest Classifier and Random Forest Regressor and tests models with varying ratios of "teachers" and "students" to find which model configuration consistently makes predictions with the highest accuracy. 

This project uses Laplacian Noise and data analytics tools to compare the varying degree of model accuracies, and in addition, relates noise to those results.

# Research

I wrote the first draft of an academic research paper with intention to continue future drafts/editing and submit to machine learning conferences for publishing. 
The paper documents the project purpose, details, and results. It is in progress and can be viewed on Google Docs.

https://docs.google.com/document/d/1OfKujjr2bnezikw3YKO2Hlacu3uM4lMOkghuCKcS-Go/edit
