# Pymaceuticals SCC Study Analysis

This repository contains the analysis of a pharmaceutical company's study on potential treatments for squamous cell carcinoma (SCC), a form of skin cancer. The study compared the performance of Pymaceuticals’ drug of interest, Capomulin, against other treatment regimens.

## Project Overview

As a senior data analyst at Pymaceuticals, Inc., I was tasked with generating all tables and figures needed for the technical report of the clinical study. This involved various data analysis and visualization tasks, including:

- Data preparation
- Summary statistics generation
- Bar charts and pie charts creation
- Quartiles calculation, outlier detection, and box plot creation
- Line plot and scatter plot generation
- Correlation and regression analysis

- `mouse_metadata.csv`: Contains metadata for each mouse, including the mouse ID, drug regimen, sex, and age.
- `study_results.csv`: Contains the results of the study, including the mouse ID, timepoint, tumor volume, and metastatic sites.

## Tasks Completed

- **Data Preparation**: Merged the mouse metadata and study results dataframes, removed duplicate data, and cleaned the dataset.
- **Summary Statistics**: Calculated mean, median, variance, standard deviation, and SEM of the tumor volume for each drug regimen.
- **Bar Charts and Pie Charts**: Generated bar charts and pie charts to visualize the distribution of drug regimens and the gender distribution of the mice.
- **Quartiles, Outliers, and Box Plot**: Calculated quartiles, detected outliers, and created a box plot to visualize the final tumor volume for each treatment regimen.
- **Line Plot and Scatter Plot**: Generated a line plot to visualize tumor volume over time for a mouse treated with Capomulin and a scatter plot to visualize the relationship between mouse weight and average tumor volume for the Capomulin regimen.
- **Correlation and Regression**: Calculated the correlation coefficient and performed linear regression analysis between mouse weight and average tumor volume for the Capomulin regimen.

## Results and Observations

1. The drug regimen Capomulin showed promising results in reducing tumor volume compared to other treatments.
2. There was a strong positive correlation between mouse weight and average tumor volume for mice treated with Capomulin.
3. Out of the four treatment regimens analyzed (Capomulin, Ramicane, Infubinol, and Ceftamin), Infubinol had the highest number of potential outliers in the final tumor volume.

## Dependencies

The project was implemented in Python using the following libraries:
- Pandas
- Matplotlib
- NumPy
- SciPy

## How to Run

To run the analysis, clone this repository and run the provided Python scripts in a Jupyter Notebook or any Python environment that supports the required dependencies.

## Resources and Acknowledgements 
I used the provided for this chalange sourses, like https://matplotlib.org/stable/gallery/statistics/boxplot_demo.html, https://mockaroo.com/, https://matplotlib.org/stable/tutorials/introductory/quick_start.html#sphx-glr-tutorials-introductory-quick-start-py etc.

Great thanks for explaining some difficult aspects and reviewing my for for the tutor Kourt Bailey.
