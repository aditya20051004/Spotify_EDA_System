# 🎵 Spotify Music Intelligence & Analytics System

A complete Data Science and Business Analytics project built on Spotify audio-feature datasets to analyze music trends, genre behavior, popularity patterns, and hidden relationships between musical attributes.

This project performs:
- Data Cleaning
- Exploratory Data Analysis (EDA)
- Business Intelligence Analysis
- Correlation Analysis
- Audio Feature Analytics
- Mood & Genre Insights
- Visualization & Statistical Interpretation

---

# 📌 Project Objectives

The main objectives of this project are:

- Analyze Spotify music trends using audio features
- Identify factors affecting song popularity
- Understand genre-level behavior and market saturation
- Explore relationships between musical attributes
- Perform business-oriented analytics on streaming music data
- Generate insights useful for recommendation systems and music platforms

---

# 📂 Dataset Features

The dataset contains several Spotify audio attributes including:

| Feature | Description |
|---|---|
| popularity | Popularity score of track |
| danceability | Dance suitability of song |
| energy | Intensity and activity level |
| valence | Positivity / happiness of song |
| acousticness | Acoustic confidence score |
| loudness | Overall loudness in dB |
| tempo | Beats Per Minute (BPM) |
| speechiness | Spoken-word presence |
| explicit | Explicit lyrics indicator |
| track_genre | Genre category |

---

# 🧹 Data Cleaning Performed

The following preprocessing steps were applied:

- Removed duplicate records
- Removed unnecessary columns
- Handled missing values
- Converted duration from milliseconds to minutes
- Validated numerical features
- Prepared data for statistical analysis and visualization

---

# 📊 Exploratory Data Analysis (EDA)

The project includes:

## 🔥 Popularity Analysis
- Most popular songs
- Most popular artists
- Genre popularity comparison
- Popularity distribution

## 🎼 Audio Feature Analysis
- Danceability vs Energy
- Loudness correlation
- Tempo analysis
- Mood-based song distributions

## 📈 Business Analytics
- Genre saturation analysis
- Explicit vs non-explicit song performance
- Artist consistency analysis
- Audio feature impact on popularity

## 🎨 Visualizations
- Histograms
- Bar Charts
- Pie Charts
- Correlation Heatmaps
- Scatter Plots
- Genre Comparison Graphs

---

# 📉 Key Insights

Some important insights discovered:

- Certain genres dominate song volume but not popularity
- Danceability and energy show strong relationships
- Explicit songs tend to have different popularity distributions
- Audio characteristics can separate songs into mood-based groups
- Some genres are oversaturated but commercially weaker

---

# 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Google Colab

---

# 📁 Project Structure

```bash
spotify-music-intelligence/
│
├── data/
│   └── dataset.csv
│
├── notebooks/
│   └── spotify_analysis.ipynb
│
├── images/
│   ├── heatmap.png
│   ├── popularity_distribution.png
│   ├── genre_analysis.png
│
├── README.md
