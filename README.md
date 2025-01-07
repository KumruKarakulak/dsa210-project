# dsa210-project
# The Relationship Between Weather and Step Count: How Weather Influences Physical Activity

## Project Overview
This project explores the connection between weather conditions and daily step count. The hypothesis is that weather significantly influences physical activity levels. Specifically:
- **Rainy and cloudy weather:** I tend to decrease my step counts due to discomfort and reduced motivation for outdoor activities.
- **Sunny and warm weather:** I prefer to take more steps due to pleasant outdoor conditions.

## Dataset
### Data Sources
1. **Weather Data:** Historical weather information for my location, including temperature, precipitation, and cloudiness. Data will be sourced from [OpenWeather API](https://openweathermap.org/) , [Weather Underground](https://www.wunderground.com) or a similar service.
2. **Step Count Data:** My personal daily step count history from Apple Health. This data includes:
   - Daily step counts
   - Date and time logs

### Data Collection
- **Weather Data:** API calls will be made to gather daily weather information according to my location for the dates in my music listening history.
- **Step Count Data:** I will export my step count data from my device or app, ensuring it aligns with the weather dataset.

## Analysis Plan
1. **Exploratory Data Analysis (EDA):**
   - Summarize and visualize trends in weather data (e.g., average temperature, frequency of rainy days).
   - Explore patterns in step count data, including overall trends and daily fluctuations.
2. **Visualization:**
   - Correlation heatmaps showing relationships between weather variables and step counts.
   - Line plots illustrating variations in step counts across different weather conditions.
3. **Machine Learning:**
   - Develop a regression model to predict daily step counts based on weather data.
   - Linear Regression, Random Forests, or Gradient Boosting.


## Project Motivation
I have always felt that my music preferences are influenced by the weather, but I have never tested this hypothesis systematically. This project will allow me to explore this connection and better understand my habits.

## Limitations and Future Work
- **Limitations:**
  - Small dataset limited to my personal step count data.
  - Weather data might not perfectly align with my specific times of activity recorded in step count logs.
- **Future Work:**
  - Expand the analysis to include data from multiple individuals for broader insights.
  - Incorporate additional contextual variables, such as mood, time spent outdoors, or health-related factors.

