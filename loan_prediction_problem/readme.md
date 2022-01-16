Here we will do the classification problem for one of the dataset in Kaggle. The data is split into two files. Train and Test file. Both of them contain information about the user's loan status.
Based on the dataset we will predict the load status of the test dataset. 
I have used two methods in this notebook to solve the classification problem. 
1) Kernel SVM with rbf
2) RandomforestClassifier

Packages used are as follows,
Numpy and pandas for data load and wrangling
SimpleImputer to handle the missing values
LableEncoder to encode the categorical information
train_test_split to split the data
StandardScaler is used for feature scaling
SVC for SupportVector Classifier
RandomForestClassifier for random forest technique
classification_report,confusion_matrix,accuracy_score for accuracy and entire classification report

Apart from these, I have added detailed comments on most of the cells for the users to understand what is happening. 
