# MEDICAL-INSURANCE-COST-PREDICTION

#MEDICAL INSURANCE PRICE PREDICTION

This project involves predicting the cost of medical insurance using a linear regression model. The main goal is to predict charges based on various attributes such as age, sex, BMI, number of children, smoking status, and region. The dataset consists of the following attributes:

Age: The age of the individual.
Sex: The gender of the individual (male or female).
BMI: Body Mass Index, a measure of body fat based on height and weight.
Children: The number of children/dependents covered by the insurance.
Smoker: Whether the individual is a smoker (yes or no).
Region: The residential area of the individual.
Charges: The medical insurance cost to be predicted.
Dataset
The dataset used in this project contains the above attributes. Charges is the target variable (y) that needs to be predicted, and it depends on the other attributes (X).

Libraries Used
NumPy: For creating arrays and performing numerical operations.
Pandas: For creating and manipulating the dataframe.
Matplotlib: For creating visualizations such as bar plots and scatter plots.
Seaborn: For enhanced visualizations.
Scikit-Learn (sklearn): For applying the linear regression algorithm and evaluating the model.
Project Workflow
Data Loading and Preprocessing:

Load the dataset using Pandas.
Perform any necessary preprocessing steps such as handling missing values and encoding categorical variables.
Exploratory Data Analysis (EDA):

Use Matplotlib and Seaborn to create visualizations and understand the relationships between variables.
Splitting the Dataset:

Split the dataset into training and testing sets using Scikit-Learn's train_test_split.
Model Training:

Apply a linear regression algorithm to the training data to build the model.
Model Evaluation:

Evaluate the model using metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), and R-squared value.
Prediction:

Use the trained model to predict the charges for the test dataset.
