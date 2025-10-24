Spotify Data Analysis & Visualization
📝 Overview

This project explores Spotify’s artist and track datasets to uncover trends in music popularity, artist influence, and genre performance.
It combines data cleaning, exploratory data analysis (EDA), and visualization techniques to reveal how different attributes such as followers, popularity, and genres correlate on Spotify.

🧩 Objectives

Understand how artist followers relate to popularity

Identify top-performing genres

Visualize Spotify data trends (popularity, followers, release year, etc.)

Learn practical data analysis using Python libraries

Dataset Description

The project uses two CSV files:

artists.csv – Contains artist details

name, followers, genres, popularity, etc.

tracks.csv – Contains track-level details

track_name, release_date, duration_ms, popularity, etc.
Project Workflow
1️⃣ Import Libraries

Load essential libraries like Pandas, NumPy, Matplotlib, and Seaborn.

2️⃣ Load Data
sp_artists = pd.read_csv('artists.csv')
sp_tracks = pd.read_csv('tracks.csv')

3️⃣ Data Cleaning

Check for missing values using isnull()

Drop null rows to ensure clean data

4️⃣ Exploratory Data Analysis (EDA)

Identify Top 10 Most Followed Artists

Analyze Followers vs. Popularity Correlation

Find Top Genres by Average Popularity

Set Release Date as Index for time-based trends

5️⃣ Data Visualization

Scatter Plot – Followers vs. Popularity

Bar Plot – Top 10 Genres by Average Popularity

Time Series Plot – Popularity over Time

🧠 Key Insights

Artists with high follower counts are generally more popular.

Certain genres (like pop, hip-hop) consistently rank higher.

Clean data drastically improves visualization and interpretation.
