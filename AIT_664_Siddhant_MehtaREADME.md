
# Hands-On-II 

Prediction of Houses in the chicago city using the regression and classification models.



## Project Overview

In this project I have build the regression model and classification model to predict the house prices in the chicago city.

## Roadmap 

- Data Cleaning( all this i have done into a new data frame so that it wont affect the original dataset.)
In the data cleaning process I replaced all the the null values in the dataset with a mean but, I got rid Of one etire record which has all the null values.

Till here it's the same process for both the regression and classification models. 

For the **classification model** it was mentioned to sub-divide the Price on the basis of median of the price. I did this and created a new price category.

Then after that I Found the Correlation between the target variable and the other variables present in the dataset.

- **Build the Models**

For the **Regression Models**

I performed Linear Regression, Random Forest and Gradient Boosting and also I have performed the K-fold cross-validation on Gradient boosting for better model performance.

For the **Classification Models**

I performed the Logistic Regression, DecisionTree Classifier and Suport vector Machine (SVM) models.

- **Findings**


**For the Regression Models**
Linear Regression Model:

(RMSE: 68.36) and (R^2: 0.56)

Random Forest Model: (RMSE: 5.08 ) and (R^2: 0.83)

Gradient Boosting Model: (RMSE: 3.79) and (R^2: 0.90)

This indicates that the Gradient Boosting Model is the best model among the Three model while predicting the House Prices of chicago city more accurately.

**For the Classification Models**


- Logistic Regression Model

  Accuracy is 0.77 and AUC = 0.90

- Decision Tree Classifier

  Accuracy is 0.83 and AUC = 0.85

- Suport Vector Machine Classifier(SVM)

  Accuracy is 0.83 and Auc = 0.90

SVM is the best choice here due to its good accuracy and excellent AUC, indicating both reliable predictions and strong discrimination ability.


- **Conclusion**
In this project, I compared regression and classification models for predicting home prices in Chicago. The Gradient Boosting Model outperformed other regression models, with an RMSE of 3.79 and a R² of 0.90, indicating the best accurate predictor. For classification, the Support Vector Machine (SVM) classifier performed best, with an accuracy of 0.83 and an AUC of 0.90, demonstrating its dependability in identifying pricing groups. Overall, combining the two modeling methodologies increases our ability to predict home values and provides more insight into Chicago's market dynamics.

 
- **References**
  
  chicago house price. (2023, May 20). Kaggle. https://www.kaggle.com/datasets/tawfikelmetwally/chicago-house-price
  



