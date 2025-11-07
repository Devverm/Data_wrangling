# Amazon prime video Analysis

## 📊 Project Overview

This project performs comprehensive exploratory data analysis (EDA) on a dataset containing detailed metadata about films and television shows, as well as information about the people involved in their creation. The analysis uncovers meaningful insights into trends, audience preferences, and factors influencing ratings and popularity.

## 🎯 Problem Statement

How do various production, content, and personnel factors affect the popularity and ratings of movies and television shows across different periods and regions?

## 📁 Dataset Description

### Titles Dataset

- `id`: Unique identifier for titles
- `title`: Official content name
- `type`: MOVIE or SHOW
- `description`: Summary
- `release_year`: Year of release
- `age_certification`: Age rating
- `runtime`: Duration in minutes
- `genres`: Associated genres
- `production_countries`: Production country codes
- `seasons`: Number of seasons (shows only)
- `imdb_id`, `imdb_score`, `imdb_votes`: IMDb metrics
- `tmdb_popularity`, `tmdb_score`: TMDB metrics

### Credits Dataset

- `person_id`: Unique identifier for people
- `id`: Title reference
- `name`: Person's name
- `character`: Role or character
- `role`: ACTOR, DIRECTOR, etc.

## 🛠️ Technologies Used

