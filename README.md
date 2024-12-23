# 911-Calls-Analysis
This project showcases an exploratory data analysis of the 911 calls dataset hosted on Kaggle. It demonstrates extraction of useful features from different variables.

## Dataset Information

It analyzes the 911 call dataset from [Kaggle](https://www.kaggle.com/datasets/mchirico/montcoalert). The dataset provides a comprehensive overview of emergency calls in Montgomery County, PA. 

The dataset contains the following fields:

- **lat**: Latitude (String)
- **lng**: Longitude (String)
- **desc**: Description of the Emergency Call (String)
- **zip**: Zipcode (String)
- **title**: Title (String)
- **timeStamp**: Timestamp of the call in the format YYYY-MM-DD HH:MM:SS (String)
- **twp**: Township (String)
- **addr**: Address (String)
- **e**: Dummy variable (always 1) (String)

The dataset is clean, well-structured, and suitable for exploratory data analysis and visualization.

## Project Objectives

The primary goals of this project are:

### Exploratory Data Analysis
- Examine the distribution and frequency of 911 calls.
- Analyze the types of emergencies and the most affected locations.
- Investigate temporal trends in emergency calls, including analysis by hour, day, and month.
### Data Visualization
- Create insightful visualizations for geographic and temporal trends.
- Plot the most common emergency types and their frequencies.
### Statistical Insights
- Determine which townships and zip codes have the highest call volumes.
- Explore correlations between time of day and type of emergencies.

## Project Workflow

### Data Cleaning
- Remove duplicates and handle missing values.
- Parse the timestamp field to extract useful information (e.g., hour, day of the week, and month).
### Data Analysis
- Analyze the frequency and distribution of calls by different categories such as township, title, and zip code.
- Identify trends in the number of calls over time.
### Visualization
- Utilize libraries such as Matplotlib and Seaborn for generating plots.
- Plot geographical heatmaps of call locations.
### Insights Extraction
- Generate summary statistics and insights from the visualizations and analysis.

## Results

- The project identifies the most common types of emergencies and the areas with the highest frequency of 911 calls.
- Temporal analysis reveals peak call times and seasonal trends in emergencies.
- Visualizations provide clear insights into the data, enhancing understanding of the emergency response patterns in the county.
- 
This analysis of 911 calls provides actionable insights into emergency patterns and response demands in Montgomery County. The results can assist local authorities and policymakers in improving emergency response strategies and resource allocation.

## Files

- **`911-Calls-Analysis.ipynb`**: Jupyter Notebook containing the code for analysis and visualizations.
- **`911.csv`**: The dataset used for the analysis (source: Kaggle).
