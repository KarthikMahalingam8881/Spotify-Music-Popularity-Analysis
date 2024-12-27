# Spotify-Music-Popularity-Analysis

This repository contains an in-depth analysis of Spotify music data to uncover trends, identify key features contributing to track popularity, and predict future hit songs. The project leverages data analysis, machine learning, and visualization techniques to provide insights into the dynamics of music consumption.

## Project Highlights

1. **Data Exploration**: 
   - Comprehensive overview of Spotify data, including track metadata, audio features, and popularity metrics.
   - Visualized patterns and relationships, such as playlist genre vs. track popularity and key trends over time.

2. **Cluster Analysis**:
   - Used K-Means clustering to group songs based on audio features and popularity.
   - Generated heatmaps to summarize feature distributions across clusters.

3. **Feature Importance**:
   - Applied Random Forest models to identify features most influential in determining track popularity.
   - Explored attributes like danceability, valence, energy, and acousticness.

4. **Comparative Analysis**:
   - Compared distributions of audio features for more popular and less popular songs.
   - Conducted statistical tests (e.g., t-tests and chi-square tests) to validate feature significance.

5. **Emerging Artists Identification**:
   - Filtered artists producing high-quality tracks with lower popularity to identify promising talents.

6. **Trend Analysis**:
   - Tracked genre-specific feature trends over time, such as danceability and energy.
   - Studied artist-specific popularity trends (e.g., Ed Sheeran vs. Maroon 5).

7. **Predictive Modeling**:
   - Built and evaluated Random Forest models to predict future hit songs.
   - Enhanced prediction accuracy using techniques like SMOTE for data resampling.

8. **Market Analysis**:
   - Investigated market dynamics by analyzing average popularity and song count across genres.
   - Visualized genre-specific market opportunities using scatterplots.

## Tools and Techniques

- **Programming Language**: Python
- **Libraries**:
  - Data Manipulation: `pandas`, `numpy`
  - Visualization: `matplotlib`, `seaborn`
  - Machine Learning: `scikit-learn`, `imblearn`
- **Statistical Tests**: T-tests, Chi-square tests
- **Clustering and Dimensionality Reduction**: K-Means, PCA
- **Resampling**: SMOTE (Synthetic Minority Oversampling Technique)

## Dataset

The dataset used includes Spotify tracks with features such as:
- **Track Metadata**: Name, artist, album, release date.
- **Audio Features**: Danceability, energy, tempo, valence, loudness, acousticness, etc.
- **Popularity Metrics**: Track popularity score.
- **Playlist Information**: Playlist name and genre.

## Key Visualizations

- Average track popularity by playlist genre.
- Clusters of songs based on valence and energy.
- Feature distributions for more and less popular songs.
- Genre-specific feature trends over time.
- Market analysis scatterplots for genres.

## Results
- Analyzed Spotify data using feature engineering, statistical tests, and ML models (84.3% accuracy) to predict popularity 
and classify moods 
- Discovered  5 emerging artists with a 30% stream growth potential and optimized playlists for 15% higher engagement, 
delivering insights through Tableau and clustering 

## Future Work
- Incorporate additional data, such as social media metrics and streaming trends, to enhance predictions.
- Explore advanced models like Gradient Boosting or Neural Networks for better accuracy.
- Extend analysis to real-time data for trend forecasting.
  
## Contributions
Contributions are welcome! Please fork the repository, make your changes, and submit a pull request.
