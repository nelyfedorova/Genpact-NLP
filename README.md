# Genpact-NLP: Pubmed Text Classification

## Problem: Classify given set of Pubmed biomedical literature abstracts into 4 classes:
a) Abstracts containing Drug adverse events  
b) Abstracts containing Congenital anomalies  
c) Abstracts containing both (a) and (b)  
d) Others  

## Dataset: Pubmed
https://pubmed.ncbi.nlm.nih.gov/

## TASK 1
Write a Python program to download at most 10,000 abstracts (in either XML format or just the plain text abstracts) using Entrez utilities belonging to each of the four classes

## TASK 2
Write a classifier using any AI/ML technique to classify a given set of abstracts into the four classes. Perform n-fold cross validation and provide performance metrics for the classification.
