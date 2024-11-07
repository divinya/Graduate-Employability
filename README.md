# Group Project Data Dynamous

## Project Overview
This project is focused on analyzing graduate employability data to derive insights about how various factors such as gender, academic performance, work experience, and other attributes influence employment outcomes. The data was cleaned, processed, and analyzed using various Python libraries such as Pandas, NumPy, and Matplotlib.

## Table of Contents
- [Project Description](#project-description)
- [Data Description](#data-description)
- [Data Cleaning and Preprocessing](#data-cleaning-and-preprocessing)
- [Analysis and Visualizations](#analysis-and-visualizations)


## Project Description
This project provides insights into how factors like gender, academic performance, and work experience influence the employability status of graduates. We used a dataset of graduates and employed various data processing and visualization techniques to identify patterns and trends.

### Features
- Data cleaning and preprocessing steps to handle missing values and outliers.
- Data analysis using statistical methods and correlation analysis.
- Visualizations like histograms, boxplots, and stacked bar charts to explore the data.
- Key insights and patterns in employability based on different factors.

## Data Description
The dataset used in this project contains several columns, such as:
- `sex`: Gender of the graduate.
- `status`: Employment status (e.g., 'Placed', 'Not Placed').
- `degree_pct`: Percentage scored in the degree program.
- `work_xp`: Work experience before graduation.
- `salary`: Annual salary if employed (some values may be missing).
- Other variables related to the graduates' background.

The data is stored in a CSV file, which can be found in the project's directory.

## Data Cleaning and Preprocessing
We performed several data cleaning steps:
1. **Handling Missing Values**: Missing values in the `salary` column were replaced with `0`.
2. **Outlier Removal**: The `salary` column was cleaned by removing outliers based on certain criteria.
3. **Categorization**: Categorical variables like `sex`, `status`, and `work_xp` were explored and encoded for analysis.

## Analysis and Visualizations
We generated several types of plots to visualize the data:
- **Histograms**: To visualize the distribution of numerical features.
- **Boxplots**: To check for outliers in numerical features.
- **Stacked Bar Charts**: To visualize the distribution of employment status across different categories like gender, work experience, and academic performance.

