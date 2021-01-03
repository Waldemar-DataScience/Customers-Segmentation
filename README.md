# Portfolio Project 2 – Clusterisation

## Customers Segmentation

### General Overview
The business aim of the project is to divide  customers of an internet shop into similar groups. Such a division  allow us  better address  different promotion strategies. 

Used in the project  raw data contains the goods purchased  by client, their quantity,  unit price and time of transaction.

Such a data organisation need to be transformed into a table where each client is represented by one row. To make it as simple as possible but still business valuable we calculate two parameters: the *Frequency of Purchase* and the *Mean Value of Purchase*.
After that we perform clusterisation and the business analyse of results. 

### Data Used
I used the public available data stets available in
UCI Machine Learning Repository, Online Retail Data Set
[link here]( https://archive.ics.uci.edu/ml/datasets/Online+Retail)
Full description also in the file *Description.txt*

Citation: 

Daqing Chen, Sai Liang Sain, and Kun Guo, Data mining for the online retail industry: A case study of RFM model-based customer segmentation using data mining, Journal of Database Marketing and Customer Strategy Management, Vol. 19, No. 3, pp. 197â€“208, 2012 (Published online before print: 27 August 2012. doi: 10.1057/dbm.2012.17).
### Project contents

The project contains two notebooks:

1. *Data Preparation* contains all data manipulation using pandas library to aggregate relevant data.

2. *Clustering* preform training machine learning model. Elbow analysis choosing what number of clusters seems to be proper and the business value of results. 

### Algorithm used

1.	K Nearest Neighbours Clustering

### Summary
The number of 8 clusters seem to be the best. 5 of them seems to be outliers. The sixth is the most common group of small clients but I selected also  two clusters of clients who buy more frequent or have the larger mean invoices. They seems to be most valuable target of marketing campaigns. 



Future improvements are planned. 

*This is version 0.9 from 3 January 2021.*
