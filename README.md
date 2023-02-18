# Overview
This is a repository containing works for the third project to graduate from Udacity Nanodegree "Introduction to Machine Learning with TensorFlow" program in 2022. 

In this project I applied unsupervised learning techniques (clustering) to identify market segments of a mail-order sales company in Germany. This project features tabular data containing 85 columns and more than 1 million rows spanning in 2 .csv files.

# Motivation
This repository is intended as a portfolio for datascience work. Recruiter/hiring managers can get idea about my skill and working style as well. Below are skills/key concepts that I practiced in this project:
- unsupervised algorithm
- market segmentation
- large tabular dataset
- clustering problem
- pandas and scikit-learn python libraries

# About files in this repository
Below is the explanation of files used in this project.
1. **Identify_Customer_Segments.ipynb**: this is the main file I used to cluster the market segment. The flow/structure of this file was prepared by Udacity team. I contributed to cells marked with "TODO:". Key activities that I did in this notebook:
    - Data exploration
    - Data cleansing (missing data, feature encoding)
    - Feature engineering and feature selection
    - Feature scaling and Principal Component Analysis (PCA)
    - K-Means clustering
2. **Identify_Customer_Segments.html**: the content of this file is the same as `Identify_Customer_Segments.ipynb`. If you want to review the code without jupyter notebook, you can use internet browser to view this file.
3. **Udacity_AZDIAS_Subset_head10.csv**: demographics data for the general population of Germany. The original file consists of 891,211 persons (rows) x 85 features (columns), but for this Github repository, only the subset containing top 10 rows is shared.
4. **Udacity_CUSTOMERS_Subset_head10.csv**: demographics data for customers of a mail-order company. The original file consists of 191,652 persons (rows) x 85 features (columns), but for this Github repository, only the subset containing top 10 rows is shared.
5. **AZDIAS_Feature_Summary.csv**: contains a summary of feature attributes, including information level, data type, and codes for missing or unknown values.
6. **Data_Dictionary.md**: contains detailed information about the features in the datasets.
