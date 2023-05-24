# AlphabetSoup Charity Neural Network Models
## Overview
The purpose of this Assignment was to calculate if applicants will end up successful if they are funded by alphabet soup. The goal was to hit 75% accuracy which we never achieved


# Model Results

## Model 1

- Loss: 0.5547528862953186, Accuracy: 0.7303789854049683

## Model 2 

- Loss: 0.5555825233459473, Accuracy: 0.7271137237548828

## Model 3

- 0.5565524697303772, Accuracy: 0.731195330619812


# Data Processing

- APPLICATION_TYPE	AFFILIATION	CLASSIFICATION	USE_CASE	ORGANIZATION	STATUS	INCOME_AMT	SPECIAL_CONSIDERATIONS	ASK_AMT	 were all used to determine success.

- The EIN and Name were removed because they were not targets or features.

# Compiling, Training, and Evaluating the Model

- the first two models have 3 layers, the third model has 4. The first and third also have an epoch of 100, meanwhile the second has 150 in order to try to achieve a higher accuracy.

- We never achieved target model performance.

## Summary
Throughout all three of the models we were never able to hit a high enough accuracy of 75%. The closest model was the third which was higher than the first by .0008 which is not much of a difference. This models accuracy was seen to hit 73.11%. The second model is the worst of them all with the best hitting 72.71%.

