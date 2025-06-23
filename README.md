# Data Analysis and Visualization Project

This project analyzes two datasets related to historical financial data, a fear and greed index, and an equality table. The code performs data loading, exploration, cleaning, analysis, and visualization to uncover insights and relationships within the data.

## Project Structure

The project is organized into the following sections within the notebook:

1.  **Data Loading:** This section loads the three datasets into pandas DataFrames.
2.  **Data Exploration:** This section explores the loaded datasets to understand their structure, summary statistics, data types, missing values, and initial anomalies.
3.  **Data Cleaning:** This section cleans the datasets by handling missing values, converting data types, and addressing potential issues.
4.  **Data Analysis:** This section analyzes the relationships between variables in the cleaned datasets, including correlation analysis and time series analysis.
5.  **Data Visualization:** This section creates various visualizations to illustrate key findings from the data analysis.

## Datasets

The project uses the following datasets:

*   `historical_data.csv`: Contains historical financial data.
*   `fear_greed_index.csv`: Contains data for a fear and greed index.
*   `Task 5 Equality Table.xlsx`: Contains data related to equality scores.

## Dependencies

The project requires the following libraries:

*   `pandas`: For data manipulation and analysis.
*   `matplotlib`: For creating visualizations.
*   `seaborn`: For creating enhanced visualizations.
*   `IPython`: (Already available in Colab) Used for notebook functionalities.

These libraries are commonly available in a standard Python environment, especially in Google Colab.

## Usage

1.  Ensure you have the required datasets (`historical_data.csv`, `fear_greed_index.csv`, `Task 5 Equality Table.xlsx`) in the same directory as the notebook or provide the correct paths.
2.  Run the notebook cells sequentially.

The notebook will output information during the exploration and cleaning phases and display the generated visualizations at the end.

## Analysis Highlights

The analysis and visualizations aim to reveal insights such as:

*   Relationships between different financial metrics in the historical data through a correlation heatmap.
*   Trends and patterns in the historical financial data and the fear and greed index over time through time series plots.
*   The distribution of equality scores across different factories and job roles through box plots and violin plots.
