# web-scraping-challenge
Module 11 Challenge

## Description
This project involves scraping information from the Mars News website and analyzing Mars weather data. The goal is to demonstrate core skills in collecting, organizing, and analyzing data, as well as visually communicating insights.

## Components

### 1. Scrape Titles and Preview Text from Mars News
- In `part_1_mars_news.ipynb`, use automated browsing to visit the [Mars News site](https://static.bc-edx.com/data/web/mars_news/index.html).
- Utilize Beautiful Soup to create a soup object and extract text elements.
- Extract and store titles and preview text of news articles in Python dictionaries.
- Print the list of dictionaries in the notebook.

### 2. Scrape and Analyze Mars Weather Data
- In `part_2_mars_weather.ipynb`, use automated browsing to visit the [Mars Temperature Data Site](https://static.bc-edx.com/data/web/mars_facts/temperature.html).
- Use Beautiful Soup to scrape data in the HTML table and assemble it into a Pandas DataFrame.
- Examine and convert data types if necessary.
- Analyze the dataset to answer specific questions:
  - Identify the number of months and Martian days worth of data.
  - Determine the coldest and warmest months on Mars based on average minimum daily temperature.
  - Identify months with the lowest and highest atmospheric pressure on Mars.
  - Estimate the number of terrestrial days in a Martian year.
- Visualize insights by plotting results as bar charts.
- Export the DataFrame to a CSV file.

## Files
- **scraping-folder**
  - output.csv
  - part_1_mars_news.ipynb
  - part_2_mars_weather.ipynb

## Table of Contents
- [web-scraping-challenge](#web-scraping-challenge)
  - [Description](#description)
  - [Components](#components)
    - [1. Scrape Titles and Preview Text from Mars News](#1-scrape-titles-and-preview-text-from-mars-news)
    - [2. Scrape and Analyze Mars Weather Data](#2-scrape-and-analyze-mars-weather-data)
  - [Files](#files)    
