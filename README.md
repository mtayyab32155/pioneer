# Netflix Movies Data Analysis Project

## Overview
This project performs an exploratory data analysis (EDA) on a dataset containing
9000+ movies. The objective is to analyze movie genres, popularity, voting patterns,
and release trends using Python data analysis and visualization techniques.

## Objectives
The analysis focuses on answering the following questions:
- Which genre has the highest number of votes?
- From which genre are most movies released?
- Which genre has the highest popularity?
- Which genre has the lowest popularity?
- In which year were the most movies released?

## Dataset
- Source: Movie database (`mymoviedb.csv`)
- Total movies: 9,827
- Key features:
  - Release Date
  - Title
  - Genre
  - Popularity
  - Vote Count
  - Vote Average

## Tools & Libraries
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn

## Data Cleaning & Preparation
- Converted `Release_Date` to year format
- Removed irrelevant columns (`Overview`, `Original_Language`, `Poster_Url`)
- Checked and removed duplicates
- Categorized `Vote_Average` into:
  - verylow
  - low
  - medium
  - high
- Split multi-genre movies so each genre appears in a separate row

## Exploratory Data Analysis
The following analyses were performed:
- Distribution of movies by genre
- Vote average categorization analysis
- Identification of movies with highest and lowest popularity
- Year-wise distribution of movie releases
- Genre-wise popularity trends

## Key Insights
- **Genre with highest votes:** Drama
- **Genre with most movies released:** Drama
- **Movie with highest popularity:** *Spider-Man: No Way Home*
- **Movies with lowest popularity:** *The United States vs. Billie Holiday* and *Threads*
- **Year with most movie releases:** 2020

## Visualizations
- Genre distribution using count plots
- Vote category distribution
- Release year distribution histogram
- Popularity comparisons

## Project Structure
- `Netflix_movies_list_data_analysis.ipynb` – Main analysis notebook
- `mymoviedb.csv` – Dataset
- `README.md` – Project documentation

## Conclusion
This project demonstrates practical data analysis skills, including data cleaning,
feature engineering, exploratory data analysis, and data visualization. The insights
derived highlight clear trends in movie genres, popularity, and release patterns.

## Author
Matyab
