## End to End machine learning project(BMI Calculator)

This is a simple BMI (Body Mass Index) predictor using a linear regression model. The program takes in height and weight as input and predicts the corresponding BMI.

# Running the Program

Download the bmidata.csv file and place it in the same directory as the Python script.

Run the Python script using your favorite Python interpreter (e.g., python bmi_predictor.py).

Enter your height and weight when prompted.

The program will output your predicted BMI.

# How it Works
### The program uses the following steps to predict BMI:

Loads the bmidata.csv file into a Pandas dataframe.
Calculates the BMI for each row in the dataframe using the calculate_bmi function.
Splits the data into training and testing sets using Scikit-learn's train_test_split.
Trains a linear regression model on the training data.
Uses the trained model to predict BMI for new input data.
Evaluates the model's performance using mean squared error (MSE).
### Functions:

calculate_bmi(height, weight)
Calculates the BMI given height and weight.

predict_bmi(height, weight)
Uses the trained linear regression model to predict BMI given height and weight.

# Dependencies
Pandas (for data manipulation)
Scikit-learn (for linear regression and model evaluation)

