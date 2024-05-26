## Description

The provided code is a demonstration of a machine learning workflow using Python libraries such as `pandas`, `numpy`, `seaborn`, and `scikit-learn`. Here's a breakdown of the tasks performed:

1. **Data Loading and Preprocessing**:
   - Loads a dataset from a CSV file named 'tested.csv' into a Pandas DataFrame.
   - Handles missing values in the 'Age' and 'Fare' columns by filling them with the mean value of each column.
   - Encodes categorical variables ('Embarked' and 'Sex') into numerical format.

2. **Data Visualization**:
   - Creates histograms to visualize the distribution of 'Age' and 'Fare' with respect to survival status.
   - Constructs a bar chart to display the count of survived and non-survived passengers.

3. **Data Splitting**:
   - Splits the dataset into training and testing sets using the `train_test_split` function.

4. **Model Building**:
   - Constructs a logistic regression model using `LogisticRegression` from scikit-learn.
   - Trains the model on the training data and evaluates its performance on the testing data.
   - Outputs the accuracy score of the logistic regression model.

This code serves as an example of how to load, preprocess, visualize, and build a machine learning model for binary classification tasks.
