# dsa210-project
# Weather and Music Preferences: How Weather Affects My Playlist

## Project Overview
This project explores the relationship between weather conditions and the type of music I listen to. The main hypothesis is that weather influences my mood, which in turn affects my music preferences. Specifically:
- **Rainy and cloudy weather:** I tend to listen to slower, more melancholic songs.
- **Sunny and warm weather:** I prefer upbeat and energetic tracks.

## Dataset
### Data Sources
1. **Weather Data:** Historical weather information for my location, including temperature, precipitation, and cloudiness. Data will be sourced from [OpenWeather API](https://openweathermap.org/) , [Weather Underground](https://www.wunderground.com) or a similar service.
2. **Music Data:** My personal music listening history from a streaming platform (e.g., Spotify, Apple Music). This data includes:
   - Track names
   - Genres
   - Tempo (BPM)
   - Listening timestamps

### Data Collection
- **Weather Data:** API calls will be made to gather daily weather information according to my location for the dates in my music listening history.
- **Music Data:** I will export my streaming history using the platform's data download feature.

## Analysis Plan
1. **Exploratory Data Analysis (EDA):**
   - Analyze weather patterns over time.
   - Explore trends in my music listening data (e.g., tempo, genre).
2. **Visualization:**
   - Correlation heatmaps between weather variables and music features.
   - Line plots showing changes in tempo or genre preference over different weather conditions.
3. **Machine Learning:**
   - Build a classification model to predict the type of music I might prefer based on weather conditions.
   - Techniques: Decision Trees, Logistic Regression, or Random Forests.

## Project Motivation
I have always felt that my music preferences are influenced by the weather, but I have never tested this hypothesis systematically. This project will allow me to explore this connection and better understand my habits.

## Limitations and Future Work
- **Limitations:**
  - Small dataset limited to my personal listening history.
  - Weather data might not perfectly align with my exact listening moments.
- **Future Work:**
  - Expand analysis to include more listeners for a broader understanding.
  - Incorporate more advanced models or sentiment analysis on song lyrics.
