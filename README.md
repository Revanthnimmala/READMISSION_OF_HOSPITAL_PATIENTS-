# READMISSION_OF_HOSPITAL_PATIENTS

PROBLEM STATEMENT 
To implement machine learning models to predict the readmission of a patient based on the records at the time of discharge.  

My attempt at the solution is as follow: 
1. Explore the data set and extracting the features that are required to predict the readmission of a patient within 30 days. 

2. Exploratory data analysis to identify patterns in the database.  

3. Using AUC measures on training different models and identifying the most accurate one. 

Conclusion
•	By analyzing MIMIC-3 dataset I predicted whether a patient gets readmitted within 30 days of discharge.
•	Analyzed the dataset by performing sensitivity Analysis and applied various calibration techniques to identify the top and most affecting features for prediction and used these features to build Random forest, Decision Trees and Logistic Models.
•	Analyzed the AUC and ROC curves to check for overfitting of the data and Dependency of top attributes on the AUC of the model.
