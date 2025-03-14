# DSA210-TermProject -> Chicago Crime Rate Analysis
## Objective
This project aims to determine the factors influencing crime rates in Chicago in recent years and the extent of their impact. By examining crime data alongside weather conditions, location, local population, crime type (e.g., murder, theft, violence), incident date (time, day, month, year), and more, the study will analyze under which conditions crime rates increase and which crime types are most affected.

## Motivation
Last summer, I lived in Chicago, USA, for three months as part of the Work and Travel program. While I enjoyed the city, many locals and visitors mentioned high crime rates, especially during the summer months. This prompted me to investigate whether higher temperatures or other factors such as location and population density could be driving these elevated crime rates. Additionally, as I consider pursuing a master's degree in the United States, understanding Chicago's crime dynamics could be valuable for my future decisions on where to live and study.

## Data Collection
### Data Sources:
#### => Detailed crime statistics from the Chicago Data Portal
#### => Chicago crime datasets available on Kaggle
#### => NOAA (National Oceanic and Atmospheric Administration) - Climate Data Online

## Data to be Collected:

#### => Weather Condition: Information on weather conditions at the time of the incident
#### => Population: Population data for the area where the incident occurred
#### => Case Number: Unique identifier for each crime case
#### => Date: Date and time details (hour, day, month, year) of the incident
#### => Block: Address or block where the crime took place
#### => IUCR: Crime classification code
#### => Primary Type: The primary category of the crime (e.g., murder, theft, etc.)
#### => Description: A brief description of the crime incident
#### => Location Description: A description of the crime location
#### => Arrest: Information on whether an arrest was made
#### => Domestic: Whether the incident was domestic-related
#### => Location Population: Total population of the area where the crime occurred
## Tools & Technologies
#### Python: For data analysis and processing
#### Pandas: To organize, clean, and analyze the dataset
#### Matplotlib & Seaborn: For creating charts and visualizations
#### BeautifulSoup/Selenium: For web scraping additional data if necessary
## Data Analysis Approach
### 1.Data Collection:
Retrieve crime data from the Chicago Data Portal and Kaggle.

### 2.Data Cleaning:
Remove missing or incorrect values and structure the data for analysis.

### 3.Data Exploration:

Visualize the relationship between crime rates and factors such as weather conditions, population density, and location characteristics.
Examine how different crime types are distributed across various times and areas.
### 4.Hypothesis Testing:

#### => Identify which factors (e.g., temperature, population density, location) most significantly influence crime rates.
#### => Analyze the impact of weather changes on specific types of crimes.
#### => Compare actual crime rates with expected averages to determine statistically significant deviations.
#### => Results & Conclusions:
#### => Summarize key findings to highlight the main factors driving Chicago’s crime rates and discuss their implications.

## Example Analysis & Expected Findings
For example, the analysis might reveal that during hot summer days, certain types of crimes (e.g., theft or violence) tend to increase. Another expected finding might be that densely populated areas experience a higher frequency of specific crime types. These insights will help to understand the multifaceted dynamics between environmental and social factors and crime rates.

## Possible Future Improvements
#### Expanding Data Sources:
=> Integrate data from additional websites to improve result accuracy.
#### Machine Learning Applications:
=> Develop predictive models to estimate crime rates based on key factors.
#### Additional Details:
=> Incorporate further details such as demographic data, socioeconomic factors, and localized area information.
#### Time Series Analysis:
=>Perform long-term trend analysis to study seasonal or yearly variations in crime rates.
