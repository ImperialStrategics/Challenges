# Credit Card Fraud

## Background

Credit card companies have a difficult time keeping their customers safe. One problem they face is fradulent transactions, how can they make sure their customers don't get charged for items they did not buy?

## Dataset

This dataset contains transactions over two days with 492 frauds out of 284,807 transactions. The dataset is highly unbalanced (frauds are only 0.172% of total transactions). For security reasons, the original features are replaced with features V1,V2, ... V28 which were obtained via principle component analysis (PCA) transformation. The only original features (with no PCA transformation) are 'Time' and 'Amount'. 'Time' represents the seconds elapsed between that transaction and the first one provided in the dataset. The feature 'Class' indicates if the transaction was fraudulent (1) or not fraudulent (0).

The dataset is provided in a simple `.csv` file located in the `dataset.csv.zip` archive. It is recommended to use the Python packages `numpy` and 'pandas` to read and manipulate the data.

## Guidance

This is not an exhaustive list of tasks, the points are provided in order to guide you:

### Understanding the Data

Due to the unbalanced nature of this dataset, identify a way to create a suitable training and testing set. Consider the need for scaling the data and explain how PCA transformation influences this decision. Explore and visualize the relationships between features and indentify any correlations.

### Feature Selection & Engineering

Select the most predictive features in the model. Which are useful and which aren't?

### Model

Select an appropriate model and tune it to improve its performance.

### Evaluation

Report your results using appropriate metrics and explain key decisions in your process. Suggest possible improvements.