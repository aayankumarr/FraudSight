# **Project: Outlier Detection in Financial Data for Fraudulent Activity Identification**



Dataset : - https://www.kaggle.com/datasets/kartik2112/fraud-detection/data



**Problem Statement**

The clustering model aims to group transaction data to uncover patterns, detect anomalies, and potentially flag fraudulent activities. Objectives include segmenting customers based on spending behavior, analyzing merchants, and identifying geographic or behavioral irregularities. This helps banks enhance fraud detection, personalize services, and improve risk management using transaction data insights.



**Data Description**

The dataset contains transaction records, including details like transaction amount, merchant, category, location, and timestamps, as well as customer demographics (age, gender, job) to analyze and identify fraudulent activities.




**Columns Description**
- Unnamed: 0: An index column, likely redundant for analysis.
- trans_date_trans_time: Timestamp indicating the date and time of the transaction.
- cc_num: The credit card number associated with the transaction.
- merchant: Name of the merchant or store where the transaction occurred. Fraudulent merchants are prefixed with "fraud".
- category: Category of the transaction, such as personal care, health fitness, travel, etc.
- amt: The amount involved in the transaction.
- first: First name of the cardholder.
- last: Last name of the cardholder.
- gender: Gender of the cardholder.
- street: Street address of the cardholder.
- city: City of the cardholder.
- state: State of the cardholder.
- zip: ZIP code of the cardholder's address.
- lat: Latitude of the cardholder's location.
- long: Longitude of the cardholder's location.
- city_pop: Population of the cardholder's city.
- job: Job title or profession of the cardholder.
- dob: Date of birth of the cardholder.
- trans_num: Unique identifier for the transaction.
- unix_time: Timestamp of the transaction in UNIX format.
- merch_lat: Latitude of the merchant's location.
- merch_long: Longitude of the merchant's location.
- is_fraud: A binary indicator where 1 represents a fraudulent transaction and 0 represents a legitimate transaction.


This dataset is useful for clustering based on transaction behaviors, geographic details, and customer demographic information to detect patterns and potentially group similar transactions together for deeper analysis


## Model

- KMEANS
- DBSCAN
- GAUSSIAN MIXTURE MODEL

## EVALUATION METRICS

- DAVIES BOULDIN INDEX
- CALINSKI HARABASZ INDEX



