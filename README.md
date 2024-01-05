# Identify Customer Segments with Arvato

## Table of Contents
1. [Introduction/Overview](#1-introductionoverview)
2. [Objectives](#2-objectives)
3. [Methodology/Approach](#3-methodologyapproach)
4. [Installation/Requirements](#4-installationrequirements)
5. [File Descriptions](#5-file-descriptions)
6. [Data Collection and Sources](#6-data-collection-and-sources)
7. [Results/Conclusions](#7-resultsconclusions)
8. [License](#8-license)

## 1. Introduction/Overview
In this project, Bertelsmann partners AZ Direct and Arvato Financial Solutions have provided two datasets one with demographic information about the people of Germany, and one with that same information for customers of a mail-order sales company. You’ll look at relationships between demographics features, organize the population into clusters, and see how prevalent customers are in each of the segments obtained.

`This project was completed as part of Udacity's Intro To Machine Learning Nanodegree`

## 2. Objectives
Apply unsupervised learning techniques on demographic and spending data for a sample of German households. Preprocess the data, apply dimensionality reduction techniques, and implement clustering algorithms to segment customers with the goal of optimizing customer outreach for a mail order company.

## 3. Methodology/Approach

- **Data Preparation**: Began with acquiring and understanding the demographic datasets. Cleaned and preprocessed the data to ensure it was ready for analysis.
- **Feature Transformation**: Implemented dimensionality reduction using Principal Component Analysis (PCA) to focus on the most informative aspects of the data.
- **Customer Segmentation**: Applied clustering techniques like KMeans to segment the population into distinct groups based on their demographics and behaviors.
- **Analysis and Insights**: Interpreted the clustering results to identify and understand the characteristics of each customer segment. Translated these findings into actionable business insights.

## 4. Installation/Requirements

- [Python](https://www.python.org/downloads/)
- [Jupyter Notebook](https://jupyter.org/install)

The following libraries are expected to be used in this project:
- `NumPy`
- `pandas`
- `Sklearn / scikit-learn`
- `Matplotlib` (for data visualization)
- `Seaborn` (for data visualization)

The code should run with no issues using Python versions 3.*.

## 5. File Descriptions
- `Identify_Customer_Segments.ipynb`: Jupyter Notebook divided into sections and guidelines for completing the project. The notebook provides more details and tips than the outline given here.

## 6. Data Collection and Sources
- `Udacity_AZDIAS_Subset.csv`: Demographic data for the general population of Germany; 891211 persons (rows) x 85 features (columns).
- `Udacity_CUSTOMERS_Subset.csv`: Demographic data for customers of a mail-order company; 191652 persons (rows) x 85 features (columns).
- `Data_Dictionary.md`: Information file about the features in the provided datasets.
- `AZDIAS_Feature_Summary.csv`: Summary of feature attributes for demographic data.

The data files have been removed in compliance with AZ Direct GmbH's terms and conditions, which restrict the use of their data solely to the Udacity course.

## 7. Results/Conclusions
- The company is performing well with older, more traditional individuals who live in less crowded areas and tend to focus on saving and investing, making mail-order sales more appealing to them.
- The company isn't as successful in reaching younger, educated people who live in densely populated areas and have higher consumption and materialistic tendencies.
- This group might prefer online shopping. However, with effective marketing, the company can better reach and serve this demographic.

Overall, the project successfully identified distinct customer segments using unsupervised learning and clustering algorithms like KMeans, coupled with Principal Component Analysis (PCA) for dimensionality reduction. The identified segments, characterized by unique demographic attributes, provide actionable insights for targeted marketing strategies.

## 8. License
Licensed under [MIT License](https://github.com/ManideepTelukuntla/InvestigateTMDBMovieData/blob/master/LICENSE)
