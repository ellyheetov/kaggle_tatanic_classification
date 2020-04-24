# kaggle_tatanic_classification

## 1. Problem Definition

I will go through the whole process of creating a machine learning model on the famous Titanic dataset, which is used by many people all over the world. It provides information on the fate of passengers on the Titanic. By using it, I will predict whether a passenger on the titanic would have been survived or not.
 
## 2. Data Dictionary from Kagle

|Variable|Definition|Key|Veriable Notes|
|:---:|:---:|:----:|:-----|
|Survival|Survival|0 = No, 1 = Yes| | 
|pclass|Ticket class|1 = 1st, 2 = 2nd, 3 = 3rd|1st = Upper, 2nd = Middle, 3rd = Lower |
|sex|sex|||
|Age|Age in years||Age is fractional if less than 1. If the age is estimated, is it in the form of xx.5|
|sibsp|# of siblings / spouses aboard the Titanic||The dataset defines family relations|
|parch|	# of parents / children aboard the Titanic||The dataset defines family relations|
|ticket|Ticket number||
|fare|	Passenger fare||
|cabin|Cabin number||
|embarked|	Port of Embarkation|C = Cherbourg, Q = Queenstown, S = Southampton||

## 3. Data Correlation Analysis
Find out how much each Feature is influencing Survived.
- Null Data Checking
- Pclass
 -Sex
- Sex and Pclass
- Age
- Age and Pclass
- Pclass, Sex and Age
- Embarked
- Family 
- Fare

## 4. Data preproecessing

- Name Replacing
- Fill Null in Age
- Fill Nill in Embarked
- Change Initial, Embarked and Sex (string to numerical)
- One-hot encoding on Initial and Embarked
- Drop columns
- Build Model and predict using the trained model
- Feature Importance

## 5.Build Model and Train

- RandomForestClassifier

Random forest builds multiple decision trees and merges them together to get a more accurate and stable prediction.

## 6. Predict on Test Set
