# Spotify Data Analysis (2015-2025)

This project contains an Exploratory Data Analysis (EDA) of a dataset consisting of 85,000 Spotify tracks from the years 2015-2025. The goal is to investigate music trends, correlations between audio features, and the characteristics of popular tracks.

## About the Dataset

File: `spotify_2015_2025_85k.csv`

The dataset includes metadata and audio features of the tracks. Key columns include:
* **Metadata:** `track_name`, `artist_name`, `genre`, `release_date`.
* **Popularity:** `popularity`, `stream_count`.
* **Audio Features:** `danceability`, `energy`, `loudness`, `tempo`.
* **Music Theory:**
    * `key`: Pitch class (0 = C, 1 = C#, ..., 11 = B).
    * `mode`: Scale mode (1 = Major, 0 = Minor).

## Analysis Performed (EDA)

The following steps were executed within the project using Python:

1.  **Data Cleaning:**
    * Conversion of `release_date` to datetime format.
    * Handling missing values.
2.  **Univariate Analysis:**
    * Distribution of track popularity (Histogram).
    * Distribution of energy across top genres (Boxplot).
3.  **Correlations:**
    * Investigation of relationships between numerical features (Heatmap), e.g., `loudness` vs. `energy`.
4.  **Tonal Analysis:**
    * Analysis of the relationship between loudness and energy, split by mode (Major/Minor).

## Technologies

The project uses:
* **Python 3.x**
* **Pandas** (Data Processing)
* **Matplotlib & Seaborn** (Visualization)

## How to Run

1. Clone the repository:
   ```bash
   git clone [https://github.com/marta23-10/spotify-analysis.git](https://github.com/marta23-10/spotify-analysis.git)


pip install pandas matplotlib seaborn
Run the analysis script (e.g., in Jupyter Notebook).
