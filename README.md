# EDA-Titanic-Dataset
Implemented Missingno python library and used regular expressions and also implemented process engineering and also very important one pandas profiling and the final report has been attached.

# What is exploratory data analysis?
Learn everything you need to know about exploratory data analysis, a method used to analyze and summarize data sets. 

Exploratory data analysis (EDA) is used by data scientists to analyze and investigate data sets and summarize their main characteristics, often employing data visualization methods. It helps determine how best to manipulate data sources to get the answers you need, making it easier for data scientists to discover patterns, spot anomalies, test a hypothesis, or check assumptions.

EDA is primarily used to see what data can reveal beyond the formal modeling or hypothesis testing task and provides a provides a better understanding of data set variables and the relationships between them. It can also help determine if the statistical techniques you are considering for data analysis are appropriate. Originally developed by American mathematician John Tukey in the 1970s, EDA techniques continue to be a widely used method in the data discovery process today.

# Why is exploratory data analysis important in data science?
The main purpose of EDA is to help look at data before making any assumptions. It can help identify obvious errors, as well as better understand patterns within the data, detect outliers or anomalous events, find interesting relations among the variables.

Data scientists can use exploratory analysis to ensure the results they produce are valid and applicable to any desired business outcomes and goals. EDA also helps stakeholders by confirming they are asking the right questions. EDA can help answer questions about standard deviations, categorical variables, and confidence intervals. Once EDA is complete and insights are drawn, its features can then be used for more sophisticated data analysis or modeling, including machine learning.

# Exploratory data analysis tools
Specific statistical functions and techniques you can perform with EDA tools include:

- Clustering and dimension reduction techniques, which help create graphical displays of high-dimensional data containing many variables.
- Univariate visualization of each field in the raw dataset, with summary statistics.
- Bivariate visualizations and summary statistics that allow you to assess the relationship between each variable in the dataset and the target variable you’re looking at.
- Multivariate visualizations, for mapping and understanding interactions between different fields in the data.
- K-means Clustering is a clustering method in unsupervised learning where data points are assigned into K groups, i.e. the number of clusters, based on the distance from each group’s centroid. The data points closest to a particular centroid will be clustered under the same category. K-means Clustering is commonly used in market segmentation, pattern recognition, and image compression.
- Predictive models, such as linear regression, use statistics and data to predict outcomes.

Some of the most common data science tools used to create an EDA include:

Python: An interpreted, object-oriented programming language with dynamic semantics. Its high-level, built-in data structures, combined with dynamic typing and dynamic binding, make it very attractive for rapid application development, as well as for use as a scripting or glue language to connect existing components together. Python and EDA can be used together to identify missing values in a data set, which is important so you can decide how to handle missing values for machine learning.
R: An open-source programming language and free software environment for statistical computing and graphics supported by the R Foundation for Statistical Computing. The R language is widely used among statisticians in data science in developing statistical observations and data analysis.

# Missingno Python Library

In the case of a real-world dataset, it is very common that some values in the dataset are missing. We represent these missing values as NaN (Not a Number) values. But to build a good machine learning model our dataset should be complete. That’s why we use some imputation techniques to replace the NaN values with some probable values. But before doing that we need to have a good understanding of how the NaN values are distributed in our dataset.

Missingno library offers a very nice way to visualize the distribution of NaN values. Missingno is a Python library and compatible with Pandas.

Missing number is a library which gives the visualization of missing values in Python

https://medium.com/towards-data-science/using-the-missingno-python-library-to-identify-and-visualise-missing-data-prior-to-machine-learning-34c8c5b5f009

This has only four functions
Bar Plot
Matrix Plot
Heatmap
Dendogram Plot

# Pandas Profiling

https://pypi.org/project/pandas-profiling/

https://www.geeksforgeeks.org/pandas-profiling-in-python/

The pandas_profiling library in Python include a method named as ProfileReport() which generate a basic report on the input DataFrame. 

The report consist of the following:

DataFrame overview,
Each attribute on which DataFrame is defined,
Correlations between attributes (Pearson Correlation and Spearman Correlation), and
A sample of DataFrame.

Pandas library offers a wide range of functions. It helps in data manipulation and provides a large pool of functionalities for almost every task. One common Pandas function is pandas describe. It presents the user with a descriptive statistical summary of all the features of the dataset. Though it is useful to understand the data still it doesn’t offer many features.

Pandas profiling is the solution to this problem. It offers report generation for the dataset with lots of features and customizations for the report generated. In this article, we will explore this library, look at all the features provided, and some of the advanced use cases and integrations that can prove useful to create stunning reports out of the data frames!
