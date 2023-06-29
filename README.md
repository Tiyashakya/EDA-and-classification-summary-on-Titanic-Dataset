# EDA
To gain insights and understand the factors that influenced the survival of passengers on the Titanic

Data Description
The dataset contains information about the passengers aboard the Titanic, including whether they survived or not. The dataset consists of the following columns:

1)PassengerId: A unique identifier for each passenger.

2)Survived: Indicates whether the passenger survived or not. It is represented by the values 0 (did not survive) and 1          (survived).

3)Pclass: The passenger class, which represents the socio-economic status of the passenger. It can take values 1, 2, or 3, where 1 represents the upper class, 2 represents the middle class, and 3 represents the lower class.

4)Name: The name of the passenger.

5)Sex: The gender of the passenger, either male or female.

6)Age: The age of the passenger. It can be represented as a decimal for infants or estimated for passengers whose age is unknown and denoted as xx.5.

7)SibSp: The number of siblings/spouses aboard the Titanic for a particular passenger.

8)Parch: The number of parents/children aboard the Titanic for a particular passenger.

9)Ticket: The ticket number.

10)Fare: The fare or price paid for the ticket.

11)Cabin: The cabin number where the passenger stayed.

12)Embarked: The port of embarkation for the passenger.C (Cherbourg), Q (Queenstown), or S (Southampton).


# Conclusions
1) Age Analysis:
- The average age of passengers aboard was 30 years, indicating a relatively young population.
- 25% of passengers were below the age of 22, 50% were below 29, and 75% were below 35.
- Most of the passengers were in the age bracket of 20 to 40, with a mix of children and senior citizens.

2) Ticket Price:
- The average price of a ticket per person was around $33.2.
- The highest price paid for a ticket was $512.32.

3) Survival Rate:
- Out of the 1309 passengers, only 38% survived the accident.
- Survival rates varied based on passenger class, gender, age, and other factors.

4) Passenger Class Analysis:
- Pclass 3 was the most crowded, accommodating 54% of the passengers.
- Pclass 2 was the least crowded, with only 21% of the passengers.
- Survival rate was highest for Pclass 1 (58%) and lowest for Pclass 3 (27%).

5) Gender Distribution:
- 64% of the passengers were male, while 36% were female.
- Survival rate was significantly higher for females (83%) compared to males (13%).

6) Port of Embarkation:
- Survival rate was highest for passengers who boarded from Cherbourg (49%).
- Survival rate was lowest for passengers who boarded from Southampton (34%).

7) Age and Survival:
- Passengers below the age of 16 had a higher chance of survival.
- The age group of 17 to 35 had a lower probability of surviving.

8) Ticket Price and Survival:
- Passengers who purchased higher-priced tickets had a higher chance of survival.

9) Family Size:
- Passengers traveling with smaller families had a higher chance of survival.
- Traveling alone also increased the chances of survival.

In summary, the analysis reveals that being female, traveling in Pclass 1, boarding from Cherbourg, and belonging to certain age groups or having higher-priced tickets increased the likelihood of survival. On the other hand, being male, traveling in Pclass 3, boarding from Southampton, and falling within the age range of 17 to 35 decreased the chances of survival. The presence of family members also influenced survival rates, smaller families  had higher chances of survival.

1) Chances of female survival is higher than male 
2) Travelling in Pclass 3 was deadliest
3) People in the age range of 20 to 40 had a higher chance of not surviving 
4) People travelling with smaller families had a higher chance of survival as compared to people travelling with large families and travelling alone

# Titanic-Classification-summary
Comparison of Classification Algorithms on the Titanic Dataset

Process Flow
1. Load the Titanic dataset,on which EDA and feature engineering, and scaling has been performed in exploration stage 
2. Perform data preprocessing and feature engineering as required.
3. Split the dataset into training and testing sets using train_test_split() function from sklearn.model_selection.
4. Initialize the decision tree, logistic regression, and KNN classification models.
5. Fit the models on the training data using their respective fit() functions.
6. Predict the labels for both the training and testing data using the predict() function of each model.
7. Calculate and store the accuracy, precision, recall, F1 score, and AUC ROC for each model using appropriate metrics from sklearn.metrics.
8. Plot the AUC curve for each model using the roc_curve() and auc() functions from sklearn.metrics.
9. Create a dataframe to store the performance metrics for each model, including the train accuracy, test accuracy, train precision, test precision, train recall, test recall, train F1 score, test F1 score, train AUC ROC, and test AUC ROC.
10. Print the performance metrics in a tabular format.


This created dataframe stores the performance metrics for each model, allowing for easy comparison and analysis of the classification algorithms on the Titanic dataset.                            

  


