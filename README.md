# Netflix-Data-Analysis
This repository contains an analysis of Netflix data using Python. The dataset includes various features related to Netflix shows and movies. The analysis aims to provide insights into the types, directors, countries, ratings, categories, and the date added of the content available on Netflix.

# Table of Contents
> Installation
> Dataset
> Analysis
> Data Cleaning
> Exploratory Data Analysis
> Visualizations
> Conclusion
> Contributing

#Installation
To run the analysis, you need to have Python installed along with the following packages:
> pandas
> numpy
> matplotlib
> seaborn
> datetime

# Dataset
The dataset used in this analysis is a CSV file named netflix.csv, which contains information about Netflix shows and movies. The dataset includes the following columns:

> show_id
> type
> title
> director
> cast
> country
> date_added
> release_year
> rating
> duration
> listed_in
> description

# Analysis
# Data Cleaning
The data cleaning steps include:

> Removing duplicate entries.
> Handling missing values by dropping rows with missing data.
> Dropping unnecessary columns: show_id, title, cast, and description.
> Renaming columns for better readability.
# Exploratory Data Analysis
The exploratory data analysis (EDA) includes:

> Converting date_added to datetime format.
> Extracting the year from date_added.
> Analyzing the distribution of content types (Movies and TV Shows).
> Identifying the top 10 directors for movies and TV shows.
> Identifying the top 10 countries producing movies and TV shows.
> Analyzing the top 10 ratings for movies and TV shows.
> Identifying the top 10 categories for movies and TV shows.
> Analyzing the distribution of the year the content was added to Netflix.

# Visualizations
The visualizations created during the analysis include:

> Pie chart showing the distribution of Movies and TV Shows.
> Bar charts for the top 10 directors, countries, ratings, and categories for movies and TV shows.
> Histogram showing the distribution of the year the content was added to Netflix.

# Conclusion
This analysis provides valuable insights into the types and distribution of content available on Netflix. The visualizations help to understand the trends and patterns in the Netflix dataset.
