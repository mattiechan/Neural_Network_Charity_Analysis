# Neural_Network_Charity_Analysis
## Project Overview
I am demonstrating Neural Networks Machine Learning algorithm for this project on credit analysis. Creating a binar classifier in addition to machine learning and neural networks, I will be working on a dataset provided by _Alphabet Soup_, to predict whether applicants will be successful or not. The dataset contains information on more than 34,000 organzations that had received funding.     

## Data Reprocessing
• **What variable(s) are considered the target(s) for your model?**<br/>

The variable that are targeted in this model is the "IS_SUCCESSFUL" column. The target variable is also known as the dependent variable which is used to train our ML model.<br/>

• **What variables(s) are considered to be the features for your model?**<br/>

All columns are considered variables to be features in the model, except target variable in addition to the columns we dropped, "EIN" and "NAME". 

• **What variable(s) are neither targets nor features, and should be removed from the input data?**<br/>

The variables that should be removed from the input data from being neither targets nor features are variables that do not effect the model. Any outliers should be removed as well as any that is not essential to the model. 

## Compiling, Training, and Evaluating the Model
• **How many neurons, layers, and activation functions did you select for your neural network model, and why?**<br/>

I used two layers because there was no significance in adding another layer. The activation function I chose to use was **relu**. 200 neurons were used. 


