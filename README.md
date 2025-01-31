# Yelp Project: Analyzing Factors Affecting Customer Satisfaction with Top Non-American Ethnic Cuisines in the US

## Overvie
This project analyzes factors affecting customer satisfaction with top non-American ethnic cuisines in the US, focusing on Chinese, Japanese, Italian, and Mexican cuisines. Using Yelp restaurant data, the objective is to explore and understand the dynamics driving customer preferences and satisfaction.

## Motivation
Understanding customer satisfaction is crucial for restaurant success. This project seeks to determine which factors influence the popularity of different ethnic cuisines and whether there are discernible patterns in customer reviews and ratings. The insights gained can provide valuable information to stakeholders in the food industry and contribute to a deeper understanding of culinary diversity in the United States.

## Data Sources
1. **Yelp Data**: Includes business information, reviews, and tips for restaurants.
2. **US Census Data**: Provides demographic information for areas where restaurants are located.

## Data Collection
- **RIAA Web Scraping**: Collected data on songs and artists from the Record Industry Association of America (RIAA).
- **SpotiPY**: Used the Spotify API to gather audio features and genres for tracks.

## Data Preparation
- Cleaned and transformed Yelp data into pandas data frames.
- Retrieved and processed US Census data for relevant demographic features.
- Merged and aggregated data to create comprehensive datasets for analysis.

## Exploratory Data Analysis (EDA)
- Detailed analysis of Yelp data to identify trends and key features influencing customer satisfaction.
- Visualization of data to understand the distribution and impact of various attributes.

## Feature Engineering
- Created new features from existing data, such as review sentiment scores using SentimentIntensityAnalyzer.
- Converted categorical variables into numerical values through one-hot encoding.
- Normalized demographic features to account for variations in population density.

## Modeling
- Developed machine learning models to predict customer satisfaction based on features:
  - **Logistic Regression**
  - **Random Forest Classifier**
  - **Naive Bayes Gaussian**
- Evaluated model performance using metrics such as ROC AUC, precision, and recall.

## Results and Discussion
- Identified key features influencing customer satisfaction, including track number, followers, loudness, duration, danceability, liveness, and acousticness.
- Analyzed the impact of different genres on award-winning songs.
- Observed trends in customer satisfaction and award distribution over time.

## Conclusion
The project provides valuable insights into the factors driving customer satisfaction with ethnic cuisines in the US. The findings highlight the importance of certain features and genres in determining the popularity of songs and cuisines.

## Future Work
- Further exploration of additional cuisines and broader geographical areas.
- Improved models and analysis techniques to enhance the understanding of customer preferences.

## Authors
- Claire Han Sun
- Bowie Liu
