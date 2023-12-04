# deep-learning-challenge

## Overview:
  The purpose of the analysis was to find the best nueral network model to create a binary classifier that can rpedict whether applicants will be successful if funded by AlphabetSoup. The goal for this assignment was to preprocess the data, compila, train and model the data to then be able to optimize it to achieve a target predictive accuracy of higher than 75%.

## Results:
  *Data Preprocessing:*
  **Target Variables for the model:**
  * IS_SUCCESSFUL

    

  **Feature Variables:**
  * APPLICATION_TYPE
  * AFFLIATION
  * CLASSIFICATION
  * USE_CASE
  * ORGANIZATION
  * STATUS
  * INCOME_AMT
  * SPECIAL_CONSIDERATIONS
  * ASK_AMT

*Compiling, Training, and Evaluating the Model*
  * I selected 5 hidden layers with 80, 70, 50, 30, 10 neurons respectively with "relu" activation functions.
  * I was not able to achieve the target model performance of above 75%. Each attempt did increase marginally but was overall at 73% for each attempt.
  * In each attempt I added more hidden layers with increasing neurons and also increased epochs to increase the model performance.

## Summary:

  The overall results of this model were not what we wanted them to be. I'd recommend instead of continuing to add more hidden layers and more nuerons I'd change up the activation function from "relu" to "sigmoid" and trying out kera-tuner to pick the optimal set of hyperparameters for the model.
    
