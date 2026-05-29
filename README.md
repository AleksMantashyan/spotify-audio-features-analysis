# Spotify Audio Features and Popularity Analysis

This project was completed as part of the Data Visualization course at the American University of Armenia. The project analyzes Spotify tracks released from 1980 to 2020 to study how audio features changed over time and whether those features are associated with track popularity.

## Project Overview

The analysis focuses on selected Spotify audio features, including energy, danceability, and loudness. The goal was to examine long-term trends in modern music and evaluate whether these features are related to track popularity.

The final cleaned dataset contained 397,220 tracks from 1980 to 2020. The project combines data cleaning, exploratory data visualization, statistical testing, and formal report writing.

## Tools Used

- R
- ggplot2
- Data visualization
- Statistical analysis
- R Markdown
- IEEE-style report writing

## Methods Used

- Data cleaning and preprocessing
- Yearly trend visualization
- Decade-level feature comparison
- Distribution comparison using boxplots
- Pearson correlation analysis
- Welch t-tests
- ANOVA
- Multiple regression

## Key Findings

- Energy, danceability, and loudness increased over time in the Spotify dataset.
- Tracks from 2000–2020 had significantly higher average energy, danceability, and loudness than tracks from 1980–1999.
- Danceability and loudness showed positive associations with popularity.
- Energy had a weaker relationship with popularity and did not remain positively associated after controlling for release year.
- Popularity could not be fully explained by audio features alone, so the results should be interpreted as descriptive and associational rather than causal.

## Repository Structure

```text
spotify-audio-features-analysis/
├── README.md
├── DS116_Final_Project_IEEE.pdf
└── DS116_Group1_Final_Project_Code.Rmd
```

## Data Source

The dataset used in this project is the Spotify Dataset 1921–2020, 600k+ Tracks from Kaggle:

https://www.kaggle.com/datasets/yamaerenay/spotify-dataset-19212020-600k-tracks

The dataset is not included in this repository. Only the final report and project code are included.

## Skills Demonstrated

- Data cleaning
- Exploratory data analysis
- Statistical testing
- Regression analysis
- Data visualization
- Analytical writing
- Interpretation of statistical results

## Author

Aleks Mantashyan  
Data Science Student  
American University of Armenia
