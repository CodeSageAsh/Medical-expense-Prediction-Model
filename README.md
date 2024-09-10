# Predicting Medical Expenses Using Linear Regression

## Overview

This project aims to predict medical expenses based on various factors using Linear Regression. The notebook explores the relationships between variables such as age, sex, BMI, children, smoker status, and region, and how these factors influence the cost of medical expenses.

## Dataset

The dataset used for this project contains 1,338 records with the following features:
- **Age**: Age of the primary beneficiary
- **Sex**: Gender of the beneficiary (male/female)
- **BMI**: Body mass index, providing an estimate of body fat
- **Children**: Number of children covered by health insurance
- **Smoker**: Whether the beneficiary is a smoker or non-smoker
- **Region**: The beneficiary's residential area in the US (northeast, northwest, southeast, southwest)
- **Charges**: Individual medical costs billed by health insurance

## Project Structure

- **Data Exploration and Visualization**: Initial exploration of the data to understand the distribution of variables, and identify potential relationships.
- **Data Preprocessing**: Handling missing values, encoding categorical variables, and feature scaling.
- **Model Building**: Implementation of a Linear Regression model to predict medical expenses.
- **Model Evaluation**: Evaluation metrics such as Mean Squared Error (MSE) and R-squared (R²) are used to assess model performance.
- **Interpretation**: Understanding the impact of each feature on medical expenses.

## Key Findings

- **Smoking** is identified as the most significant factor affecting medical expenses.
- **BMI** and **age** also play crucial roles, with higher values generally leading to increased charges.
- The model provides insights into how lifestyle and demographic factors influence healthcare costs.

## How to Use

1. **Open the notebook**:
   - You can open the notebook in Jupyter Notebook, JupyterLab, or any other compatible environment to run the code cells and visualize the results.

## Dependencies

The following Python libraries are required to run this notebook:
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

## Contributing

Feel free to contribute to this project by creating issues, suggesting improvements, or submitting pull requests.

## Contact

For any questions or feedback, please reach out via [palweashmit@gmail.com]
