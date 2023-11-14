# deep-learning-challenge

#Report on the Neural Network Model

## Overview of the analysis: The purpose of this analysis was to create a neural network that could help choose applicants for Alpahbet Soup that have higher chances of success in their ventures. 

# Results:

## Data Preprocessing

- What variable(s) are the target(s) for your model? 
  -  IS_SUCCESSFUL

- What variable(s) are the features for your model? 
  -  APPLICATION_TYPE
  -  AFFILIATION
  -  CLASSIFICATION
  -  USE_CASE
  -  ORGANIZATION
  -  STATUS
  -  INCOME_AMT
  -  SPECIAL_CONSIDERATIONS
  -  ASK_AMT
- What variable(s) should be removed from the input data because they are neither targets nor features?
  -  EIN
  -  NAME

## Compiling, Training, and Evaluating the Model

- How many neurons, layers, and activation functions did you select for your neural network model, and why? 
I started with 2 hidden layers with relu activation and sigmoid for the outer layer
- Were you able to achieve the target model performance?
I was not able to reach target performance of 75%. My accuracy was 72%
- What steps did you take in your attempts to increase model performance?
I changed my node layers, but was never able to get an accuracy of above 73%

# Summary: 

- With this Neural Network Model, I was unable to reach target model performance, but I was consistent with reaching around 73%. Going forward, I would try to improve my accuracy by changing the number of nodes for my hidden and outer layers. 
