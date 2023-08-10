# Bank Marketing Analysis and Term Deposit Subscription Prediction with H2O AutoML


## Table of Contents

- [Project Description](#project-description)
- [Dataset Information](#dataset-information)
- [Project Aim](#project-aim)
- [Technologies Used](#technologies-used)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Project Description

This project involves the analysis of bank marketing campaigns and the prediction of term deposit subscriptions. By utilizing machine learning techniques, we aim to uncover patterns in customer behavior and predict whether a client will subscribe to a term deposit based on various features.

## Dataset Information

The dataset used in this project is sourced from a Portuguese banking institution's direct marketing campaigns. It contains information about client demographics, loan history, marketing campaign details, and subscription history. The dataset is structured with both numerical and categorical attributes, making it suitable for classification tasks.

## Project Aim

The primary goal of this project is to build a predictive model that can accurately determine whether a client will subscribe to a term deposit based on the provided data. By leveraging H2O AutoML, we automate the process of training and selecting the best-performing machine learning model for this classification task.

## Technologies Used

- Python
- H2O AutoML
- Pandas
- NumPy
- Matplotlib

## Getting Started

1. Clone the repository.
2. Install the required dependencies by running `pip install -r requirements.txt`.
3. Download the dataset and place it in the appropriate directory (e.g., "Data" folder).
4. Open the Jupyter Notebook or Python script containing the project code.

## Usage

1. Load and explore the dataset using pandas.
2. Preprocess the data by merging relevant dataframes and removing unnecessary columns.
3. Initialize H2O environment and convert data to H2O dataframe.
4. Split the data into training and testing sets.
5. Train an AutoML model using H2O AutoML, specifying parameters such as runtime and stopping metric.
6. Evaluate model performance and explore the leaderboard to identify the best-performing model.
7. Further analyze the selected model, such as inspecting variable importances.

## Results

The project results include:

- Identification of the best-performing model using H2O AutoML.
- Evaluation metrics for the selected model on the test set.
- Insights into variable importances and feature contributions.
