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
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns



Always use a space after the hash (#) and before your heading text.

## 🔍 Key Analysis Areas

### Data Cleaning & Preprocessing

- Removing duplicates and handling missing values
- Feature engineering for improved analysis

### Univariate, Bivariate, and Multivariate Analyses

- Distribution of genres and runtimes
- Correlation of IMDb and TMDB scores
- Analysis of ratings by country and genre

## 📊 Key Insights

- Movies comprise ~86% of titles; shows, 14%
- IMDb and TMDB scores show a strong positive correlation (0.58)
- Most movies run between 80 and 100 minutes
- US, India, and UK produce the majority of titles
- Drama and Comedy are the most common genres

## 🚀 Installation & Usage
Clone the repository
git clone <your-repository-url>
cd film-tv-analysis

Install requirements
pip install numpy pandas matplotlib seaborn

Run the notebook
jupyter notebook Copy-of-Sample-EDA-Submission-Template.ipynb




## 📈 Sample Visualizations

- Distribution plots for ratings and runtimes
- Bar charts and heatmaps for genres and correlations
- Time series of ratings over years

## 💼 Business Applications

- Improve streaming recommendation systems
- Guide production and casting decisions
- Inform marketing and release strategies

## 🔮 Future Enhancements

- Predictive modeling for ratings
- Sentiment analysis of descriptions
- Collaboration network analysis among cast and crew

## 🤝 Contributing

1. Fork the repo
2. Create a feature branch
3. Commit and push changes
4. Open a Pull Request

## 📄 License

This project is intended for educational and research purposes.


