# Census Data Analysis Project

This project uses census data to explore data analysis techniques and supervised learning models. It applies different classification algorithms to predict individuals' income class based on their demographic and socioeconomic characteristics.

## Data Source

The dataset was obtained from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Adult). This dataset is widely used for binary classification studies, such as predicting whether an individual's income is over 50K per year.

## Project Structure

- **dados_do_censo_anderson83.py**: Main script with data analysis and application of machine learning models.
- **adult.data**: Census data file used to train and evaluate the models.

## Prerequisites

The project was developed on Google Colab but can be run in any Python environment with the following libraries installed:

- `pandas`
- `seaborn`
- `matplotlib`
- `scikit-learn`

To install the dependencies, use:
```bash
pip install pandas seaborn matplotlib scikit-learn
```

## Execution

To run the project, follow these steps:

1. Connect to Google Drive, if using Colab, to access the data file (`adult.data`).
2. Define the path to the directory where the data file is saved.
3. Run each cell to load, preprocess, and visualize the data.
4. Test the classification models available in the script, such as Logistic Regression, Decision Tree, K-Nearest Neighbors, among others.

## Dataset Description

The dataset has the following columns:

- **age**: Age of the individual.
- **workclass**: Employment category (e.g., government, self-employed, etc.).
- **education**: Education level.
- **education-num**: Education level code.
- **marital-status**: Marital status.
- **occupation**: Occupation.
- **relationship**: Family relationship (e.g., wife, husband, etc.).
- **race**: Race.
- **sex**: Gender.
- **capital-gain**: Capital gain.
- **capital-loss**: Capital loss.
- **hours-per-week**: Hours worked per week.
- **native-country**: Country of origin.

The goal is to predict the **income** variable (above or below 50K per year) based on these characteristics.

## Machine Learning Models

The project includes the application of various classification algorithms, including:

- Logistic Regression
- Decision Tree
- K-Nearest Neighbors
- Random Forest
- Naive Bayes

These models are trained and evaluated to determine which offers the best performance in terms of accuracy and other evaluation metrics.

## Evaluation Metrics

The main metrics used to evaluate the models are:

- **Accuracy**
- **Confusion Matrix**

