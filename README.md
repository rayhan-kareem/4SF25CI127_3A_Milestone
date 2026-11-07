# Milestone 1 – CIE: Spotify Data Analysis

## Project Overview
This project analyzes the Spotify Tracks Dataset using Python. The goal is to clean and transform the data, handle missing values, generate insights, and create visualizations.

## Dataset
- **Dataset:** Spotify Tracks Dataset
- **Source:** Kaggle
- **File:** `spotify_tracks.csv`

## Tools and Libraries
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook
- Visual Studio Code

## Data Understanding
The dataset was explored using:
- `head()` to view the first rows
- `shape` to check the number of rows and columns
- `info()` to inspect data types and missing values
- `describe()` to view statistical summaries

## Data Transformation
The following transformations were performed:
- Removed the unnecessary `Unnamed: 0` column
- Checked for duplicate rows
- Created a new `duration_min` column by converting track duration from milliseconds to minutes
- Identified numerical and text columns

## Null Value Handling
- Checked missing values in all columns
- Applied mean imputation to numerical columns where applicable
- Replaced missing text values in `artists`, `album_name`, and `track_name` with `"Unknown"`
- Verified that no missing values remained

## Key Insights
- Average track popularity: **33.24**
- Average danceability: **0.57**
- Average energy: **0.64**
- Highest observed popularity score: **100**
- The **pop-film** genre had the highest average popularity among the genres analyzed, at approximately **59.28**

## Visualizations
The project includes:
1. Top 10 popular songs
2. Distribution of song danceability
3. Energy vs. danceability scatter plot
4. Top 10 genres by average popularity

## Conclusion
This project demonstrates data cleaning, transformation, missing-value handling, exploratory data analysis, insight generation, and visualization using Python. The analysis provides an overview of popularity and audio characteristics across Spotify tracks and genres.

## Repository Contents
- `Spotify_Data_Analysis.ipynb` — Jupyter Notebook containing the analysis
- `spotify_tracks.csv` — Dataset used for the analysis
- `README.md` — Project documentation
