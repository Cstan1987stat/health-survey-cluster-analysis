# Health Survey Cluster Analysis

## Project Overview
This project analyzes the 2022 NHIS (National Health Interview Survey) data to identify patterns and clusters among health indicators with R. Using exploratory data analysis, dimensionality reduction techniques, and clustering algorithms, this analysis aims to uncover meaningful segments within health survey respondents.

### Completed Work
* **[data preprocessing](https://github.com/Cstan1987stat/health-survey-cluster-analysis/blob/main/notebooks/data_preprocessing.ipynb)**: Code used to prreprocess the inital 2022 NHIS survey data, exported as [adult_22_filtered.csv](https://github.com/Cstan1987stat/health-survey-cluster-analysis/blob/main/adult22_filtered.csv)


* **[data understanding](https://github.com/Cstan1987stat/health-survey-cluster-analysis/blob/main/notebooks/data_understanding.ipynb)**: Analysis of dataset dimensions, variable types (categorical vs numerical, ordinal vs nominal), and data completeness. 

* **[univariate analysis](https://github.com/Cstan1987stat/health-survey-cluster-analysis/blob/main/notebooks/univariate_analysis.ipynb)**: Analysis of individual variables with:
  * Numerical variables: Summary statistics, density plots, and boxplots.
  * Categorical variables: Bar plots and proportion tables. 


* The [numerical bivariate analysis](https://github.com/Cstan1987stat/health-survey-cluster-analysis/blob/main/notebooks/bivariate_analysis_notebooks/numerical_bivariate_analysis.ipynb) notebooks provides a correlation heatmap and scatterplot for the numerical variables.
* The [categorical mixed bivariate analysis](https://github.com/Cstan1987stat/health-survey-cluster-analysis/blob/main/notebooks/bivariate_analysis_notebooks/categorical_mixed_bivariate_analysis.ipynb) notebook provides contingecy tables, chi-square tests results, and stacked bar charts for categorical variables. It also looks at the relationship between categorical and numerical variables by calculating the group-wise summary statistics, grouped boxplots, two-sample t-tests results, and ANOVA results.
 
