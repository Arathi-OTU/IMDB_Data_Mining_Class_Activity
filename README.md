# IMDb Exploratory Data Analysis (EDA)

## Project Overview

This project performs Exploratory Data Analysis (EDA) on the IMDb Title Basics dataset obtained from the official IMDb datasets.

The objective is to understand the structure of the dataset, analyze trends in movie and TV titles, study runtime distributions, identify the most common genres, and visualize historical changes in IMDb content using interactive visualizations.

---

## Dataset

Source:
https://datasets.imdbws.com/

Dataset Used:
- title.basics.tsv.gz

The dataset contains information about IMDb titles including:

- Title Type
- Primary Title
- Original Title
- Adult Content Indicator
- Start Year
- End Year
- Runtime (minutes)
- Genres

---

## Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Plotly Express
- Plotly Graph Objects

---

## Data Preprocessing

The following preprocessing steps were performed:

- Loaded IMDb TSV dataset
- Converted TSV file into DataFrame
- Replaced missing values (`\N`) with NaN
- Converted numerical columns to appropriate data types
- Removed invalid records
- Created decade column from release year
- Split multiple genres into individual genre values
- Prepared cleaned dataset for visualization

---

## Exploratory Data Analysis

The notebook includes the following visualizations:

### 1. Title Type Distribution
Shows the number of Movies, TV Series, TV Episodes, Shorts, Videos, and other title types.

### 2. Adult vs Non-Adult Content
Displays the proportion of adult and non-adult titles using a pie chart.

### 3. Titles Released Over Time
Illustrates how the number of IMDb titles has changed across years.

### 4. Titles by Decade
Shows production trends grouped by decades.

### 5. Runtime Distribution
Analyzes the distribution of runtime across IMDb titles.

### 6. Average Runtime by Title Type
Compares average runtime for different title categories.

### 7. Runtime Variation
Uses boxplots to study runtime variability and outliers.

### 8. Top 20 Genres
Displays the most common genres available in the IMDb dataset.

### 9. Genre Treemap
Provides an interactive treemap representing genre popularity.

---

## Key Insights

- Movies represent the largest portion of IMDb titles.
- Adult titles make up only a very small percentage of the dataset.
- IMDb content production has increased significantly in recent decades.
- Most titles have runtimes between 60 and 120 minutes.
- Movies generally have longer runtimes than TV episodes.
- Drama, Comedy, and Documentary are among the most frequently occurring genres.
- Runtime distributions contain several outliers representing unusually long titles.
- Interactive visualizations make it easier to explore genre and temporal trends.

---

## Project Structure

```
IMDb_EDA/
│
├── IMDB_Class_activity1.ipynb
├── title.basics.tsv.gz
├── README.md
└── visualizations/
```

---

## How to Run

1. Clone the repository.

```
git clone <repository_link>
```

2. Open the notebook in Google Colab or Jupyter Notebook.

3. Download the IMDb dataset from:

https://datasets.imdbws.com/

4. Place `title.basics.tsv.gz` in the project directory.

5. Run all notebook cells.

---

## Future Improvements

- Analyze IMDb ratings dataset.
- Join title and ratings datasets.
- Build dashboards using Dash or Streamlit.
- Perform predictive analytics on movie trends.
- Create genre-based recommendation insights.

---

## Author

Arathi Jadhav
