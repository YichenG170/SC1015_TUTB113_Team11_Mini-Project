# SC1015_TUTB113_Team11_Mini-Project
The main purpose of the mini-project is to find factors that can be used to predict whether a flight's arrival time will be delayed or not, and further find appropriate models using these variables to predict whether the flight's arrival time will be delayed or not. 

All of the data covered in this mini-project are in the CSV file "DelayedFlights". Data in this CSV file is gathered by the U.S. Department of Transportation's (DOT) Bureau of Transportation Statistics (BTS) in 2008, and can be downloaded on https://www.kaggle.com/datasets/giovamata/airlinedelaycauses. 

After data preparation and data cleaning, an EDA is done to select potential numeric predictors for the response variable `ArrDelay`. Categorical variables are found to be unsuitable for predicting. It can be found that the most important factors that affect whether a flight's arrival time is delayed or not are departure delay (`DepDelay`), estimated elapse time (`CRSElapsedTime`), distance between the origin and destination (`Distance`), and taxi out time (`TaxiOut`).

When selecting models for the dataset, RandomForestClassifier (extra-curricular knowledge) and DecisionTreeClassifier are used. Both of them have accurate predictions, and results from DecisionTreeClassifier is even more accurate than results from RandomForestClassifier. Therefore, the DecisionTreeClassifier is the most appropriate model for predicting `ArrDelay`. 
