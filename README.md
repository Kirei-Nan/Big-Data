# Breast Cancer Survivability Prediction

This repository contains code and documentation for a data mining project that aims to predict the survivability rate of breast cancer patients using the Surveillance, Epidemiology, and End Results (SEER) Public-Use Data.

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Methodology](#methodology)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Introduction
The objective of this project is to apply data mining techniques to predict the survivability rate of breast cancer patients. By developing an accurate predictive model, we aim to assist healthcare professionals in making informed decisions and improving patient outcomes.

## Dataset
The dataset used in this project is the "Breast_Cancer_dataset.csv" file, which contains information about breast cancer patients from the SEER database. The dataset includes various features such as age, race, marital status, tumor size, and other relevant clinical information.

## Installation
To run the code in this repository, you need to have the following dependencies installed:
- Python (version 3.6 or higher)
- pandas
- numpy
- scikit-learn
- imbalanced-learn

You can install the required packages using pip:
```
pip install pandas numpy scikit-learn imbalanced-learn
```

## Usage
1. Clone this repository to your local machine.
2. Install the necessary dependencies as mentioned in the [Installation](#installation) section.
3. Place the "Breast_Cancer_dataset.csv" file in the same directory as the code files.
4. Open the Jupyter Notebook or Python script containing the code.
5. Run the code cells or execute the script to perform data preprocessing, feature selection, model training, and evaluation.
6. The results, including model performance metrics and feature importances, will be displayed in the notebook or console output.

## Methodology
The project follows the following methodology:
1. Data Loading and Exploration
2. Data Preprocessing
   - Encoding Categorical Variables
   - Handling Outliers
   - Dimensionality Reduction using PCA
3. Feature Selection and Ranking
   - Training and Evaluating Models (KNN, Naive Bayes, Decision Tree, Random Forest, Gradient Boosting)
4. Hyperparameter Tuning
   - Grid Search for KNN and Gradient Boosting
5. Results Analysis
   - Evaluation of Models with Best Hyperparameters
   - Feature Importance Analysis

## Results
The Gradient Boosting model achieved the highest performance with an accuracy of 0.977431, precision of 0.957025, recall of 1.0, and an F1 score of 0.978041 after hyperparameter tuning. The top three most important features were found to be PC6, PC5, and PC1.

## Contributing
Contributions to this project are welcome. If you find any issues or have suggestions for improvements, please open an issue or submit a pull request on the GitHub repository.

## License
This project is licensed under the [MIT License](LICENSE).

Feel free to customize the README file based on your specific project details and requirements.