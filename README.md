# M19-Neural_Network_Charity_Analysis

## Overview 
The purpose of this project is to use the knowledge of machine learning and neural networks to create a binary classifier that can predict whether applicants will be successful if funded by Alphabet Soup.
During this project we will first be preprocessing Data for a Neural Network Model. Then, compile, Train, and Evaluate the Model. finally, we will try and optimize the Model.

## Results 

### Data Preprocessing

The target column for this model: IS_SUCCESSFUL
The features for the model are: APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS, ASK_AMT
The other columns were removed from the input data.

### Compiling, Training, and Evaluating the Model

The model was trained with 2 hidden layers, one 80 and the other one 30 neurons. the result summary below: 

<img width="919" alt="model_results" src="https://user-images.githubusercontent.com/91625564/155923345-3ad7e2c1-854b-4845-900d-d5757c02f683.png">



After the optimized model, I added a third hidden layer. I decided to use a sigmoid activation function. These 3 layers had 80, 40, and 8 neurons respectfully.

<img width="919" alt="model_results_opt" src="https://user-images.githubusercontent.com/91625564/155923378-1c5f16bd-0cca-4be5-8103-06174146c5bc.png">



## Summary 

In summary, we can say that this deep learning neural network model did not reach the target of 75% accuracy. The optimization also did not work on improving the results as the accuracy stayed almost the same 72%. 
We can consider other machine learning models like Random Forest or Logistical Regression to respond to this project.


