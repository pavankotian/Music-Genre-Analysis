# Music Genre Analysis Project
This repository contains my Week 1 data analysis project.

Music Genre Popularity Analysis

A mini data analysis project by Pavan Kotian

Project Overview

This project explores how different music genres perform across multiple metrics such as popularity, danceability, energy, and song count.
The goal is to understand what makes a genre “strong” overall—not just popular.

The analysis was done using Python, Pandas, NumPy, and Matplotlib, and the final report (PDF) includes all plots and insights.

Tools & Techniques Used

Pandas for data cleaning, grouping, aggregations

NumPy for numerical operations

Matplotlib for visualizations (line plots, histograms, scatter plots, bubble chart)

GroupBy + Agg for computing average popularity, danceability, energy, and count

Sorting & ranking genres based on metrics

Correlation-style comparisons (energy ↔ danceability, duration ↔ popularity)

Key Insights

Funk is the most popular genre but has a very low song count.

Pop emerges as the strongest overall genre, balancing popularity, danceability, energy, and representation.

Alternative consistently ranks the lowest across most metrics.

Song count alone does not determine popularity.

Combined metrics give a more realistic picture of a genre’s strength.

Included in This Repository

songs.csv — Sample dataset used for analysis

analysis_notebook.ipynb — Python notebook containing all code

Pavan_Kotian_Music_Genre_Popularity_Analysis_with_plots.pdf — Final analysis report with explanations + visuals

README.md — Project summary (you are reading it)

How to Run the Project

Clone the repository:

git clone https://github.com/pavankotian/Music-Genre-Analysis.git


Install dependencies:

pip install pandas numpy matplotlib


Open the notebook:

jupyter notebook analysis_notebook.ipynb


Run each cell to reproduce the analysis and plots.

Final Thoughts

This project is a great introduction to data exploration, visualization, and storytelling with data.
It reflects a practical workflow used in analytics and machine learning pipelines.
