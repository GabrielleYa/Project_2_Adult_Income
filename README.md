# Adult_Income
Predicting income level based on individuals' personal information.

## **Source**
This dataset named “adult” is found in the UCI machine learning repository
http://www.cs.toronto.edu/~delve/data/adult/desc.html

The detailed description on the dataset can be found in the original UCI documentation
http://www.cs.toronto.edu/~delve/data/adult/adultDetail.html

## **The Data**
The dataset contains:
- 16 columns

- Target filed: Income

- The income is divide into two classes: <=50K and >50K

- Number of attributes: 14

- 7% have missing values.


**Author:** Gabrielle Ray


**Methods**
---
- Inapropriate values were dropped or replaced to create a fluent data set
- Males and females were compared to contrast income relations

## **Visual 1**
![Screenshot 2023-10-20 050017](https://github.com/GabrielleYa/Project_2_Adult_Income/assets/135492530/94bd5ed5-80d2-48fe-a1b7-8b8b464c43dd)

- All males work at least 35 hours per week with a mean of about 40 hours per week
  

## **Visual 2**
![Screenshot 2023-11-08 144340](https://github.com/GabrielleYa/Project_2_Adult_Income/assets/135492530/f175b490-c5d5-4dfd-8f72-fad931c89d26)

- Most of the features present a weak postive correaltions
- the closetest feature correlation pair to 1 is educational_num and capital-gain
- Higher correlations or more than likly presented in the categorical features


## **Results**
- The best model to predict an adults income level based on their personal information is the Logistic Regression model. Both models with and witout hyperparameters had a recall score of 0.60. This means that the models were able to correctly predict 0.60% of adults' income based on their personal. With some additional data it is possible for this score to improve. If the stkeholders are to use this model to predict adult's income ther is a 0.40% chance that the prediction would be inacurrate.
