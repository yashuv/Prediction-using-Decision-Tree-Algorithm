# Prediction using Decision Tree Algorithm
This is the `third` project I completed in my internship at __TheSparksFoundation__ for the function "Data Science and Business Analytics."

## Task:
* Create the Decision Tree classifier and visualize it graphically.
* The purpose is if we feed any new data to this classifier, it would be able to predict the right class accordingly.
* Dataset : https://bit.ly/3kXTdox

## Solution:
Decision tree classifier is implemented such that if we feed any new data to this classifier, it would be able to predict the right class accordingly. Decision tree classifier a type of supervised learning algorithm that can be used for classification tasks. It works by constructing a tree-like model of decisions based on the features of the training data.

I accomplished the project task under following steps:

## 1. Importing necessary libraries
Importing library in a Python script allows you to use the functions, classes, and other objects defined in those libraries in your code and makes it easier to accomplish tasks.

For example, I imported the Pandas library to use its data manipulation and analysis tools.

## 2. Load Dataset
Loading a dataset is an important step in the data science process because it allows you to access the data and begin working with it. There are many different ways to load a dataset, depending on where the data is stored and how it is formatted.

For example: I loaded the data from `csv file`.

## 3. Exploratory Data Analysis (EDA)
It is a valuable tool for understanding and gaining insights from data, and uncovering any issues or anomalies. It can also be used to generate ideas for further research or to communicate findings to others.and is an important step in the data science process.

Some common techniques I used in EDA include:

* __Visualizing the data:__ Plotting the data help you get a sense of the distribution and relationships between variables. for eg: histogram, boxplot, pairplot, and decision tree are used in this project for visualizing purpose.

* __Summarizing the data:__ Calculating summary statistics such as mean, median, and standard deviation can help you get a sense of the central tendency and spread of the data.

* __Checking for missing values:__ Make sure there are no missing values in the data set, as these can cause issues with analysis and modeling.

* __Checking for outliers:__ Look for any unusual or extreme values that could be causing skews in the data. for eg: Some outliers are removed from dataset in this project for better model performance.

## 4. Model building
It is the process of creating a mathematical or statistical model to represent the relationships and patterns in a dataset. Model building is a common task in data science and machine learning, as it allows you to make predictions or inferences about the data based on the patterns identified in the model.

There are many different types of models that can be built, including linear models, logistic regression models, decision trees, and neural networks. The choice of model will depend on the type of data and the specific goals of the analysis.

`Decision tree classifier` is implemented in this project.

## 5. Performance evaluation
It is an important step in the model building process, as it allows you to assess the effectiveness of the model and make any necessary adjustments to improve its performance. It is also important to evaluate the performance of a model on unseen data, as this can provide a more realistic assessment of its performance on real-world tasks. 

To calculate evaluation metrics for a decision tree classifier, I performed use the following steps:

* Split the data into a training set and a test set.
* Fit the model to the training set.
* Use the model to make predictions on the test set.
* Calculate the evaluation metrics using the predictions and the true values.

Some common *performance evaluation metrics* for the decision tree classifier are:
* __Accuracy:__ It is the proportion of correct predictions made by the model.
*  __Precision:__ It is the proportion of correct positive predictions made by the model.
* __Recall:__ It is the proportion of actual positive cases that were correctly predicted by the model.
* __F1 score:__ It is the harmonic mean of precision and recall.

## 6. Making Predictions
After having trained a machine learning model, you can use it to make predictions on our own data. I did this by calling a prediction function on the model, passing in the new data as an input.

For example: The model predicts the species of Iris flower when it is given the dimensions of flowers as indicated.

## Conclusion:
Decision tree classifiers are popular because they are easy to understand and interpret, and they can handle both numerical and categorical data. They are also relatively fast to train and make predictions with, which makes them a good choice for many practical applications.

<br>

__Thank You and Happy Learning!__