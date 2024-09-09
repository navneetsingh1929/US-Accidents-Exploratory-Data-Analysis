# US-Accidents-Exploratory-Data-Analysis

# Aim

The aim of this project is to perform an exploratory data analysis (EDA) on the US traffic accidents dataset (2016-2023) to derive insights on accident patterns, high-risk areas, and factors influencing accident severity. The dataset contains approximately 7.7 million records and was sourced from Kaggle.

# Objective
1. Data Preparation and Cleaning: Load the dataset into a Jupyter Notebook using Pandas, clean the data, and handle missing or incorrect values.
2. Exploratory Analysis: Identify trends in the data, such as the most accident-prone cities, impact of weather conditions, and traffic patterns.
3. Visualization: Create visualizations such as bar charts and heatmaps to effectively communicate the findings.
4. Insight Generation: Draw actionable insights on factors contributing to accidents such as time, weather, location, and severity.

# Project Learnings
1. Data Cleaning: The project started by loading the US accidents dataset and examining its structure, including reviewing the columns and fixing missing or erroneous values.
2. Data Transformation: Several columns required transformations to make the data suitable for analysis, such as converting date-time formats and categorizing accident severity.
3. Handling Missing Data: Missing data was either filled or removed depending on the analysis needs to ensure accuracy and consistency in insights.
4. Pandas and DataFrames: Extensive use of Pandas for data manipulation, including filtering data, grouping, and calculating key statistics.

# Analysis
1. Data Overview:
   a) The dataset includes over 7.7 million records with detailed information on traffic accidents in the US from 2016 to 2023.
   b) Key columns in the dataset include accident severity, weather conditions, temperature, city, state, and time of the accident.

2. Top Cities with Most Accidents:
   a) A column chart was created to visualize the cities with the highest number of accidents. The cities with the most frequent accidents include major metropolitan areas, indicating higher risk in densely populated regions.

3. Time of Accidents:
   a) Peak Hours: The analysis shows that accidents are most common during morning and evening rush hours, indicating the impact of high traffic volume.
   b) Accidents by Day: A weekly pattern is observed, with higher accident frequencies on Fridays and Mondays.

4. Impact of Weather Conditions:
   a) A heatmap was used to visualize how weather conditions such as rain, fog, and snow correlate with accident frequency.
   b) Temperature and Accidents: The relationship between temperature and accidents was examined, revealing a slight increase in accident rates in colder weather, particularly in snowy conditions.

5. Severity of Accidents:
   a) Accident severity was classified into several categories (from minor to fatal). The analysis highlighted which factors (e.g., road type, lighting conditions) contribute to more severe accidents.
   b) High Severity Factors: Poor weather conditions and nighttime driving were among the factors contributing to higher accident severity.

6. Geographical Patterns:
   a) Maps and scatter plots were used to visualize accident distribution across different states, revealing that certain states like California, Texas, and Florida have a higher concentration of accidents due to larger populations and urbanization.

7. Accidents and Road Type:
   a) A breakdown of accidents based on road type (highway, city road, etc.) was conducted to understand how road structure impacts accident frequency.

# Visualizations
Several visualizations were created using Matplotlib and Seaborn:

1. Column Charts: Displayed accident frequency by city and time.
2. Heatmaps: Illustrated the correlation between weather conditions and accident rates.
3. Line Charts: Showed accident trends over time.
4. Geographical Maps: Mapped accident concentration across different US states.

# Conclusion
This exploratory data analysis revealed important trends in US traffic accidents over a period of 7 years. Key insights include:
1. Accidents are more frequent in major metropolitan cities and during rush hours.
2. Adverse weather conditions, particularly snow and rain, significantly contribute to the likelihood and severity of accidents.
3. States like California and Texas face the highest accident frequencies, while severity increases with poor visibility and nighttime driving.

These findings could help transportation authorities improve road safety measures, such as better traffic management during peak hours, awareness campaigns in high-risk areas, and implementing safety protocols during adverse weather conditions.
