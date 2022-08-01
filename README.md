# weather-prediction

This project is about the prediction of the weather prediction of a city, to do this information were gathered on how each d ays weather condition and the properties of that day. The predictions were made possible with the use of machine learning algorithms.

The dataset used to perform this prediction was gotten from Knaggle.com ,a machine learning platform.
Details about this is showm below.

## Importing Libraries

The libraries imported include; pandas, matploylib, seaborn, numpy, and some sklearn packages.

## Loading and reading the data

The data gotten has 1461 rows and 6 columns. 
The columns have the following titles, date ,precipitation, temp_max, temp_min, wind, and weather.

The types of weather condition available in the weather column are; drizzle, sun, rain, snow, and fog. 
The other types of data present are numerical data.

## Exploratory Data Analysis

Data analysis in performed for the features of the data. 
From analysis, it is seen that rain and sum have te highest counts in the weathers.
Precipitation data is skewed, temp_max is a quite distributed. same with temp_min (both are the maximun temperature and the minimum temperature of each day). The Wind feature is quite distributed.

## Preprocessing

The preprocessing done here is firstly spitting the data into features and label, then the features are scaled using sklearn Standaed scaler, then the data was finally spitted to training and test sets.

## Modeling

The last thing that needs to be done after preprocessing is to create a model that will predict the weather condition if the city. 

The models used will be discuss below
### Random Forest Classifier

Random Forest Classifier and any other model were gotten from the scikit learn library.
Upon the usage of this model and using it with cross caludation, the acuracy of the model is 83%.

### Gradinet Boosting Classifier

The result of using this model upon scoring gave an accuracy of 83% also.


### SVM

This model is gives an accuracy of 79%.

## Conclusion

From the results above, the model that performed beat is Random Forestr Classifier.
