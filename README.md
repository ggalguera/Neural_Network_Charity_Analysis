# Neural Network Charity Analysis
## OVerview
The goal of this task is to help Beks, who is using machine learning and neural networks to predict where to make investments for Alphabet Soup foundation. Beks has received a CSV containing over 34,000 organizations that have received funding from Alphabet Soup in the past. The dataset includes various metadata columns, such as EIN, NAME, APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS, ASK_AMT, and IS_SUCCESSFUL. The task is to create a binary classifier using the dataset features that can predict whether an organization will be successful if funded by Alphabet Soup.

## Results Summary:
### Data Preprocessing:
Target variable(s): IS_SUCCESSFUL.
Feature variable(s): APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS, and ASK_AMT (standardized).
Variables to remove from input data: EIN and NAME
### Compiling, Training, and Evaluating the Model:
Neural Network Model architecture:
First hidden layer with 18 neurons and relu activation function.
Second hidden layer with 8 neurons and relu activation function.
Output layer with sigmoid activation function.
Target model performance was not achieved.
### Steps taken to try and increase model performance:
Added a new layer with 8 neurons.
Dropped ASK_AMT and tried standardizing it.
Tried different activation functions: sigmoid, tanh, softmax, and linear.

## Summary
The deep learning model that was built to predict the success of funding for organizations by Alphabet Soup using various metadata fields resulted in an accuracy of approximately 71.35%, which was not able to achieve the target performance.
To improve the model performance, a recommendation would be to try a different machine learning algorithm such as Random Forest or Gradient Boosting, which are effective for classification problems with a large number of input features. Both algorithms can handle categorical variables and can handle the nonlinear relationships between features.
Random Forest can create multiple decision trees and select the best features to make decisions, whereas Gradient Boosting trains many weak models sequentially and combines them into a strong model. Both algorithms also have hyperparameters that can be tuned to optimize the model performance.
