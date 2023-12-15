# West Nile Virus Prediction in Chicago

## Project Overview
This project delves into the analysis and prediction of West Nile Virus (WNV) prevalence in Chicago, utilizing historical mosquito trapping data. The goal is to uncover the key factors influencing the spread of WNV and create predictive models that can aid public health planning and mosquito control initiatives.

## Data Source
The primary dataset for this study is sourced from the City of Chicago, comprising mosquito data spanning from 2008 to 2019. It encompasses diverse aspects such as mosquito counts, trap types, WNV presence, and geographical data.

## Objectives
- Conduct an in-depth Exploratory Data Analysis (EDA) to decode the dataset and highlight significant patterns.
- Develop models to predict West Nile Virus occurrences, integrating environmental data and mosquito trap information (ongoing).

## Exploratory Data Analysis (EDA)
### Data Cleaning and Preprocessing
- The 'Date' column was transformed into a datetime format for better analysis.
- Addressed missing values in 'Latitude' and 'Longitude', especially for specific locations like O'Hare Airport.

### Key Insights
- **Temporal Patterns**: Higher mosquito activity was noted in the second half of the year, peaking in August.
- **Species Analysis**: Culex Pipiens and Culex Restuans species demonstrated a higher susceptibility to WNV.
- **Trap Effectiveness**: While Gravid traps were most commonly used, Sentinel and CDC traps proved more efficient in capturing mosquitoes.
- **Temperature Influence**: A general correlation was observed between increased temperatures and WNV positive cases, albeit with annual variations.

### Visualizations
- Utilized histograms, box plots, and time series graphs to depict mosquito counts, trap effectiveness, and time-related trends.
- Employed dual-axis plots to correlate average temperatures with the frequency of WNV positive cases.

## Model Building

### Linear Regression
The linear regression model aimed at predicting mosquito numbers, yielding an MSE of 169.67 and an R-squared value of 0.07. Adjustments for multicollinearity led to slight improvements, with an MSE of 173.43 and R-squared of 0.05. The model faced challenges such as low explanatory power and multicollinearity, particularly with binary variables.

### Logistic Regression
The logistic regression model, designed to predict WNV presence, achieved an accuracy of around 81%. It was more adept at predicting the absence rather than the presence of WNV. Despite modifications and variable adjustments, the model's accuracy remained consistent, emphasizing the need for more comprehensive data for prediction.

### Model Limitations
- **Linear Regression**: Faced issues like low explanatory power and multicollinearity, underscoring the complexity of predicting mosquito numbers based solely on available variables.
- **Logistic Regression**: Although reaching an accuracy of 81%, the model's effectiveness in predicting true positives (WNV presence) was limited. The need for more diverse data, including climate and broader trap types, was evident.

### Ongoing Efforts
- Refining the models by incorporating additional relevant variables and data sources.
- Exploring advanced modeling techniques to enhance predictive accuracy.

## Conclusion
The exploratory data analysis provided valuable insights into the factors influencing mosquito populations and WNV spread in Chicago. The prediction models, while facing limitations, offered a foundational understanding of the complex relationships involved. Ongoing efforts aim to refine these models for more accurate predictions, ultimately contributing to effective public health strategies against WNV.