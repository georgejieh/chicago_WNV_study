# West Nile Virus Prediction in Chicago

## Project Overview
This project focuses on analyzing and predicting the prevalence of the West Nile Virus (WNV) in Chicago based on historical mosquito trapping data. The aim is to gain insights into factors influencing WNV spread and to develop predictive models to assist in public health planning and mosquito control efforts.

## Data Source
The dataset used in this project is provided by the City of Chicago, tracking mosquito data from 2008 to 2019. It includes information about mosquito counts, types of traps used, presence of West Nile Virus, and geographical coordinates of traps.

## Objectives
- Conduct a thorough Exploratory Data Analysis (EDA) to understand the dataset and identify key patterns.
- Develop predictive models to forecast the occurrence of West Nile Virus based on environmental and mosquito trap data (in progress).

## Exploratory Data Analysis (EDA)
### Data Cleaning and Preprocessing
- Converted the 'Date' column to a datetime format.
- Handled missing values in 'Latitude' and 'Longitude' columns, especially for observations related to specific locations like O'Hare Airport.

### Key Findings
- **Temporal Trends**: Observed higher mosquito activity in the latter half of the year, with August being the peak month.
- **Species Analysis**: Identified Culex Pipiens and Culex Restuans as species more susceptible to WNV.
- **Trap Efficiency**: Gravid traps were the most commonly used, but Sentinel and CDC traps showed higher efficacy in capturing mosquitoes.
- **Temperature Correlation**: Found a general correlation between warmer temperatures and increased WNV positive cases, though with yearly variations.

### Visualizations
- Histograms, box plots, and time series plots to illustrate mosquito counts, trap efficiencies, and temporal trends.
- Dual-axis plots to show the relationship between average temperature and WNV positive cases.

## Prediction Models (In Progress)

