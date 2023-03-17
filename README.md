# Bokeh Micro Task: NYC Taxi Trip Data Visualization
## By Ajoke Yusuf
## Table of Content
- Introduction
- Dataset Overview
- Data Cleaning
- Data Visualization using Bokeh plot
- Interactive Bokeh plot
## Introduction
The main aim of this project is to carry out an exploratory data analysis with a subset of the dataset using Bokeh plots for visualization. In this project, the link to download the dataset was provided. The pdf containing the metadata can be found [here](https://www.nyc.gov/assets/tlc/downloads/pdf/data_dictionary_trip_records_green.pdf). I will be using Python data science and Bokeh plot for visualizing my data to explore the dataset’s variables and understand the data’s structure, oddities, patterns, and relationships.

## Dataset Overview
The dataset link was provided and downloaded from [here](https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page). 
The dataset downloaded was 2022 Green Taxi Trip Record in parquet format which span from January 2022 to November,2022. The datset consist of 2137732 records and 23 variable in the dataframe. See the data dictionary(meta data) to understand the dataset variables

## Data Cleaning
- Imported the data and went through the metadata to understand the meaning of each features/variable.
- Dropped columns that contained 99% to 100% null values
- Converted the dtypes of "lpep_pickup_datetime" and "lpep_pickup_datetime" column to datetime
- Extracted month, day, and time from "lpep_pickup_datetime" and "lpep_pickup_datetime"
- Dropped null values found in other columns

## Data Visualization using Bokeh PLot
I used various Bokeh plot for visualization of my analysis carried out. Example of plot used are: Scatter plot, whisker plot, data interactive bar chart, pie chart, subplot e.t.c

## Interactive Bokeh PLot
I created data table plot in Bokeh which provide a flexible and powerful way to explore, analyze, and visualize large datasets.
