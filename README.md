# PRODIGY_DS_05

# Traffic Accident Data Analysis

## Overview

This project aims to analyze traffic accident data to identify patterns related to road conditions, weather, and time of day. The analysis involves data cleaning, exploratory data analysis (EDA), and visualization to derive meaningful insights into accident occurrences.

## Dataset

The dataset used for this analysis is `US_Accidents_March23.csv`, which contains a comprehensive record of traffic accidents across the United States. It includes various features such as:

- **ID**: Unique identifier for each accident
- **Severity**: Severity level of the accident (1 to 4)
- **Start_Time**: Date and time when the accident occurred
- **Location**: Latitude and longitude of the accident's starting point
- **Weather Conditions**: Conditions at the time of the accident (e.g., Fair, Rain)
- **City, State**: Location details
- **Various Environmental Factors**: Temperature, humidity, visibility, etc.

## Libraries Used

The following libraries were utilized in this analysis:

- `numpy`: For numerical operations
- `pandas`: For data manipulation and analysis
- `matplotlib`: For data visualization
- `seaborn`: For statistical data visualization

## Key Findings

1. **City-wise Accident Distribution**:
   - Miami has the highest number of accidents, likely due to its high population density and traffic volume.
   - Star Junction and Stromsburg have the fewest accidents, possibly due to their smaller size.

2. **State-wise Accident Distribution**:
   - California reports the highest number of accident cases, consistent with its large population and road network.
   - South Dakota has the least number of accidents, likely due to lower population density.

3. **Yearly Accident Rates**:
   - 2021 recorded the highest accident rates, suggesting a potential increase in traffic or changes in reporting.

4. **Accident Severity**:
   - Most accidents were categorized at severity level 2, indicating they were not extremely severe.

5. **Weather Conditions**:
   - Fair weather conditions were prevalent during most accidents, suggesting that driver behavior or traffic congestion may be more significant factors than adverse weather.

6. **Time of Day**:
   - Most accidents occurred in the morning, likely due to rush hour traffic.

## Data Cleaning Steps

- Dropped columns with a high number of missing values.
- Filled missing values for categorical variables with the mode.
- Checked and confirmed there are no duplicate entries.

## Visualization

Various visualizations were created to represent the data effectively, including:

- Bar plots for the top and bottom cities and states with the most accidents.
- A pie chart representing accident severity distribution.
- Histograms and scatter plots to analyze accidents by time of day and weather conditions.

## Conclusion

This analysis provides valuable insights into traffic patterns and accident hotspots, which can inform policy decisions, urban planning, and safety measures to reduce the incidence and severity of accidents.
