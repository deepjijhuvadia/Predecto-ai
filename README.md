**Custom Model Predictor**

This code implements a Streamlit application for custom machine learning model training and evaluation for regression tasks. Users can upload a CSV dataset, preprocess the data, select features and target variables, choose a prediction algorithm, and train and evaluate the model. 

**Getting Started**

1. Ensure you have Python installed on your system, along with the following libraries:
   - numpy
   - pandas
   - matplotlib
   - streamlit
2. Clone or download this repository.
3. Open a terminal or command prompt and navigate to the project directory.
4. Run the application using `streamlit run main.py`.

**Code Structure**

* `preprocess_data.py`: Contains functions to preprocess data, including handling date columns and encoding categorical features.
* `train_test_split_custom.py`: Implements a custom function for splitting data into training and testing sets. 
* `linear_regression.py`: Provides a linear regression implementation.
* `ridge_regression.py`: Implements Ridge regression with an alpha parameter for regularization.
* `lasso_regression.py`: Implements Lasso regression with an alpha parameter for regularization.
* `gradient_boosting_regression.py`: Implements Gradient Boosting regression with hyperparameters for number of estimators and learning rate.
* `decision_tree_regression.py`: Implements a basic Decision Tree regression model.
* `r2_score.py`: Defines a function to calculate the R-squared score for regression evaluation.
* `mean_squared_error.py`: Defines a function to calculate the Mean Squared Error (MSE) for regression evaluation.
* `main.py`: The main script that builds the Streamlit application.

**Using the App**

1. Upload a CSV dataset using the file uploader.
2. The application displays a preview of the data.
3. Preprocessed data is displayed after feature engineering.
4. Select features and target columns for prediction.
5. Choose a prediction task from the dropdown menu (for informational purposes only).
6. Select a machine learning algorithm from the available options:
   - Linear Regression
   - Ridge Regression
   - Lasso Regression
   - Gradient Boosting Regression
   - Decision Tree Regression
7. Click the "Train and Evaluate" button.
8. The app displays the chosen algorithm and evaluation metrics, including R-squared and Mean Squared Error (MSE).
9. A scatter plot visualizes the actual vs. predicted values.
