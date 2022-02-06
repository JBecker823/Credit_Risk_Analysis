# Credit_Risk_Analysis

Credit_Rick_Analysis
Supervised Machine Learning and Credit Risk 

Overview of the loan prediction risk analysis: 
Credit risk is an inherently unbalanced classification problem, as good loans outnumber risky loans. Different techniques and strategies were used to train and evaluate models with unbalanced classes. Various libraries and algorithms were used to build and evaluate models using resampling. Some of the methods include:
1.	Imbalanced-learn
2.	Scikit-learn
3.	RandonOverSampler
4.	SMOTE algorithm
5.	ClusterCentroid Algorithm
6.	SMOTEENN algorithm
7.	BalancedRandomForestClassifier
8.	EasyEnsembleClassifier

Purpose: 
1.	Explain how machine learning algorithm is used in data analysis.
2.	Create training and test groups from given data set. 
3.	Implement the logistic regression, decision tree, random forest, and support vector machine algorithm. 
4.	Interpret the results of the logistic regression, decision tree, random forest, and support vector machine algorithms. 
5.	Compare the advantages and disadvantages of each supervised learning algorithm. 
6.	Determine which supervised learning algorithm is best used for a given data set of scenarios. 
7.	Use ensemble and resampling techniques to improve model performance. 

Results: 
The results for the six machine learning models including their respective balanced accuracy, precision, and recall scores are as follows: 

Naïve random oversampling

<img width="845" alt="Naive_Random_Oversampling" src="https://user-images.githubusercontent.com/91567484/152696818-351616ce-1bd9-4593-8578-ba1d04389b3d.png">

1.	Balance Accuracy: 0.6613
2.	Precision: The precision is low for High-risk loans and is high for Low-risk loans
3.	Recall: High/low risk = .66/.67

SMOTE Oversampling

<img width="861" alt="SMOTE_Oversampling" src="https://user-images.githubusercontent.com/91567484/152696820-de282536-e5f9-420c-9496-9a16719ac617.png">


1.	Balanced Accuracy: .06303
2.	Precision: The precision is low for high-risk loans and is high for Low-risk loans.
3.	Recall: High/Low risk = .62/.64

Undersampling

<img width="825" alt="Undersampling" src="https://user-images.githubusercontent.com/91567484/152696831-81ad4caf-b809-447f-b4ba-0f3cd0139353.png">

1.	Balanced Accuracy: 0.6303
2.	Precision: The precision is low for High-risk loans and is high for Low-risk loans
3.	Recall: high/low risk = .63/.40

Combination Under-Over Sampling

<img width="809" alt="Combo_under_over_sampling" src="https://user-images.githubusercontent.com/91567484/152696841-8f1e1e6d-487e-4d01-ab2b-f270045caac3.png">


1.	Balanced Accuracy: .05174
2.	Precision: The precision is low for High-risk loans and is high for Low-risk loans
3.	Recall: High/Low risk = .70/.57

Balanced Random Forest Classifier

<img width="814" alt="Balance_random_forest_classifier" src="https://user-images.githubusercontent.com/91567484/152696849-607cc4ac-46ee-4fbe-bc8d-b48c8063022c.png">


1.	Balanced Accuracy: 0.7878
2.	Precision: The precision is low for High-risk loans and is high for Low-risk Loans.
3.	Recall: High/Low risk = .67/.91

Easy Ensemble AdaBoost Classifier

<img width="809" alt="Easy_ensemble_ababoost_classifier" src="https://user-images.githubusercontent.com/91567484/152696856-37add3bf-786a-4d70-ad4f-693c9eacf156.png">


1.	Balanced Accuracy: .9254
2.	Precision: The precision is low for High-risk and is high for Low-risk loans.
3.	Recall: High/Low risk = .91/.94

Summary: 

When working with balanced accuracy, the highest compared accuracy between 0 and 1 and is closest to 1 is the best machine learning model. For the credit card data set, the Easy Ensemble AdaBoost Classifier is the best model to choose with its .93 balanced accuracy. The other models were below .80 balanced accuracy. The precision for all models were similar and within an appropriate range. The recall score also needs to fall within 0 and 1, with numbers closer to 1 being the better model. The Easy Ensemble AdaBoost Classifier had the highest recall score, making it the final best machine learning model to choose for further credit card analysis.
