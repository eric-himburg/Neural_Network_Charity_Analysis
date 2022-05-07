# Neural Network Charity Analysis
## Overview of the Analysis
Deep neural networks were used to help predict where to make investments.  A dataset containing more than 34,000 charity organizations was pre-processed using a binary classifier.  The data was trained, tested and evaluated in order to create an accurate predicting model.  The input data and model parameters were changed several times in order to achieve the highest accuracy.   

## Results
### Data Preprocessing
* The "IS_SUCCESSFUL" column of data was the target of the model.  Ultimately, we want ot predict whether or not the money given to a charity organization is successfully used or not.  
* The features of the model include "STATUS", "ASK_AMT", "APPLICATION_TYPE", "CLASSIFICATION", "USE_CASE", "ORGANIZATION", and "INCOME_AMT".
* The data which was neither a target nor a feature and which was ultimately dropped from the data included: "EIN" and "NAME".  These were identification data and were not relevant to making a prediction.  

### Compiling, Training, and Evaluating the Model
* How many neurons, layers, and activation functions did you select for your neural network model, and why?
* Were you able to achieve the target model performance?
* What steps did you take to try and increase model performance?

![charity analysis](screenshots/neural_network1.png)


## Summary

