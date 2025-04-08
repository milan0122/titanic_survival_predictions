# titanic_survival_predictions
#### First I explored the dataset size and its info  as well as visualizing ie. preprocessing the dataset
#### handling missing of Age, by taking median value of Age
#### get_dummies used to convert categorical features like sex 

####  For training the model, titanic dataset- train.csv  where model trained on RandomForestClassifer with 100 estimators, 5-max depth.
#### Testing is done using - test.csv dataset and finally got overall 77% accuracy 
which is listed in Kaggle
Kaggle Link: https://www.kaggle.com/code/milan012/titanic-survival-predictions
#### However in this notebook, i split the train dataset into 80-20 and achieve 82% accuracy. 