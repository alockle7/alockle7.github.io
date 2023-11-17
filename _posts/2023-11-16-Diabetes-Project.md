# Modeling to Predict Diabetes

## Outline of the Project
The purpose of this project is to create a model that can predict diabetes in patients using the 
[`diabetes_binary_health_indicators_BRFSS2015.csv`](https://www.kaggle.com/datasets/alexteboul/diabetes-health-indicators-dataset/)
dataset. The first step is to perform an **Exploratory Data Analysis** on the variables on interest. Then we split the data into a
training dataset to train our models using 5-fold cross-validation, and a test dataset to test the model on. The models that we used include logistic regression, 
LASSO logistic regression, a classification tree, random forest, naive bayes, and Flexibile Discriminant Analysis. We then used logLoss as the method to select the best model.

## Reflections

### What would I do differently?

I would spend more time on Exploratory Data Analysis to make a more informed decision on which variables to include or exclude from my models. 

### What was the most difficult part for me?

The most difficult part for me was selecting a model that we did not cover in class. It took a bit of trial and error to find a model that is appropriate for this dataset.

### What are your big take-aways from this project?

My big takeaway is that it is important to select models that work for the data. For example, the type of model that I select depends on whether my goal is 
classification or regression. The purpose of this project was to classify, not predict a continuous response. Therefore, linear regression would not be a 
suitable model for this project.

## Links to Repos
The link to the GitHub repo is [here](https://github.com/halljc76/ST558_Project_3).  
And the link to the nicely rendered repo is [here](https://halljc76.github.io/ST558_Project_3/).
