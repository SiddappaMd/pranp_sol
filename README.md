# TO compile each file you write the following commands in terminal, screenshot of the terminal is attached. 

# For problem 1 ------>   python3 problem1.py
# For problem 2 ------>   python3 problem2.py
# For problem 3 ------>   python3 problem3.py
# For problem 4 ------>   python3 problem4.py

# Code Challenge Template

# coding: utf-8

# Overview
# --------
# 
# Save the attached file to your workspace and unpack the files. You should now have a folder, coding-data-exam, with three sub-folders:
# 
#         wx_data/        Weather data files
#         yld_data/       Yield data files
#         answers/        Empty folder where you will place your answers to the questions on this exam
#         src/            Empty folder where you will place your source code that generated the answers
# 
# Weather Data Description
# ------------------------
# 
# The wx_data folder has files containing weather data records from 1-Jan-1985 to 31-Dec-2014. Each file corresponds to a particular weather station from Nebraska, Iowa, Illinois, Indiana, or Ohio. 
# 
# Each line in the file contains 4 records separated by tabs: 
# 
# 1. The date (YYYYMMDD format)
# 2. The maximum temperature for that day (in tenths of a degree Celsius)
# 3. The minimum temperature for that day (in tenths of a degree Celsius)
# 4. The amount of precipitation for that day (in tenths of a millimeter)
# 
# Missing values are indicated by the value -9999.
# 
# Yield Data Description
# ----------------------
# 
# The yld_data folder has a single file, US_corn_grain_yield.txt, containing a table of the total harvested corn grain yield in the United States measured in 1000s of megatons for the years 1985 - 2014.
# 
# Problem 1
# ---------
# Program to calculate for each weather data file the number of days in which the maximum temperature and minimum temperature data are present but the precipitation data is missing. Output is written inin the file MissingPrcpData.out in the answers folder.
# 
# 
# Problem 2
# ---------
# Program to calculate the following values for every year for every station, ignoring missing data:
# 
#         Average maximum temperature (in degrees Celsius)
#         Average minimum temperature (in degrees Celsius)
#         Total accumulated precipitation (in centimeters)
# 
# Results are in the file YearlyAverages.out in the answers folder.
# Problem 3
# ---------
# Program that tabulates how often each year from 1985-2014 had the highest average maximum temperature, highest average minimum temperature, and highest total accumulated precipitation from the set of weather stations. Output is written to the file YearHistogram.out in the answers folder. Created a histogram of the output and save the result as YearHistogram.png.
# 
# Problem 4
# ---------
# Use the annual average maximum temperature, annual average minimum temperature, and total annual precipitation results from Problem 2 and calculate the Pearson correlation between these variables and the grain yield data stored in US_corn_grain_yield.txt. Output to the file Correlations.out in the answers folder.
