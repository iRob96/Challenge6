# Challenge6


Rental Market Analysis

This app allows users to find viable investment opportunities in the San Fransico market.

---

## Tech Used

Python 3.7
Jupyter Lab
Pyviz (HVplot & Geoviews)

---
## Install Guide

Install libraries in python by going to the terminal and typing the following:
Pyviz- conda install -c pyviz hvplot geoviews
--

##Use

We were given csv files of different information. We called in those files using the path function to create dataframes. Then we edited those dataframes using the groupby and mean functions to sort by specifc areas and take their averages. After that we plotted the info by using hvplot funtion to make interactive charts. We repeated these steps using various csv and plots. On the final step we put info from two separte dataframes using the concat function. We sorted that info as well to clean it up. the final step was to make a hvplot with geoviews (using actual coordinates) by seting all the proper parameters and answer the questions that followed.
