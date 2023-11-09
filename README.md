# Wildfire-Analysis
"🔥 Wildfire Analysis Tools 📊  Explore data, scripts, and insights for wildfire analysis. #WildfireAnalysis #DataScience"
# Wildfire Analysis Project

This repository contains notebooks and scripts for wildfire analysis. The project aims to provide valuable insights into wildfire data, including data scraping, preprocessing, analysis, and visualization.

## Data 
Data for the wildfire was scrapped from https://www.sciencebase.gov/catalog/item/61aa537dd34eb622f699df81 . Specifically Combined_datset was used. The data used for analysis in this
project is from 1963 to 2023. The city for which the Analysis is done is West Odessa.

# Data Files for Wildfire and Air Quality Analysis

This repository contains data files used in wildfire and air quality analysis, along with a brief explanation of each file.

1. **preprocessed_fire_data.csv**: This file contains initial total fire data extracted from a website. It has been processed and converted into a structured DataFrame from raw JSON format. The dataset includes important variables, such as the area affected by fire in acres and the distance in miles from the city of interest, which is West Odessa in this case.

2. **particulate_data.json**: This file contains raw data for particulate level Air Quality Index (AQI) specific to West Odessa.

3. **gaseous_data.json**: This file contains raw data for gaseous level Air Quality Index (AQI) specific to West Odessa.

4. **particulate_aqi_data_processed.csv**: This file contains data processed from `particulate_data.json` for further analysis.

5. **gaseous_aqi_data_processed.csv**: This file contains data processed from `gaseous_data.json` for further analysis.

6. **particulate_aqi_data_processed.json**: This file contains the processed data from `particulate_data.json` for analysis purposes.

7. **gaseous_aqi_data_processed.json**: This file contains the processed data from `gaseous_data.json` for analysis purposes.

8. **aqi_score_combined.csv**: This file contains the final AQI value and the wildfire impact score calculate for visualisation and prediction purposes.

These data files are essential for conducting analysis related to wildfires and air quality. Feel free to explore and use them for your research and projects.


## Notebooks

1. **using_reader.ipynb**: This Jupyter notebook is dedicated to scraping wildfire data.

2. **aqi_extraction.ipynb**: Scrapes Air Quality Index (AQI) data for a specific city.

3. **data_preprocessing.ipynb**: Handles data preprocessing tasks.

4. **final_analysis.ipynb**: Calculates a custom wildfire score, compares it with AQI data, and returns correlations.

5. **visualization.ipynb**: Contains code for generating various graphs and visualizations.

6. **forecast.ipynb**: Implements forecasting techniques for wildfire analysis.

Feel free to explore the notebooks for detailed information on each step of the wildfire analysis process.

## Graphs 

The graphs folder contains several graphs produced from this analysis

## Dependencies

Make sure to install the required dependencies before running the notebooks. You can typically find the necessary packages in a `requirements.txt` file or within the notebooks themselves.

## Usage
