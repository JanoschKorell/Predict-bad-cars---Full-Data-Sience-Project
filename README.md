# Predict-bad-cars---Full-Data-Sience-Project




This project is a complete Datascience workflow consisting of:




EDA, 
Outliers, 
Imputation, 
Train-Test-Split, 
Dim Reduction, 
Feature Engineering, 
Hyperparameter Optimization, 
Train Model (XGBoost), 
Classification report, I
Interpretation with SHAP Values.





"""
Task:

One of the biggest challenges of an auto dealership purchasing a used car at an auto auction is the risk of 
that the vehicle might have serious issues that prevent it from being sold to customers. The auto community 
calls these unfortunate purchases "kicks".
Kicked cars often result when there are tampered odometers, mechanical issues the dealer is not able to 
address, issues with getting the vehicle title from the seller, or some other unforeseen problem. 
Kick cars can be very costly to dealers after transportation cost, throw-away repair work, and market 
losses in reselling the vehicle.
Modelers who can figure out which cars have a higher risk of being kick can provide real value to 
dealerships trying to provide the best inventory selection possible to their customers.

The challenge of this competition is to predict if the car purchased at the Auction is a Kick (bad buy).


Problem:     

The problem is one of classification. The metric can be F1 or Recall, so that category 1 = "bad car" can 
be captured as well as possible. F1 offers the possibility to get the best possible balance between 
recall and precision. Therefore, the metric will be f1.
"""





"""
Please watch for comments that accompany the process and identify findings. 
"""

"""
1. EDA
    1.1 Rename, relabel, dtypes
    1.2 Pairplot: Overview of the data
    1.3 Describe: Summary statistics
    1.4 Overview of categorical features
    1.5 Correlations
    1.6 Outlier Detection
    1.7 Missing Data
2. Train Test Split
3. Data Preparation
4.Imputation
    4.1 Imput kat
    4.2 Imput num
5. Deal with outliers
6. Feature Engineering
7. Dimensionality Reduction
8. Feature Selection
9. Simple Baseline Model
10. Train model XGBoost with HyperOpt
11. Train model XGBoost
12. Feature Importance
13. Finale Datapipeline
14. Confusion Matrix / Classification report
15. Addition: Interpretation with SHAP
16. Addition: Advice to the client

"""
