# ANALYSIS-OF-PRECIPITATION-VARIABILITY-AND-TRENDS-OVER-SOUTH-AFRICA-1990-2020-
# Climate Science Assignment: Exploring Climate Variability and Trends

## Overview

This project focuses on analyzing climate variability and trends, specifically precipitation patterns, using the CRU TS4.07 dataset. The analysis involves processing and visualizing climate data using Python with libraries such as xarray, matplotlib, and numpy. The primary goal is to understand how precipitation changes over time and space within a specified country.

## Project Objectives

The project is divided into four main parts:

1.  **Data Acquisition and Exploration:** Downloading the CRU TS4.07 dataset and performing initial data inspection.
2.  **Temporal Analysis:** Analyzing annual mean precipitation, identifying trends, and assessing interannual variability.
3.  **Spatial Patterns over Time:** Examining decadal changes in precipitation and identifying spatial hotspots of change.
4.  **Extreme Event Analysis:** Analyzing the frequency of "wet years" to understand extreme precipitation events.

## Data

The CRU TS4.07 dataset is used, which provides monthly precipitation data. The dataset is available in NetCDF format and can be downloaded from:

* [CRU TS4.07 Dataset](https://crudata.uea.ac.uk/cru/data/hrg/)

## Tools

The analysis is performed using Python with the following libraries:

* xarray
* matplotlib
* numpy

## Project Structure

The project is organized as follows:

### Part 1: Data Acquisition and Exploration

* **1.1 Dataset Download:** Download the monthly precipitation data from the CRU TS4.07 dataset.
* **1.2 Bounding Box Definition:** Define the spatial extent of the analysis by specifying a bounding box (latitude and longitude ranges) for the assigned country.
* **1.3 Data Loading and Initial Inspection:** Load the dataset using xarray and describe its dimensions, coordinate system, variables, and units.
* **1.4 Mean Precipitation Mapping:** Calculate and visualize the spatial distribution of mean precipitation over the period 1990-2020.

### Part 2: Temporal Analysis

* **2.1 Annual Mean Precipitation Time Series:** Compute and plot the time series of annual mean precipitation.
* **2.2 Trend Analysis:** Fit a linear trend line to the annual time series and interpret the trend.
* **2.3 Variability Analysis:** Calculate and discuss the standard deviation of the annual mean precipitation.

### Part 3: Spatial Patterns over Time

* **3.1 Decadal Averages:** Calculate and plot mean precipitation for the decades 1990-1999 and 2010-2020. Generate a difference map to show changes between the two decades.
* **3.2 Hotspot Identification:** Identify and report the top 5 grid points with the largest increase and decrease in precipitation.

### Part 4: Extreme Event Analysis

* **4.1 Wet Year Frequency:** Define a "wet year" and calculate the frequency of wet years for each grid cell. Visualize the spatial distribution of wet year frequency.

## Deliverables

* A well-organized report (maximum 8 pages) including:
    * Description of the bounding box.
    * Plots and maps with labeled axes, colorbars, and legends.
    * Tables of hotspot results.
    * Interpretations of figures and tables.
    * A concluding summary of key findings.
* Python code (.ipynb or .py script) with clear comments and logical sectioning.

## Grading Rubric

| Task                                          | Marks |
| --------------------------------------------- | ----- |
| Part 1: Data Handling and Mean Map            | 15    |
| Part 2: Time Series, Trend, and Variability | 25    |
| Part 3: Decadal Change and Hotspot Identification | 30    |
| Part 4: Extreme Event (Wet Year) Analysis    | 20    |
| Report Structure, Code Quality, Interpretation     | 10    |
| **Total** | **100** |

## Citation

The CRU TS4.07 dataset should be cited as follows:

>   Harris, I. C., & Jones, P. D. (2022). CRU TS4.07: Climatic Research Unit (CRU) Time-Series (TS) Version 4.07 of High-Resolution Gridded Data of Month-by-month Variation in Climate (January 1901-December 2022). Centre for Environmental Data Analysis. https://crudata.uea.ac.uk/cru/data/hrg/

