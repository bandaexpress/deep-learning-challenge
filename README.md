# deep-learning-challenge
Module 21 Assignment from Columbia University Data Analytics Bootcamp

# Overview
This tool selects applicants for funding with the best chance of success in their ventures using machine learning and neural networks. Using a binary classifier that can predict whether applicants will be successful if funded.

# Results: 
![image](https://github.com/bandaexpress/deep-learning-challenge/assets/17518802/1f64ea21-e3c4-49b3-8f4c-e951e2897158)


### Data Preprocessing

Targetted Variables
The fictional dataset for reference is:

<li>EIN and NAME—Identification columns
<li>APPLICATION_TYPE—Alphabet Soup application type
<li>AFFILIATION—Affiliated sector of industry
<li>CLASSIFICATION—Government organization classification
<li>USE_CASE—Use case for funding
<li>ORGANIZATION—Organization type
<li>STATUS—Active status
<li>INCOME_AMT—Income classification
<li>SPECIAL_CONSIDERATIONS—Special considerations for application
<li>ASK_AMT—Funding amount requested
<li>IS_SUCCESSFUL—Was the money used effectively

### Featured Variables
The feature for this model: IS_SUCCESSFUL—Was the money used effectively

### Removed Variables
EIN and Name

## Compiling, Training, and Evaluating the Model
8 neurons for the first hidden layer and 5 neurons for the second hidden layer, with 1 neuron in the output layer. In an attempt to increase accuracy, I tried with 32 neurons in the first hidden layer and 16 neurons in the second hidden layer to increase capacity to learn more intricate patterns and relationships. Activation Functions: ReLU activation functions are used for both hidden layers, while the output layer uses a sigmoid activation function. ReLU (Rectified Linear Unit) is commonly used in hidden layers as it helps introduce non-linearity into the model, allowing it to learn complex patterns. Sigmoid activation in the output layer is suitable for binary classification tasks like yours, where the output needs to be in the range [0, 1] representing probabilities.

### Were you able to achieve the target model performance?
No, increasing the neurons and adding a dropout value only marginally increased the accuracy.

### What steps did you take in your attempts to increase model performance?
Increasing neurons in hidden layers. Adding in a dropout rate. 

## Summary
While the model achieves a decent accuracy of approximately 73%, the loss indicates that there is room for improvement. A recommendation for improving model performance would be to experiment with different architectures, activation functions, regularization techniques, and hyperparameters. For example, a deeper neural network with more neurons and additional hidden layers could capture more complex patterns in the data, potentially leading to higher accuracy.

### References
IRS. Tax Exempt Organization Search Bulk Data Downloads. https://www.irs.gov/Links to an external site.
