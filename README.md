# Flight-Delay-Prediction

Flight delays are one of the important modern life challenges of airports and airline agencies. We were interested to see how to use spark to solve a real world problem

## Data 

The data for this project entails the flights arrival, departure, delay time and reason for delay for commercial flights in the United States of America. The data is from October 2012 to April 2019.  The dataset has about 50 million records and size is of 22 gigabytes

## Methods
The jupyter notebook with the analysis can be found [here](https://github.com/muthusm/Flight-Delay-Prediction/blob/main/4.%20Methods.ipynb). It includes all the steps we have used to generate and analyse the data with the required output.

## Results

We addressed the following questions:

1. How does weather predict plane delays. This is a regression task and we used Linear Regression. We got an accuracy of 95%

2. What is the optimal time of day of the week or time of the years that is best to fly with minimal delays. This is a classification task and we used Logistic Regression and achieved AUC of 0.5

3. Which flight carrier is prone to delays. This is a classification task and we used Logistic Regression and achieved AUC of 0.8


## Conclusion
The first linear regression model we created was able to predict the arrival delay. We trained with past data. In future, when we give information with the airport details, and flight information the model will be able to calculate the arrival delay in minutes. Similarly the second logistic regression model classifies if the given flight will have optimal delay or not. The random forest model can predict/classify whether the given flight will have departure delays or not. This is definitely helpful to the users travelling frequently to know more aboue the airlines and help them avoid flight delays which is very common recently. 


