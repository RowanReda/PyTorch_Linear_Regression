# PyTorch Regression: Linear Regression using ANN
## Project Description
This project implements linear regression models using Artificial Neural Networks (ANNs) in PyTorch to analyze the relationship between housing prices and various features in a dataset. Two separate notebooks are provided:

1. Area Only Model: This notebook focuses solely on predicting housing prices using the 'area' feature.
2. All Features Model: This notebook utilizes all available features in the dataset for predictions.
   
The goal is to build, train, and evaluate both models, aiming for an expected R-squared value of +0.75. The project includes data preprocessing, normalization, and performance evaluation metrics such as Mean Squared Error (MSE), Mean Absolute Error (MAE), and R-squared. Visualizations are included to compare predicted prices against actual values, demonstrating the effectiveness of each model.

## Objective
This project aims to perform linear regression using an Artificial Neural Network (ANN) implemented in PyTorch. The objective is to analyze the relationship between housing prices and the area in a dataset, build and train the ANN model, and evaluate its performance.

## Dataset Description
- **Dataset Name**: `Housing-1.csv`
- **Description**: This dataset contains information about housing prices and relevant features, including 'area' as the main feature used for predictions. The dataset includes various other features encoded for analysis.

## Steps to Run the Code in Colab
1. Open [Google Colab](https://colab.research.google.com/).
2. Click on **File** > **Upload notebook** to upload your `.ipynb` file.
3. Install the required libraries by running !pip install torch torchvision pandas sklearn matplotlib in a new cell.
4. Upload the Housing-1.csv file to Colab.
5. Ensure the `Housing-1.csv` dataset is uploaded to the same directory as your notebook.
6. Run all the cells in the notebook sequentially.

## Dependencies
The following libraries are required to run the code:
- `torch` (for PyTorch)
- `pandas` (for data manipulation)
- `numpy` (for numerical operations)
- `scikit-learn` (for data preprocessing and evaluation)
- `matplotlib` (for plotting)


