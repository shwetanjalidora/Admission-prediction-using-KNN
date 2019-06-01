### DESCRIPTION OF THE DATASET:
  
#### The dataset contains several parameters which are considered important during the application for Masters Programs. The parameters included are:

* GRE Scores ( out of 340 )
* TOEFL Scores ( out of 120 )
* University Rating ( out of 5 )
* Statement of Purpose and Letter of Recommendation Strength ( out of 5 )
* Undergraduate GPA ( out of 10 )
* Chance of Admit: 
                   A= 90-100% chance of admission
                   B= 80-90% chance of admission
                   C= 70-80% chance of admission
                   D= 60-70% chance of admission
                   E= 50-60% chance of admission
                   F= 40-50% chance of admission


### Here are the steps involved:
 * Data extraction
 * Data Cleaning
 * Data manipulation
 * Predictive Analysis
 
**Features**:A feature is an individual measurable property or characteristic of a phenomenon being observed

**Targets**: The “target variable” is the variable whose values are to be modeled and predicted by other variables

In this problem, we are predicting the chance of a candidate being admitted based on the GRE,TOEFL,SOP,LOR and CGPA score.This means that the feature variables are the values that we use(GRE,TOEFL,SOP,LOR and CGPA ) to predict the target variable(Chance of admission).

### Conclusions:
* **Since the data is imbalanced we will consider the f1 score to test the accuracy of our model.**

* **The average weighted f1 score when k=5 we observe an f1 score of 0.57.**

* **Next we increased our k value to be square root of the number of instances in pur training data ie., k=17. Now the f1 score is 0.62. We observe an increase in the accuracy with the increase of k value.**

* **Later, we took a set of values from 1-40 to find the optimal k value and we found out that the optimal k value is 25.** 

* **Here the f1 score is 0.66 which is more when compared to k=17.**

* **May be we can increase the range from 40 to a higher number to get even more accurate results.**

* **From these above values we can say that based on the GRE Score,TOEFL Score LOR and Sop rating we can predict the chances of a candidate being admitted to a University using KNN algorithm**
