# Neural_Network_Charity_Analysis

## Analysis Overview
**The purpose of this project is to use TensorFlow and deep learning neural networks to analyze and classify the success outcome of charitable organizations. Using the following methods  will help explain the outcome of for the anlysis:**

- **Preprocessing Data for a Neural Network Model**
- **Compile, Train, and Evaluate the Model**
- **lastly Optimize the Model**

## Results

### **Data Prepreocessing**

- **The `"IS_SUCCESSFUL"` column contains binary data referring to whether or not the charity donation was used effectively. This variable is the target for the deep learning neural network model.**

- **The `"APPLICATION_TYPE", "AFFILIATION", "CLASSIFICATION", "USE_CASE", "ORGANIZATION", "INCOME_AMT", "SPECIAL_CONSIDERATIONS", "ASK_AMT"` columns the features of the model. Encoding the categorical varibles, splitting into training and testing datasets and standardization have been applied to these columns.**

- **The `"EIN","NAME"` columns are neither targets nor fetaures and have been removed from the input data.**

## Complining, Training, and Evaluating the Deep Neural Network Model

- **This deep-learning network model is made of two hidden layers with 120 abd 50 neurons respectively.**

  - **The inut data has 43 features and 25,724 samples.** 
  - **The output layer is made ofa unique neuron as it is a binary classification.**

- 




## Resources
- **Alphabet Soup Charity Data:** [Charity_Data](https://2u-data-curriculum-team.s3.amazonaws.com/dataviz-online/module_19/charity_data.csv)

- **Software: Python 3.8.8, Anconda Navigator 2.1. 1, Conda 4.11.0, Jupyter notebook 6.4.6**
