# Comparative-Performance-Analysis-of-using-ML-algorithms-for-Fraud-Detection-in-Insurance-Claim
For years the commercial enterprise of vehicle insurance companies has
greatly suffered from fraudulent claims, they have spent millions of dollars on 
fraudsters. It has become a grave issue for insurance companies hence along 
with organizations that fight against crimes and the government sector are 
searching for ways to detect these frauds and reduce them. Here in this 
research comparative performance analysis of Machine Learning Algorithms 
for fraud detection in the insurance claim process has been conducted to 
identify the most efficient and effective way to detect fraud, hoping to help 
insurance companies to identify fraudsters beforehand. 
The research was performed via three methods and evaluated using two 
evaluation phases. Eight ML algorithms (Logistic Regression, Gradient Boost, 
Random Forest, Decision Tree, Support Vector Machine, Ada Boost, MultiLayer Perceptron, and K-Nearest Neighbor) were used to compare the 
performance. The first method was applying ML algorithms to the imbalanced 
data set, the second to the over-sampled dataset, and the third to undersampled data set. Parameter tuning was also conducted for some of the ML 
algorithms to improve the model performance and to find out the best-matched 
value for parameters. In evaluation phase 1, the ML models for each method 
were evaluated using accuracy, precision, recall, f1-score, number of TN 
values, and number of FN values. From method 1, method 2, and method 3, 
respectively KNN (n_ neighbors = 3), RF (n_estimators =10), and LR were 
performed well than other ML models. Then those chosen ML models from 
each method were again evaluated using ROC and AUC values in evaluation 
phase 2. In the evaluation phase 2, RF from method 2 shows the highest value 
of AUC showing 0.91 value. In the evaluation phase 1 also RF was able to 
perform the highest accuracy, precision, recall, and f1-score respectively 83%, 
92 %, 72 %, and 81%. It predicted the highest number of fraud claims (TN 
values = 4061), and it had the lowest value for FN, which means a smaller 
number of fraud claims were misidentified as not-frauds. Comparative 
performance analysis conducted in this research has proved that using 
Random Forest on the over-sampled insurance data set is the best way to 
detect fraud in the insurance claim process.

