# Part-3-Regression-with-Multiple-Linear-Algorithm
 An assignment for DSC530 at GCU that focused on applying a multiple linear regression algorithm to make predictions using a dataset.

Check out the full report [here.](https://github.com/jhould007/DSC530-Topic-1-Part-3-Regression-with-Multiple-Linear-Algorithm/blob/main/Part%203%20Regression%20with%20Multiple%20Linear%20Algorithm.ipynb)

# Assignment Instructions
Often, you may want to train your model using more than one independent variable and a label. This is known as multiple regression, in which two or more independent variables are used to predict the value of a dependent variable. Some real-world examples of its use include predicting next year's Gross National Product (GNP) based on last year's GNP, current interest rate, unemployment, and some other variables.

To demonstrate completion of this assignment, create a Microsoft Word document with your working code, screenshots of program results, and written answers to questions. Writing should be professional and rigorous, and include scientific/mathematical justification, where appropriate, for all conclusions reached. Upload your final Jupyter notebook and Word document to the digital classroom when complete.
For this activity, in 250-500 words, answer the following:

1. Make sure all necessary libraries are loaded. Print your x (independent) and y (dependent) variables from the data frame. Show the results.
2. Fit an ordinary least square method using the OLS method from the seaborn library to figure out your most significant variables. Show the results and interpret the following:
 * R-squared
 * Adjusted. R-Squared
 * Degree of freedom
 * Coefficient of determination and P-values
3. Test, identify, and detect multicollinearity in your dataset. Explain how you resolved it and report the results.
4. Fit a linear regression model using the linear regression method from scikit-learn library. Obtain the coefficients and interpret the results.
5. Split the data into 80% training and 20% testing sets using the train_test_split class.
6. Train the multiple regression model on the training set using the LinearRegression class.
7. Make regression predictions and interpret your results in the context of the question(s) you're trying to answer.
8. Validate your multiple regression model using a confusion matrix, accuracy score, and k-fold cross-validation.

APA style is not required, but solid academic writing is expected. This assignment uses a rubric. Please review the rubric prior to beginning the assignment to become familiar with the expectations for successful completion. You are not required to submit this assignment to LopesWrite.
