# 📺 Netflix Movie Analysis

## Project Description

This project analyzes a dataset of Netflix movies to gain insights into the characteristics of the movie library on the platform. The analysis covers movie duration distribution, most frequent genres, and a specific investigation into movies released in the 1990s.

## Data

The analysis uses the `netflix_data.csv` dataset with the following columns:

| Column | Description |
|--------|-------------|
| `show_id` | The ID of the show |
| `type` | Type of show |
| `title` | Title of the show |
| `director` | Director of the show |
| `cast` | Cast of the show |
| `country` | Country of origin |
| `date_added` | Date added to Netflix |
| `release_year` | Year of Netflix release |
| `duration` | Duration of the show in minutes |
| `description` | Description of the show |
| `genre` | Show genre |

## Analysis Performed

The project includes the following analysis steps:

1.  **Data Loading and Exploration:** Loading the dataset and performing initial data exploration to understand its structure and content.
2.  **Movie Filtering:** Filtering the dataset to include only movies.
3.  **Movie Duration Distribution:** Visualizing the distribution of movie durations using a histogram.
4.  **Most Frequent Genres:** Identifying and visualizing the top 10 most frequent movie genres using a bar plot with counts.
5.  **Analysis of 1990s Movies:**
    *   Determining the most frequent movie duration for movies released between 1990 and 1999.
    *   Counting and listing short action movies (duration less than 90 minutes) released in the 1990s.

## Skills Used

*   Python
*   Data Manipulation (pandas)
*   Data Analysis
*   Data Visualization (matplotlib, seaborn)

## How to Run

This analysis can be run in a Python environment with the necessary libraries installed (pandas, numpy, matplotlib, seaborn). Ensure the `netflix_data.csv` file is in the correct path as specified in the notebook.
