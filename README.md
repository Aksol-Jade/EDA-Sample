
---

# Exploratory Data Analysis Practice

---

## Project Overview

This project performs an in-depth exploratory data analysis (EDA) on a Spotify dataset, which contains attributes of popular streamed songs. The goal is to uncover patterns, trends, and relationships between audio features and stream counts to inform potential predictive modeling or musical insights.

---

## Objectives

1. Assess the dataset's structure and quality.
2. Clean and preprocess inconsistent or missing entries.
3. Analyze distributions, central tendencies, and variability.
4. Visualize trends in track release frequency over time.
5. Evaluate correlations between audio features and streaming performance.

---

## Key Questions Explored

### 1. Dataset Structure

* How many rows and columns does the dataset have?
* What are the data types and which columns have missing values?

### 2. Descriptive Statistics

* What are the mean, median, and standard deviation of the `streams` column?
* How do `released_year` and `artist_count` distribute?
* Are there notable outliers or trends?

### 3. Track and Artist Rankings

* What are the top 5 tracks based on stream count?
* Who are the most frequently occurring artists in the dataset?

### 4. Release Patterns

* How does the number of track releases vary per year and per month?
* What trends are visible over time in terms of streaming success?

### 5. Correlation Analysis

* How do `bpm`, `danceability_%`, and `energy_%` relate to stream counts?
* Are there strong relationships between other musical features such as `valence_%` and `acousticness_%`?

---

## Methods and Tools

* **Languages**: Python
* **Libraries**: Pandas, NumPy, Matplotlib, Seaborn
* **Cleaning Techniques**:

  * Fixing mislabeled string values in numeric columns (`streams`, `in_deezer_playlists`)
  * Type conversions for accurate numerical analysis
* **Visualizations**:

  * Distribution plots
  * Correlation heatmaps
  * Line charts for release trends
  * Scatter plots for feature-stream relationships

---

## Highlights

* Discovered temporal spikes in song releases during January and May.
* Identified a consistent rise in high-streamed tracks from recent years, with 2022 having the highest aggregate stream volume.
* Observed that high `danceability_%` and `energy_%` may contribute to higher stream counts, but the effect is not strongly linear.
* Noted increasing collaborations (higher `artist_count`) in recent years among the most streamed songs.

---

## Conclusion

This EDA provides foundational insights into Spotify song characteristics that contribute to popularity. It sets the groundwork for potential predictive modeling and audio feature optimization.

---

