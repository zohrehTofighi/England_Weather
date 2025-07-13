# England_Weather

## Project Recap

This project performs an exploratory data analysis (EDA) on a historical weather dataset from England. It analyzes temperature, humidity, and other atmospheric conditions over time and visualizes trends by year, month, and weather summary.

## Dataset Description

Formatted Date:	Full timestamp of the recorded weather (used to extract year, month, and day)

Summary:	Short textual description of weather (e.g., Mostly Cloudy, Rain)

Precip Type:	Type of precipitation: usually Rain or Snow

Temperature (C):	Temperature in Celsius

Apparent Temperature (C):	What the temperature feels like, considering wind and humidity

Humidity:	Relative humidity (between 0 and 1)

Wind Speed (km/h):	Wind speed in kilometers per hour

Wind Bearing (degrees):	Wind direction in degrees

Visibility (km):	Visibility range in kilometers

Loud Cover:	Cloud Cover – represents how cloudy the sky is

Pressure (millibars):	Atmospheric pressure in millibars

Daily Summary:	More detailed description of the day’s weather

## Libraries Used

pandas, numpy, matplotlib, seaborn


## EDA (Exploratory Data Analysis)	

Data Cleaning:

Missing values were identified and removed using dropna().

The Formatted Date column was parsed and split into date, year, and month components.

Data Sampling:

The dataset contains hourly data, so one entry per day was selected ([::24]) for analysis.

Visualizations:

Bar plot: Average humidity per weather status (Summary)

Count plots: Number of entries per year, month, and day

Scatter plot: Temperature vs. Humidity

## Key Insights

Distribution of humidity varies across weather summaries.

The dataset spans multiple years and allows for seasonal trend analysis.

Temperature and humidity are positively correlated in many observations.
