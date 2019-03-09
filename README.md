# Nobbas-Technologies-Assignment
Internship Assignment given by Nobbas Technologies

The following classification is achieveable. In this project, I have broken the dataset into 2 categories:
1. Categorial Data
2. Numerical Data

The Numerical data has been trained using XGBoost and LSTM algorithms. In both the models, Features likeid, city, postalCode, bathrooms, bedrooms,
listPrice, livingArea, yearBuilt, lotSize, propSubType, listingCategory, numOfParking and NoOfPhotos have been used as INDEPENDENT VARIABLES
to Train the model and Feature 'grade' has been used as DEPENDENT VARIABLE.

The Categorial Data has been trained using NAtural Language Processing approach using Bag of Words Model. For this purpose, the feature 
'listingDescription' has been used to train the model as INDEPENDENT VARIABLE and Feature 'grade' has been used as DEPENDENT VARIABLE. 


FUTURE WORK and AREA OF IMPROVEMENT

The Results obtained from above 3 models can be ENSEMBLED using algorithms like AdaBoost to achieve better accuracy.
