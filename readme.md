This project involves performing Exploratory Data Analysis (EDA) on Airbnb listings in New York City using the "New York Airbnb Open Data 2024" dataset. The analysis provides insights into various factors influencing Airbnb pricing, location distribution, and other related factors.

Table of Contents
Project Overview

Data Description

Data Cleaning

Exploratory Data Analysis

Visualizations

Key Insights

Setup and Installation

Usage

Contributions

License

Project Overview
This project explores the New York Airbnb dataset to uncover valuable insights. We perform various steps of data cleaning, statistical analysis, and visualizations to better understand the dataset, identify trends, and answer business-related questions about Airbnb listings.

Objective
Understand the pricing trends of Airbnb listings in NYC.

Examine the relationship between various features (e.g., room type, neighborhood) and the listing price.

Explore the geographical distribution of Airbnb listings.

Data Description
The dataset contains information about over 50,000 Airbnb listings in New York City. The key features include:

price: Price per night for the listing.

room_type: The type of room (e.g., Entire home/apt, Shared room).

neighbourhood_group: The neighborhood group where the listing is located.

availability_365: Number of available days in the year.

reviews_per_month: Average number of reviews per month.

latitude & longitude: Location coordinates.

Data Cleaning
In this step, we address any missing values, remove duplicates, and ensure that the dataset is in the correct format for analysis. This includes:

Handling missing values in key columns.

Converting data types for specific columns.

Dropping duplicates and irrelevant rows.

Exploratory Data Analysis
Univariate Analysis: Analysis of individual variables to understand their distributions.

Bivariate Analysis: Investigation of relationships between two variables (e.g., price vs. room type).

Correlation Analysis: Examining how numerical variables relate to each other.

Visualizations
Throughout the analysis, we use various visualization techniques such as:

Histograms and Boxplots to explore price distributions.

Bar charts to compare room types and neighborhoods.

Scatter plots and heatmaps for correlation analysis.

Geospatial maps to visualize the geographical distribution of listings.

Key Insights
Average price of Airbnb listings and price ranges across different neighborhoods.

Factors influencing the price, such as room type, location, and availability.

Distribution of listings across New York City.

Setup and Installation
To set up this project locally, follow these steps:

Clone this repository:

bash
Copy
Edit
git clone https://github.com/Vibhanshu89/airbnb-eda.git
cd airbnb-eda
Install the required libraries: It's recommended to create a virtual environment to manage dependencies. Then install the necessary libraries:

bash
Copy
Edit
pip install -r requirements.txt
The requirements.txt file contains:

nginx
Copy
Edit
pandas
numpy
matplotlib
seaborn
folium
Usage
To start exploring the dataset, simply run the following Python script:

bash
Copy
Edit
python airbnb_eda.py
This will run the full exploratory data analysis process and generate various plots and statistical summaries.

Contributions
Feel free to contribute to this project by submitting issues, suggestions, or pull requests.