# Coursera_Capstone
IBM Applied Data Science Capstone

## Introduction | Business Undertanding 
To reduce the frequency of car collisions we have to develope a model to predict the severity of an accident given the current weather, road and visibility conditions. 
When conditions are bad, this model will say to be more careful.

## Data Understanding 
The target is 'SEVERITYCODE' (it is used to measure the severity of an accident). 
Attributes used to weigh the severity of an accident are 'WEATHER', 'ROADCOND' and 'LIGHTCOND'.

## Extract Dataset & Convert 
The data is not fit for analysis perfectly. 
We should not use all attributes for our model. 
Most of the attributes are text-type, so we should convert them to a numerical type.
We should use label encoding to covert the features.

## Balancing the Dataset 
The target variable SEVERITYCODE is only 42% balanced. 
the quantity of severitycode in class 1 is 136485 and the class 2 is 58188.
We can fix this by downsampling the class 1.
