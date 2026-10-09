# House Price Prediction Using Linear Regression

## Project Overview

This project uses Machine Learning to predict house sale prices using the Ames Housing dataset. It was developed as a beginner project to practice data preprocessing, model training, and evaluation using Python.

## Objectives

* Explore and clean a real-world dataset.
* Handle missing numerical and categorical values.
* Convert categorical features using one-hot encoding.
* Train a Linear Regression model.
* Evaluate predictions using Mean Absolute Error (MAE) and R².
* Investigate prediction errors and experiment with preprocessing pipelines.

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib / Seaborn (if used in the notebook)
* Scikit-learn
* Google Colab

## Workflow

1. Load and explore the dataset.
2. Identify and handle missing values.
3. Encode categorical variables.
4. Separate features and target (`SalePrice`).
5. Split the data into training and testing sets.
6. Train a Linear Regression model.
7. Evaluate predictions using MAE and R².
8. Inspect large prediction errors.
9. Experiment with a preprocessing pipeline.

## Results

The initial Linear Regression model achieved:

* **MAE:** approximately 14,761
* **R²:** approximately 0.925

A later pipeline experiment achieved:

* **MAE:** approximately 29,493
* **R²:** approximately 0.725

The pipeline experiment did not improve the results. The difference showed that preprocessing choices can substantially affect model performance and should be investigated carefully.

## What I Learned

* Exploring and cleaning real-world data.
* Handling missing values and categorical features.
* Training a regression model using Scikit-learn.
* Evaluating model performance.
* Investigating prediction errors.
* Comparing preprocessing approaches and documenting unsuccessful experiments.

## Dataset

Ames Housing dataset. Include the original dataset source or download link used for this project here.

## Future Improvements

* Investigate why the preprocessing pipeline produced different results.
* Compare Linear Regression with other regression algorithms.
* Use cross-validation and more systematic feature engineering.
