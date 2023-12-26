# IMDb Anime Data Web Scraping and Analysis

## Overview

This project focuses on web scraping IMDb's website to gather data on the top 1000 "Anime" movies. The collected data includes movie details such as name, certificate rating, duration, genre, IMDb rating, metascore, director, stars, votes, gross earnings, and a brief plot summary. The goal is to create a dataset for further analysis, recommendations, and insights.

## Project Structure

- **Web Scraping Notebook:** `web_scraping_imdb_anime.ipynb`
  - Initializes the project, installs required libraries, and imports necessary modules.
  - Defines a web scraping function to extract data from IMDb.
  - Scrapes IMDb data for multiple pages and creates a DataFrame.
  - Saves the DataFrame to a CSV file.

- **Exploratory Data Analysis (EDA):** `eda_imdb_anime.ipynb` (Optional)
  - Explores various aspects of the movie data, including summary statistics, data visualization, genre analysis, director and actor insights, movie duration, user votes, gross earnings, and top-rated movies.

## Installation

1. Install required libraries:

   ```bash
   pip install beautifulsoup4 requests pandas numpy matplotlib seaborn
