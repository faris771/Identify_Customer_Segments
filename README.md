# Project: Identify Customer Segments

## Overview

In this project, we apply unsupervised learning techniques to identify segments of the population that form the core customer base for a mail-order sales company in Germany. The goal is to use these segments to direct marketing campaigns towards audiences that will have the highest expected rate of returns. The data used in this project is provided by Bertelsmann Arvato Analytics and represents a real-life data science task.

This project is part of the Palestine Launchpad by **Spark**, and **Udacity** with **Google**. 

## Data

The project uses the following datasets:
- `Udacity_AZDIAS_Subset.csv`: Demographics data for the general population of Germany.
- `Udacity_CUSTOMERS_Subset.csv`: Demographics data for customers of a mail-order company.
- `Data_Dictionary.md`: Detailed information about the features in the provided datasets.
- `AZDIAS_Feature_Summary.csv`: Summary of feature attributes for demographics data.

## Steps

### 1. Data Preprocessing
- **Assess Missing Data**: Identify and handle missing values in the dataset.
- **Feature Selection and Encoding**: Select relevant features and encode categorical variables.
- **Feature Engineering**: Engineer new features from mixed-type features.

### 2. Feature Transformation
- **Scaling**: Apply feature scaling to standardize the data.
- **Dimensionality Reduction**: Use Principal Component Analysis (PCA) to reduce the dimensionality of the data.

### 3. Clustering
- **Apply Clustering**: Use K-means clustering to segment the general population into clusters.
- **Cluster Analysis**: Compare the customer data to the general population clusters to identify overrepresented and underrepresented segments.

## Findings

- **Overrepresented Clusters**: Certain clusters have a higher proportion of customers compared to the general population, indicating segments that are relatively popular with the mail-order company.
- **Underrepresented Clusters**: Some clusters have a lower proportion of customers compared to the general population, indicating segments that are relatively unpopular with the mail-order company.

## Conclusion

By analyzing the principal components and the characteristics of the overrepresented and underrepresented clusters, we can infer the types of people who are more or less likely to be customers of the mail-order company. This information can be used to target marketing campaigns more effectively.

## Files

- `Identify_Customer_Segments.ipynb`: Jupyter notebook containing the full analysis and code.
- `README.md`: This file, providing an overview of the project.

## Requirements

- Python 3.x
- Jupyter Notebook
- Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn

## Usage

1. Clone the repository.
2. Open `Identify_Customer_Segments.ipynb` in Jupyter Notebook.
3. Run the cells to perform the analysis.
