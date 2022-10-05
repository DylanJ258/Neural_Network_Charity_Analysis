# Neural_Network_Charity_Analysis
## Overview
Beks has come a long way since her first day at that boot camp five years ago—and since earlier this week, when she started learning about neural networks! Now, she is finally ready to put her skills to work to help the foundation predict where to make investments.

With your knowledge of machine learning and neural networks, you’ll use the features in the provided dataset to help Beks create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup.

## Results
### Data Preprocessing
* What variable(s) are considered the target(s) for your model?
  * The target is the IS_SUCCESSFUL column.
* What variable(s) are considered to be the features for your model?
  * APPLICATION_TYPE—Alphabet Soup application type
  * AFFILIATION—Affiliated sector of industry
  * CLASSIFICATION—Government organization classification
  * USE_CASE—Use case for funding
  * ORGANIZATION—Organization type
  * STATUS—Active status
  * INCOME_AMT—Income classification
  * SPECIAL_CONSIDERATIONS—Special consideration for application
  * ASK_AMT—Funding amount requested
* What variable(s) are neither targets nor features, and should be removed from the input data?
  * EIN and NAME—Identification columns, are neither targets or features and should be removed from the input data.

### Compiling, Training, and Evaluating the Model
* How many neurons, layers, and activation functions did you select for your neural network model, and why?
  * I decided to use 100 and 30 neurons for my hidden networks
* Were you able to achieve the target model performance?
  * I was not able to achieve the target model performance.
* What steps did you take to try and increase model performance?
  *  In attempt 1 I increased the number of neurons in the hidden layers. In attempt 2 I added a hidden layer. In attempt 3 I increased the number of epochs. All attempts failed to reach the desired outcome.
  
## Summary
* Despite multiple attempts, the model didnt reach the desired outcome of 75% accuracy.
* A supervised machine learning model, like Random Forest Classifier, might be a better option.
