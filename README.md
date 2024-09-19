# Breast Cancer Classification

## Project Description

This project focuses on classifying breast cancer data using several machine learning models. The primary aim is to evaluate and compare the performance of Logistic Regression, Decision Tree, and Random Forest classifiers in predicting cancer diagnosis.

The dataset used includes various features related to breast cancer characteristics. This project includes data preprocessing, model training, and evaluation phases.

## Dataset

The dataset used is `Breast_cancer_dataset.csv`, which contains the following columns:
- `id`
- `diagnosis`
- `radius_mean`
- `texture_mean`
- `perimeter_mean`
- `area_mean`
- `smoothness_mean`
- `compactness_mean`
- `concavity_mean`
- `concave points_mean`
- `texture_worst`
- `perimeter_worst`
- `area_worst`
- `smoothness_worst`
- `compactness_worst`
- `concavity_worst`
- `concave points_worst`
- `symmetry_worst`
- `fractal_dimension_worst`
- `Unnamed: 32` (which is often an empty or irrelevant column)

## Getting Started

To run this project, follow these steps:

1. **Clone the Repository:**

    ```bash
    git clone https://github.com/kaggle/Breast_Cancer_Classification.git
    ```

2. **Navigate to the Project Directory:**

    ```bash
    cd Breast_Cancer_Classification
    ```

3. **Install Required Libraries:**

    It is recommended to create a virtual environment and install the dependencies using:

    ```bash
    pip install -r requirements.txt
    ```

    `requirements.txt` should include the following libraries:

    ```
    pandas
    scikit-learn
    numpy
    ```

4. **Update File Path:**

    Update the `file_path` variable in the code to the location of your dataset.

5. **Run the Code:**

    Execute the Jupyter notebook or Python script to perform the classification and see the results.

## Evaluation

The project evaluates three classification models:
- Logistic Regression
- Decision Tree
- Random Forest

For each model, performance metrics such as accuracy, precision, recall, and F1-score are reported.


## Acknowledgements

- Breast cancer dataset from [kaggle]
- Scikit-learn for machine learning algorithms and evaluation metrics.

