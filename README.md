# 🎵 Spotify Stream Analysis with Python & Power BI

## Project Overview
This project focuses on analyzing and visualizing the top streamed songs across different music platforms such as Spotify, YouTube, and TikTok. The dataset, "Most Streamed Spotify Songs 2024," contains information about tracks, albums, artists, and performance metrics on various platforms.


The goal of this project is to clean, transform, and prepare the dataset using Python Pandas for accurate analysis, followed by using Power BI to create insightful visualizations. The project is divided into two primary phases:

Phase 1: Data Cleaning & Preparation (Using Python Pandas)
Phase 2: Data Visualization & Insights (Using Power BI)

## Project Motivation
As data continues to play a pivotal role in the music industry, understanding trends, artist performance, and cross-platform popularity is critical. This project aims to leverage data analytics to generate insights that could benefit artists, labels, and marketers alike, while also improving data manipulation and visualization skills.

## Data
The dataset used in this project is sourced from Kaggle, titled Most Streamed Spotify Songs 2024. 
" https://www.kaggle.com/datasets/nelgiriyewithana/most-streamed-spotify-songs-2024 "
The dataset contains detailed information about songs' performances across various music streaming platforms, including:

Spotify: Streams, Popularity, Playlist Count, and Reach
YouTube: Views, Likes, Playlist Reach
TikTok: Posts, Views, Likes
Additional columns include metadata about the tracks, albums, and artists.

## Tools and Technologies
Python Libraries:
Pandas: For data cleaning, transformation, and manipulation.

Power BI:
Data Visualization: Used to create interactive dashboards and visualizations for uncovering insights.

## Project Phases

Phase 1: Data Cleaning & Preparation (Python Pandas)
Loading Data: The dataset is loaded and initially inspected to understand its structure and identify any anomalies.
Handling Missing Values: The data is cleaned by identifying and handling missing values across all relevant columns.
Dropping Unnecessary Columns: Columns that do not provide useful information for the analysis (such as less-known platforms or non-essential metadata) are removed.
Transforming Data: Data types are adjusted appropriately for numerical analysis (e.g., removing commas from numbers and converting dates to datetime format).
Splitting Data: The dataset is segmented into smaller DataFrames for analysis by platform: Spotify, YouTube, and TikTok.
Data Preparation for Visualization: The cleaned data is saved, exported to individual csv files and ready for further analysis in Power BI.

Phase 2: Data Visualization & Insights (Power BI)
Import Cleaned Data: The cleaned and transformed data is imported into Power BI.
Create Interactive Dashboards: Visualizations such as bar charts, line graphs, heatmaps, and more are used to explore:
Top 10 tracks by streams across each platform.
Most popular artists across platforms.
Trends in streaming data over time (e.g., spikes in streams, cross-platform performance).
Generate Insights: The dashboards reveal insights about which songs and artists are performing well across platforms, enabling deeper understanding of the music landscape.

## Key Features
Data Cleaning and Wrangling: Removing noise from the data, dealing with missing values, and making the dataset analysis-ready.
Cross-Platform Analysis: Insights about songs' performances on multiple streaming platforms.
Interactive Visualizations: Power BI dashboards that allow dynamic exploration of music streaming trends.

## How to Run This Project

Prerequisites
Python: Ensure you have Python installed on your system.
Required Libraries: Install the following libraries:

''' pip install pandas '''

Power BI: Download and install Microsoft Power BI Desktop.
Step 1: Clone the Repository
Step 2: Data Cleaning with Python
Open the Jupyter notebook or Python script that contains the data cleaning and transformation code.
Run the script to clean and prepare the dataset.
Step 3: Import Data to Power BI
Open Power BI Desktop.
Import the cleaned data (CSV or Excel) generated from the Python script.
Build your dashboard using the Power BI interface.
Project Structure

Spotify-Stream-Analysis/
│
├── data/                           # Raw and cleaned datasets
│   ├── Most Streamed Spotify Songs 2024.csv 
│   └── Cleaned_Spotify_Data.csv 
│
├── notebooks/                      # Jupyter notebooks for data cleaning and preparation
│   └── DataCleaning.ipynb
│
├── visuals/                        # Power BI reports and visualizations
│   └── Spotify_Stream_Dashboard.pbix
│
├── README.md                       # Project documentation
└── requirements.txt                # Python dependencies


## Insights & Results
Some initial insights that can be derived from the project:

Top Tracks: Identify the top 10 most-streamed tracks on Spotify, YouTube, and TikTok.
Artist Popularity: Determine which artists have the highest number of top-performing tracks across platforms.
Cross-Platform Performance: Analyze how certain tracks perform differently on various platforms, such as strong performance on TikTok but lower performance on YouTube.

## Future Work
Extend the Analysis: Incorporate other music platforms or external factors (e.g., seasonal trends, release dates) that may affect song performance.
Predictive Analytics: Use machine learning models to predict future trends in streaming data based on past performance.
