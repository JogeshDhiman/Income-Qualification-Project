Income Qualification 

DESCRIPTION

Identify the level of income qualification needed for the families in Latin America

# Problem Statement Scenario:
Many social programs have a hard time making sure the right people are given enough aid. 
It's tricky when a program focuses on the poorest segment of the population. 
This segment of population can't provide the necessary income and expense records to prove that they qualify.

In Latin America, a popular method called Proxy Means Test (PMT) uses an algorithm to verify income qualification. 
With PMT, agencies use a model that considers a family's observable household attributes like the material of their 
walls and ceiling or the assets found in their homes to classify them and predict their level of need. 
While this is an improvement, accuracy remains a problem as the regions population grows and poverty declines.

The Inter-American Development Bank (IDB) believes that new methods beyond traditional econometrics, 
based on a dataset of Costa Rican household characteristics, might help improve PMT's performance.

# Following actions performed:
* Identify the output variable.
* Understand the type of data.
* Check if there are any biases in your dataset.
* Check whether all members of the house have the same poverty level.
* Check if there is a house without a family head.
* Set the poverty level of the members and the head of the house same in a family.
* Count how many null values are existing in columns.
* Remove null value rows of the target variable.
* Predict the accuracy using random forest classifier.
* Check the accuracy using a random forest with cross-validation.
