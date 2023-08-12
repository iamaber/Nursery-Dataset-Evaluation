# Nursery-Dataset-Evaluation


Ratings of nursery school application submissions are made using this database. When student enrollment was too large, it was employed. Besides we have 9 features in this database which mainly represent the selection criteria. The ultimate choice was based on three subproblems: the parents' occupations and the child's nursery, the family's financial situation and structure, and the family's social and physical well-being. 


Finding the final evaluation will allow us to determine which students are encouraged and which ones are not is the project's motivation. 


Pre-processing reveals numerous rows with null values and that column-wise values aren't provided. We are deleting the row where we find null values in order to solve this problem because we cannot forecast a value. We can identify an ideal dataset after removing the null values, and we may use this dataset to perform our encoding. While encoding we have assigned our categorical values into numerical values. We can not pass strings in supervised machine learning models for that reason it is important to encode the given data. 


We used random dataset splitting for this project. The general idea behind random data splitting is to partition the available data into two or more subsets: one for training the model and the other for testing the model's performance.


References:
UCI Machine Learning Repository: Nursery Data Set. (n.d.). 

https://archive.ics.uci.edu/ml/datasets/nursery 
