# kaggle_tatanic_classification

### 1. Problem Definition

타의타닉 호에서 탑승했던 사람들의 정보를 바탕으로 생존자를 예측한다.
 
### 2. Data Dictionary from Kagle

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

### 3. Data Correlation Analysis
각 Feature가 Survived에 얼마나 많은 영향을 미치고 있는지를 알아본다.
#### 3.0 Null Data Checking
#### 3.1 Pclass
#### 3.2Sex
#### 3.3 Sex and Pclass
#### 3.4 Age
#### 3.5 Age and Pclass
#### 3.6 Pclass, Sex and Age
#### 3.7 Embarked
#### 3.8 Family 
#### 3.9 Fare

### 4. Data preproecessing

### 5.Build Model and Train

### 6. Predict on Test Set