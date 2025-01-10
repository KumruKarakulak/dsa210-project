
# Project: Step Count and Weather Data Analysis

## Overview
This project explores the connection between weather conditions and daily step count. The hypothesis is that weather significantly influences physical activity levels. Specifically:

- **Rainy and cloudy weather**: I tend to decrease my step counts due to discomfort and reduced motivation for outdoor activities.
- **Sunny and warm weather**: I prefer to take more steps due to pleasant outdoor conditions.

## Datasets

### 1. `stepp.csv`
- **Description**: Tracks the number of steps taken each day.
- **Columns**:
  - `Date` (string): Date in the format `YYYY-MM-DD`.
  - `Step Count` (integer): Total number of steps recorded on that date.
- **Rows**: 153

**Sample Data**:
```
         Date  Step Count
0  2024-08-01        8675
1  2024-08-02       19561
2  2024-08-03        5116
3  2024-08-04        6150
4  2024-08-05        6012
```

### 2. `weatherrr.csv`
- **Description**: Provides daily weather information.
- **Columns**:
  - `Date` (string): Date in the format `YYYY-MM-DD`.
  - `Temperature` (integer): Daily temperature in Celsius.
  - `Precipitation` (integer): Amount of precipitation in millimeters.
  - `Cloudiness` (integer): Cloud coverage percentage.
- **Rows**: 153

**Sample Data**:
```
         Date  Temperature  Precipitation  Cloudiness
0  2024-08-01           35              0           28
1  2024-08-02           33              0           25
2  2024-08-03           35              0           17
3  2024-08-04           28              0           33
4  2024-08-05           33              0           12
```

## Data Sources
- **Weather Data**: Historical weather information for my location, including temperature, precipitation, and cloudiness. Data will be sourced from OpenWeather API, Weather Underground, or a similar service.
- **Step Count Data**: My personal daily step count history from Apple Health. This data includes:
  - Daily step counts
  - Date and time logs

## Data Collection
- **Weather Data**: API calls will be made to gather daily weather information according to my location for the dates in my step count history.
- **Step Count Data**: I will export my step count data from my device or app, ensuring it aligns with the weather dataset.

## Analysis Plan

### Exploratory Data Analysis (EDA)
- Summarize and visualize trends in weather data (e.g., average temperature, frequency of rainy days).
- Explore patterns in step count data, including overall trends and daily fluctuations.

### Visualization
- Correlation heatmaps showing relationships between weather variables and step counts.
- Line plots illustrating variations in step counts across different weather conditions.

### Machine Learning
- Develop a regression model to predict daily step counts based on weather data.
- Techniques: Linear Regression, Random Forests, or Gradient Boosting.

## Project Motivation
I have always felt that my music preferences are influenced by the weather, but I have never tested this hypothesis systematically. This project will allow me to explore this connection and better understand my habits.

## Limitations and Future Work

### Limitations
- Small dataset limited to my personal step count data.
- Weather data might not perfectly align with my specific times of activity recorded in step count logs.

### Future Work
- Expand the analysis to include data from multiple individuals for broader insights.
- Incorporate additional contextual variables, such as mood, time spent outdoors, or health-related factors.