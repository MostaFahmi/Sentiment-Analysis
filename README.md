## Overview

- Conducted sentiment analysis on Amazon product reviews using Python.
- Utilized TextBlob for general sentiment analysis and NLTK's VADER for detailed sentiment analysis.

## Libraries Used

- **NumPy and Pandas**: Data manipulation and analysis.
- **Matplotlib and Seaborn**: Data visualization.
- **NLTK (Natural Language Toolkit)**: VADER for sentiment analysis.
- **TextBlob**: General sentiment analysis.
- **WordCloud**: Creation of word clouds.
- **Cufflinks and Plotly**: Interactive visualizations.
- **TQDM**: Displaying progress bars.
- **Warnings**: Management and suppression.

## Data

- Dataset: [CSV file containing Amazon product reviews (`amazon.csv`).](https://drive.google.com/drive/folders/1Vbz73qJ0GlhFIvm8NIipbIqtE5M7t_tm)
- Columns: `reviewText`, `overall` (rating), and calculated columns like `polarity` and `subjectivity` from TextBlob.

## Data Exploration

- Functions for missing values, data types, duplicates, and quantiles analysis.

## Categorical Data Analysis

- Analysis and visualization of categorical data, e.g., sentiment of reviews using bar plots and pie charts.

## Sentiment Analysis

- Used TextBlob and VADER to categorize reviews as Positive, Negative, or Neutral.
- Additional column (`wilson_lower_bound`) for sorting reviews.

## Sentiment Analysis Plotting

- Visualized sentiment distribution and its relation to overall scores using bar plots.
