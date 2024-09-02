# Household-Level Day-Ahead Peak Electricity Demand Forecast- Additional Materials

This repository contains additional materials for the extended research project submitted to the University of Manchester for the degree of MSc Data Science in the Faculty of Humanities.

Student ID: 11473492

## Important note

The Jupyter Notebooks in the `code` folder contains code needed to reproduce the work, along with the output of the code. They are designed for reproducibility and verifiability of results (e.g., using print statements and tables),
and do not involve extensive EDA or code that is not needed for reproducing the work. 

For the full code used for this study, please refer to the `full-code` folder, which contains 
the full version of each script/Notebook.

## Data Sources

- **Low Carbon London Project dataset**: Available at https://beta.ukdataservice.ac.uk/datacatalogue/studies/study?id=7857. Note: This data is safeguarded.
- **Weather data**: Provided in the repository as CSV files since it is publicly available to anyone (queried using the querying tool on Visual Crossing- https://www.visualcrossing.com/weather/weather-data-services).

## Jupyter Notebooks

To reproduce the work, please go through the notebooks in the `code` folder in numerical order:

1. Data Merging
2. Initial Survey Data Cleaning
3. Feature Extraction (Attitudes Survey)
4. Feature Extraction (Appliance Survey)
5. Exploratory Data Analysis and Imputation
6. Additional Feature Engineering and Selection
7. Model Development (A, C) 

Note: 7B is not included as it is not needed to reproduce the work. However, it is available in the `full-code` folder.

## Additional Visualizations

The `additional-visualizations` folder contains:
- Pearson and Spearman's rank correlation matrices
- Mutual information of categorical variables with the target variable

For more visualizations, refer to notebooks 5 and 6.
