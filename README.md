# Exploratory Data Analysis with YouTube & Spotify Dataset 📀🎼 

<p align="center">
  <img src="https://www.tunelf.com/wp-content/uploads/2020/06/add-spotify-music-to-video-1.jpg" alt="Spotify YouTube Data">
</p>

## Project Overview 📚

This project explores a dataset that combines **Spotify** and **YouTube** data, providing insights into song attributes, artist info, and listener engagement across both platforms. Through this analysis, we aim to identify patterns in music popularity and audience preferences.

---

## Dataset Highlights ✨

The dataset includes various attributes related to music tracks, such as:

- **Track & Artist**: The name of the song and the artist performing it.
- **Album Type**: Specifies whether the song is part of an album, a standalone single, or a compilation.
- **Danceability & Energy**: Indicators of how suitable the track is for dancing and the overall energy or intensity of the song.
- **Valence & Tempo**: Reflects the mood of the song, with valence showing positivity or negativity, and tempo providing the pace of the rhythm.
- **Key**: The musical key of the track, represented as integers mapped to pitches.
- **Loudness**: The average loudness of the track in decibels (dB), useful for comparing volume levels between tracks.
- **Speechiness**: A measure of the presence of spoken words within the track, with values closer to 1.0 indicating more speech-like content.
- **Acousticness**: A confidence score that indicates the likelihood of the track being acoustic, with higher values suggesting more acoustic qualities.
- **Instrumentalness**: The likelihood that the track is instrumental, with higher values indicating fewer vocals.
- **Liveness**: Detects the presence of audience sounds, with higher values suggesting the track was recorded live.
- **Valence**: Describes whether the track has a positive (happy, cheerful) or negative (sad, angry) emotional tone.
- **Tempo**: The speed of the track, measured in beats per minute (BPM).
- **Duration**: The length of the track, expressed in milliseconds.
- **Streams & Views**: The number of plays the track has received on Spotify and YouTube.
- **Engagement Metrics**: Interaction data from YouTube, including likes, comments, and other forms of engagement.


---

## Analysis Process 🧮

Our analysis employs a structured, step-by-step approach to extract meaningful insights:

### 1. Dataset Exploration 🔍
We started with library setup and data import, followed by a preliminary review to understand the dataset’s structure and identify essential attributes.

### 2. Data Cleaning 🧹
- **Removing Non-Essential Columns**: Non-essential columns were removed, and certain attributes were reformatted for clarity. 
- **Handling Missing Data**: Missing values were handled carefully to ensure data consistency.
- **Data Type Adjustments**: Binary columns like "Licensed" and "official_video" were converted to Boolean types for easier analysis.

### 3. Refining Data for Analysis 🔧
Key variables were refined and new features were created to make song duration and engagement metrics more interpretable.

### 4. Data Distribution & Correlation Analysis  📊
- **Distribution Analysis**: Continuous features were examined using histograms and box plots to visualize their distribution.
- **Correlation Analysis**: Relationships between song attributes and user engagement were observed.
- **Categorical Data Distributions**: Pie charts were used to visualize categorical data, like album type and official video status.

### 5. Research Questions 🔄
We explored relationships between various features to uncover patterns that reveal trends in user engagement and platform-specific performance.

---

## Key Insights 💡

Here are some key findings from the analysis:

- **Variation in Engagement Across Platforms**: Some artists and tracks perform distinctly better on either Spotify or YouTube, reflecting differences in audience behavior.
  
- **Musical Features and Popularity**: Energetic, high-tempo tracks with high danceability are common among top-performing songs, especially on YouTube where visually engaging music tends to resonate. On Spotify, users show a slight preference for songs with acoustic elements, reflecting the platform’s immersive listening experience.
  
- **Audience Behavior and Engagement Patterns**: Analysis indicates that user engagement varies by content type and platform features. On YouTube, visually engaging music videos tend to draw higher views and likes, reflecting a strong preference for visual storytelling. Conversely, Spotify listeners appear more engaged with audio-focused content, showing higher stream counts for tracks with unique musical elements like acoustic richness or high vocal prominence.
  
- **Genre Preferences and User Engagement**: Tracks with higher "speechiness" (e.g., lyrical and vocal-heavy songs) perform better in terms of streams, indicating that listeners on Spotify favor tracks with pronounced vocal elements, while more instrumentally driven tracks show relatively lower engagement.

---

## Conclusion 🎯

This analysis highlights key trends in music engagement across Spotify and YouTube, offering insights into how various musical features and content types may influence user interaction and performance on each platform. By examining factors such as energy, danceability, and acoustic richness, we can observe distinct audience preferences that may shape engagement levels. These findings provide a perspective on how musical elements might align with user behaviors across different streaming environments.

If you found this project insightful, please consider giving the project a ⭐! Thank you for your support and interest. 🙏

---
