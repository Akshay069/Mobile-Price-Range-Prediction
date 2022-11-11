Project Title : Mobile Price Range Prediction
--------------------------------------------------------------------------------------------------------------------------
![image](https://user-images.githubusercontent.com/107321295/201355321-bf49b12c-772f-4a05-8700-f312f3434697.png)


Problem Statement:
--------------------------------------------------------------------------------------------------------------------------
In the competitive mobile phone market companies want to understand sales data of mobile phones and factors which drive the prices. The objective is to find out some relation between features of a mobile phone(eg:- RAM, Internal Memory, etc) and its selling price. In this problem, we do not have to predict the actual price but a price range indicating how high the price is.

Approach:
-------------------------------------------------------------------------------------------------------------------------
Perform classification analysis using multiple models and predict the price ranges of the moible phones and in the end will compare the evaluation metrics for all different models to find the best model.

Steps to be followed:
--------------------------------------------------------------------------------------------------------------------------
Started off with data overview, just to understand what’s in the dataset and in order to inspect how clean the dataset is for working.
Visualizations makes things easier so, performed exploratory data analysis and checked for data distribution.\
Checked for multicollinearity to check if the features are depedent or independent of each other.\
Perform the outlier detection task and delt with it successfully.\
Split the dataset into training and testing data (80% of the data is used for training & 20% of the data is being used for testing).\
Perform different machine learning models as follows:
Logistic Regression.\
Random Forest Classifier.\
Decision Tree Classifier.\
Support Vector Machine classifier.\
Compared model performance using different evaluation metrics in order to get the best performing model.

Conclusion:
---------------------------------------------------------------------------------------------------------------------------
From EDA we can see that there is no imbalance in classes of output variable which is a good thing. also there is very less multicolinearity beetween features which is kind of reduces our work still we did some changes in variables which ultimetly improve our performance.\
It has been observed that expensive mobiles can have fewer features. Like you can find expensive mobile phones with no wifi, no touch screen, no 4G support, no dual sim and even with no bluetooth support. and thats thats mainly beacause of the quality and thr brand of the mobile phone.\
As We have used predictive models, It is being obseved that the data distribution of each variable to the each classes of output variable is almost similar which might be the reason for worst performance of tree based models.\
Mainly features like RAM, battery power, pixels and Mobile weight plays the significant role in deciding the price range of mobile phone.\
On the basis of the classification report, we can say that the SVM using hyperparameters we got the best results out of all other followed by logistic regression model.
