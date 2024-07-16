
# Netflix Data Analysis Project


## Overview

This project analyzes Netflix shows and movies data using SQL and visualizes the findings using Tableau.


## Data Sources

Data was sourced from Kaggle Netflix dataset.


## Tableau Dashboard

The Tableau dashboard provides visual insights into the Netflix dataset, highlighting top IMDB-rated shows and movies, production countries, and more.

![Netflix Dashboard](https://github.com/MohammedNasar07/Netflix-Data-Analysis/blob/main/Netflix%20Dashboard%20(Tableau).png?raw=true)


## SQL Analysis

The SQL analysis includes queries to identify top-rated shows, analyze genres, and more.


-- Analysis of top-rated Netflix shows

SELECT * FROM shows WHERE rating = 'top-rated';


-- Analysis of Netflix content by genre

SELECT genre, COUNT(*) FROM shows GROUP BY genre;


