Regression with Abalone Dataset
Overview

This project aims to build and evaluate various regression models using the Abalone dataset. The primary objective is to predict the age of abalones based on physical measurements.
Dataset

The dataset used in this project is the Abalone dataset, which contains the following attributes:

    Sex: M, F, and I (infant)
    Length: longest shell measurement (in mm)
    Diameter: perpendicular to length (in mm)
    Height: with meat in shell (in mm)
    Whole weight: whole abalone (in grams)
    Shucked weight: weight of meat (in grams)
    Viscera weight: gut weight (in grams)
    Shell weight: after being dried (in grams)
    Rings: integer (age of abalone is rings + 1.5)

The target variable is the number of rings, which serves as an indicator of the abalone's age.
Dependencies

To run the notebook, you need the following Python libraries:

    pandas
    numpy
    matplotlib
    seaborn
    scikit-learn

You can install these libraries using pip:

  pip install pandas numpy matplotlib seaborn scikit-learn

Notebook Structure

    Data Loading and Preprocessing:
        Load the dataset
        Explore and preprocess the data

    Exploratory Data Analysis (EDA):
        Visualize the distribution of features
        Understand correlations between features and the target variable

    Model Building:
        Split the data into training and testing sets
        Train different regression models including:
            Linear Regression
            Support Vector Regression (SVR)
            Decision Tree Regression
            Random Forest Regression
            Gradient Boosting Regression

    Model Evaluation:
        Evaluate models using:
            Mean Absolute Error (MAE)
            Mean Squared Error (MSE)
            Root Mean Squared Error (RMSE)
            R-squared (R²)

    Results Comparison:
        Compare the performance of different models based on MAE and MSE

How to Use

    Clone the repository or download the notebook.
    Install the required dependencies.
    Open the notebook using Jupyter Notebook or Jupyter Lab.
    Follow the steps in the notebook to load the data, preprocess it, build models, and evaluate their performance.

Results

After training and evaluating multiple models, the following results were obtained:

    Model 1:
        MAE: 1.3964
        MSE: 4.1237

    Model 2:
        MAE: 2.2696
        MSE: 10.6270

    Model 3:
        MAE: 1.7494
        MSE: 7.0996

    Model 4:
        MAE: 1.2917
        MSE: 3.6116

    Model 5:
        MAE: 1.2991
        MSE: 3.6815

Model 4 had the best performance with the lowest MAE and MSE.
Conclusion

The notebook demonstrates how to build and evaluate regression models using the Abalone dataset. The results indicate that Model 4, which achieved the lowest MAE and MSE, is the most effective for predicting abalone age in this context.
