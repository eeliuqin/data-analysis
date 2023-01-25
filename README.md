# Projects of Data Analysis

This repository is a series of notebooks of data analysis related projects using Python or R.

Some features like internal links, SVG are not rendered correctly in GitHub, so it's recommended to view it in nbviewer, a tool created by Jupyter community for rendering a notebook hosted on GitHub.

Here is the list of projects and the corresponding nbviewer links:

## Python

- [Visualizing U.S. Plug-in Electric Vehicle Sales](https://github.com/eeliuqin/data-analysis/blob/main/us-plug-in-electric-vehicle-sales.ipynb) (clich [hear](https://nbviewer.org/github/eeliuqin/data-analysis/blob/main/us-plug-in-electric-vehicle-sales.ipynb) to view it in nbviewer)
  * Task: EDA of the U.S. PEV sales data, finding out the top models, top makers, and Tesla vs. Non Tesla sales.
  * Data source: U.S. Plug-in Electric Vehicle Sales, 2010-2022, the [.csv](https://github.com/eeliuqin/data-analysis/blob/main/data/us-plug-in-ev-sales.csv) file was scraped from 4 websites.
  
- [Analyzing Strategy Games on Apple App Store](https://github.com/eeliuqin/data-analysis/blob/main/mobile-strategy-games.ipynb) (click [here](https://nbviewer.org/github/eeliuqin/data-analysis/blob/main/mobile-strategy-games.ipynb) to view it in nbviewer)
  * Task: Analyzing mobile strategy games by classifications, price, user ratings, and competitors. Providing recommendations to mobile game developers.
  * Data source: 17K Mobile Strategy Games dataset found in [Kaggle](https://www.kaggle.com/datasets/tristan581/17k-apple-app-store-strategy-games?select=appstore_games.csv)


- [Finding the Most Popular Data Science Questions](https://github.com/eeliuqin/data-analysis/blob/main/popular-data-science-questions.ipynb) (click [here] (https://nbviewer.org/github/eeliuqin/data-analysis/blob/main/popular-data-science-questions.ipynb) to view it in nbviewer)
  * Task: Finding out the most popular data science questions and provide recommendations for online education sites that focus on data science.
  * Data source: Run SQL query and download the corresponding .csv file from [Data Science Stack Exchange](https://data.stackexchange.com/datascience/query/new)

- [Exploring CIA World Factbook](https://github.com/eeliuqin/data-analysis/blob/main/cia-world-factbook-visualization.ipynb) (click [here](https://nbviewer.org/github/eeliuqin/data-analysis/blob/main/cia-world-factbook-visualization.ipynb) to view it in nbviewer)
  * Task: EDA of the world's facts, including population, population density, population growth rate, mortality rate, and migration rate.
  * Data source: Single-File SQLite Distribution of 260+ World Factbook Country Profiles that can be downloaded from [Github](https://github.com/factbook/factbook.sql/releases)


## R

- [Text Mining and Sentiment Analysis for NYC Airbnb Reviews](https://github.com/eeliuqin/data-analysis/blob/main/airbnb-nyc-sentiment-analysis.ipynb) (click [here](https://nbviewer.org/github/eeliuqin/data-analysis/blob/main/airbnb-nyc-sentiment-analysis.ipynb) to view it in nbviewer)
  * Task: Performing text mining and sentiment analysis on those reviews. Finding out why users leave negative reviews.
  * Data source: 2009-2022 New York City Airbnb reviews. The data can be found [here](http://insideairbnb.com/get-the-data/)

- [Capstone Project of the Google Data Analytics Professional Certificate: Cyclistic Bike-Share Analysis](https://github.com/eeliuqin/data-analysis/blob/main/google-da-capstone-project-bike-share.ipynb) (click [here](https://nbviewer.org/github/eeliuqin/data-analysis/blob/main/google-da-capstone-project-bike-share.ipynb) to view it in nbviewer)
  * Task: Analyzing how the Cyclistic bikes are used differently by casual riders and annual members. Devising a new marketing strategy to turn casual riders into annual members.
  * Data source: Chicago Divvy Bicycle Sharing Data from May, 2021 to April, 2022. The data can be downloaded [here](https://divvy-tripdata.s3.amazonaws.com/index.html)

- [Understanding Worldwide COVID-19 Vaccination Progress](https://github.com/eeliuqin/data-analysis/blob/main/covid19-vaccination-progress.ipynb) (click [here](https://nbviewer.org/github/eeliuqin/data-analysis/blob/main/covid19-vaccination-progress.ipynb) to view it in nbviewer)
  * Task: Analyzing vaccination rates by country and vaccines used by countries. 
  * Data source: `country_vaccinations.csv` from [Kaggle](https://www.kaggle.com/datasets/gpreda/covid-world-vaccination-progress?datasetId=1093816&language=R&select=country_vaccinations.csv). Data was collected daily from the GitHub repository [covid 19 data](https://github.com/owid/covid-19-data). 

- [Exploring NYC High Schools Perceptions](https://github.com/eeliuqin/data-analysis/blob/main/nyc-high-schools-perceptions.ipynb) (click [here](https://nbviewer.org/github/eeliuqin/data-analysis/blob/main/nyc-high-schools-perceptions.ipynb) to view it in nbviewer)
  * Task: Analyzing whether perceptions of NYC school quality are related to demographic and academic success metrics.
  * Data source: The NYC school data was compiled from publicly available data provided by the city of New York. It has been cleaned up and uploaded by Dataquest, and can be downloaded from [here](https://data.world/login?next=%2Fdataquest%2Fnyc-schools-data%2Fworkspace%2Ffile%3Ffilename%3Dcombined.csv).

- [Analyzing Forest Fires Data](https://github.com/eeliuqin/data-analysis/blob/main/forest-fires.ipynb) (click [here](https://nbviewer.org/github/eeliuqin/data-analysis/blob/main/forest-fires.ipynb) to view it in nbviewer)
  * Task: Investigating when forest fires were most frequent and if any patterns existed.
  * Data source: [forestfires.csv](https://archive.ics.uci.edu/ml/machine-learning-databases/forest-fires/) is a dataset of forest fires in Montesinho park, Portugal, collected from January 2000 to December 2003.


## A/B Testing

- [Udacity A/B Testing Final Project: Free Trial Screener](https://github.com/eeliuqin/data-analysis/blob/main/AB-Testing/Udacity-AB-Testing-Final-Project.ipynb) (click [here](https://nbviewer.org/github/eeliuqin/data-analysis/blob/main/AB-Testing/Udacity-AB-Testing-Final-Project.ipynb) to view it in nbviewer)
  * Experiment: Udacity tested a change where if the student clicked start free trial, they saw a pop up modal that asked them how much time they had available to devote to the course. The critical value was 5 hours:
    - If the student indicated 5 or more hours per week, they would be taken through the checkout process as usual.
    - If they indicated fewer than 5 hours per week, a message would appear indicating that Udacity courses usually require a greater time commitment for successful completion, and suggesting that the student might like to access the course materials for free. At this point, the student would have the option to continue enrolling in the free trial, or access the course materials for free instead.
  * Hypothesis: This UI change might set clearer expectations for students upfront, thus reducing the number of frustrated students who left the free trial because they didn't have enough time—without significantly reducing the number of students to continue past the free trial and eventually complete the course.
  * Data source:
    - [Rough Estimates of the Baseline Values](https://docs.google.com/spreadsheets/d/1MYNUtC47Pg8hdoCjOXaHqF-thheGpUshrFA21BAJnNc/edit#gid=0): This spreadsheet contains rough estimates of the baseline values, we are going to use it for pre-test analysis, in other words, we will design the A/B test based on its data.
    - [Test Results](https://docs.google.com/spreadsheets/d/1Mu5u9GrybDdska-ljPXyBjTpdZIUev_6i7t4LRDfXM8/edit#gid=0): This spreadsheet contains the test results, we are going to analyze it to decide if the change has any effect.
