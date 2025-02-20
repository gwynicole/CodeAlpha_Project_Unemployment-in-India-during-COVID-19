# CodeAlpha_Project_Unemployment-in-India-during-COVID-19

# Overview
This project analyzes the impact of COVID-19 on unemployment and labor participation in India (2020) using Python. The study explores regional unemployment trends before and after the lockdown, identifies the most affected regions, and visualizes labor participation rates. The insights help understand economic disruptions and recovery patterns during the pandemic.

# Dataset
- Name: Unemployment in India.csv
- Source: The dataset contains unemployment-related data from different regions of India in 2020.
- Columns:
  - Region – Name of the state/region
  - Date – Month and year of recorded data
  - Estimated Unemployment Rate (%) – Percentage of unemployed individuals
  - Estimated Labour Participation Rate (%) – Workforce participation rate
  - month_int – Numeric representation of the month (used for filtering data)
 
# Dependencies
- import pandas as pd
- import numpy as np
- import matplotlib.pyplot as plt
- import seaborn as sns
- import plotly.express as px


# Results
- Unemployment Spike During Lockdown: Unemployment rates peaked in April-May 2020 due to strict lockdowns, followed by a gradual decline as the economy reopened.
- Most Affected Regions: Tripura, Haryana, and Jharkhand had the highest unemployment rates during the pandemic.
- Labor Participation Variability: Some states maintained higher workforce participation, while others showed a significant decline.
- Before vs. After Lockdown: A comparison of pre-lockdown (Jan-Apr 2020) vs. post-lockdown (Apr-Jun 2020) showed a sharp rise in unemployment across all regions.
- Unemployment Trends Over Time: A time-series analysis revealed fluctuations in unemployment, highlighting economic recovery patterns.
