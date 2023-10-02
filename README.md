# deep-learning-challenge

## Overview of the analysis

The goal of the challenge was to use the features in the provided dataset to create a binary classifier that can predict whether applicants for funding will be successful if funded by Alphabet Soup.

## Results

# Data Preprocessing
What variable(s) are the target(s) for the model?
- "IS_SUCCESSFUL"
What variable(s) are the features for your model?
- "APPLICATION_TYPE", "AFFILIATION", "CLASSIFICATION", "USE_CASE", ORGANIZATION", "STATUS", "INCOME_AMT", "SPECIAL_CONSIDERATIONS", "ASK_AMT"
What variable(s) should be removed from the input data because they are neither targets nor features?
- "EIN", "NAME"

# Compiling, Training, and Evaluating the Model
How many neurons, layers, and activation functions did you select for your neural network model, and why?
- 2 hidden layers, 8 and 5 neurons each, both using "relo" activation function
Were you able to achieve the target model performance?
- No. Average accuracy my model was able to deliver was close to 72.50%
What steps did you take in your attempts to increase model performance?
- Tried changing the binning of highly variable features, increased number of layers to 4, increased number of neurons (summing to 63 neurons), tried dropping more columns.
