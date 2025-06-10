Netflix Data Cleaning & Analysis Project:
This project focuses on cleaning, analyzing, and generating insights from Netflix's title dataset. It covers intermediate-level data wrangling using Python and presents key insights about content types, trends, durations, and categories.

Dataset Overview:
Source: Public Netflix dataset (2008–2021)
Total Records: 8,500 titles
Columns: type, title, director, country, date_added, release_year, rating, duration, listed_in, etc.

Key Objectives:
Clean raw Netflix data and handle missing/null values.
Perform exploratory data analysis (EDA) with visualizations.
Engineer new features for deeper insights.
Build a professional portfolio-ready Jupyter Notebook.

Tools Used:
Python (Pandas, NumPy, Matplotlib, Seaborn)
Jupyter Notebook (Anaconda)
GitHub (for version control and showcasing)

Data Cleaning Steps:
Removed/standardized "Not Given" and null values.
Parsed date_added into year, month, day.
Split duration into duration_int and duration_unit.
Extracted and counted genres from the listed_in colum.

 EDA Highlights:
Movie vs TV Show distribution.
Top countries by content production.
Genre frequency analysis.
Director contribution counts.
Release trends over years and months.
Rating distribution.

Feature Engineering:
content_age → Age of content as of 2025.
num_genres → Number of genre tags per title.
time_to_netflix → Years between release and upload on Netflix.

Insights
Majority of Netflix content is movies.
United States and India lead in content volume.
Many shows are tagged with 2–3 genres.
TV-MA is the most common rating.
Netflix continues to upload older content alongside new releases.

File Structure:
Netflix_Data_Analysis.ipynb – Main project notebook.
netflix1.csv – Cleaned Netflix dataset.
README.md – This file.
