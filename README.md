# Fraud-Detection-in-E-commerce
Part 0 Summary of Fraud Detection Code Lab

Part 1 Import Data and Package Setup

Part 2 Data exploration and EDA: Distribution of the label column / EDA / Check Missing Values
  
Part 3 Data Transformation: Identify and Append country info based on ip_addres / Feature Engineering before Split
  
       
Part 4 Data Split

Part 5 Feature Engineering after Split: Convert categorical features with high cadinality to numericals in train data / Convert categorical features with high cadinality to numericals in test data / Normalization and Standardization separately for train and test data
  
Part 6 Model Training: Simple LogisticRegression model / Simple RF model / SMOTE sampling / RF on smoted training data
  
Part 7 Parameter tuning by GridSearchCV: Optimizing on F1_score on Regularized Logistic Regression / Optimizing on F1_score on Weighted Random Forest / Optimizing Recall_score on Weighted Random Forest
  
Part 8 Check Fraud Characteristics: Check the relationship between n_dev_shard and Fraud / Check the relationship between interval_after_signup and Fraud / Check Fraud Data
  
Part 9 Model Application

---------------------------------------------------------------------------------------------
About the dataset:

E-commerce companys always try to identify users with high-risk for performing fraud activities.
There are two dataset--one named imbalancedFraudDF and the other one named IpAddress_to_Country.
imbalancedFraudDF dataset contains specific user's information including user_id/signup_time/purchase_time/purchase_value/device_id	source/browser/sex/age/ip_address/class

IpAddress_to_Country dataset contains country information corresponding to the ip address range including lower_bound_ip_address/upper_bound_ip_address/country



