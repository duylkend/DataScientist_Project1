# Ford GoBike System Data Analysis

## Project Overview

This project explores the Ford GoBike System Data to analyze trip patterns, user behaviors, and other relevant factors that influence the bike-sharing system's operations. By leveraging data science techniques, this project aims to provide insights that can optimize the system's efficiency and user experience.

## Motivation

The main motivation behind this project is to:
1. Understand the factors influencing trip duration.
2. Understanding peak usage times can help in optimizing bike distribution and station management.
3. Analyzing bike usage across different user demographics can guide targeted marketing strategies and service improvements.
4. Identifying popular stations can help in optimizing bike placement and ensuring that high-demand areas are well-served.

## Libraries Used

The following Python libraries were used in this project:
- `pandas`: For data manipulation and analysis.
- `numpy`: For numerical operations.
- `matplotlib`: For creating visualizations.
- `seaborn`: For enhanced data visualizations.
- `scikit-learn`: For data preprocessing, machine learning models, and clustering.
- `sklearn.preprocessing`: For transforming data, including scaling, normalization, encoding, and imputation.
- `sklearn.impute`: Specifically for handling missing values in datasets
- `sklearn.cluster`: For clustering algorithms, such as K-Means.
- `statsmodels.api`: For statistical computations and modeling, including regression analysis, time series analysis, and hypothesis testing.

## Files in the Repository

- **FordGoBike_Data_Analysis.ipynb**: Jupyter Notebook containing the full analysis, including data preparation, exploratory data analysis (EDA), modeling, and visualization.
- **201902-fordgobike-tripdata.csv**: Directory containing the Ford GoBike dataset used in the analysis. (Ensure you include a sample dataset or instructions on how to obtain it.)
- **README.md**: This file, providing an overview of the project, libraries used, results summary, and acknowledgements.

## Summary of Results

### Key Insights:
1. Peak usage times: Identifying when bike demand is highest.
2. Popular start and end stations: Understanding where bikes are most in demand and returned.
3. User behavior: Analyzing differences in usage patterns between subscribers and customers.
### Recommendations:
- **Redistribution Strategy**: 
	 - Based on peak usage times, it is recommended to allocate more bikes to high-demand areas during peak hours.
	 - Understanding peak usage times can help in optimizing bike distribution and station management.
	 - Analyzing bike usage across different user demographics can guide targeted marketing strategies and service improvements.
	 - Identifying popular stations can help in optimizing bike placement and ensuring that high-demand areas are well-served.
- **Targeted Marketing**: Tailor marketing campaigns to convert casual customers into subscribers by offering incentives during specific hours or seasons.

## Acknowledgements

I would like to acknowledge the following:
- **Bay Wheels (formerly Ford GoBike)**: For providing the data used in this analysis.
- **Udacity**: For their Data Scientist Nanodegree program, which provided the foundation for conducting this project.

## How to Use This Repository

1. Clone this repository to your local machine.
   ```bash
   git clone https://github.com/duylkend/DataScientist_Project1.git
   
2. Blog
	https://duylkend.github.io/FordGoBike_Data_Analysis.html