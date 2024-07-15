# Airbnb Listings in Seattle Analysis
Python + Tableau | An analysis project that focused on Seattle market to figure out where and how to invest in The Airbnb market in Seattle

## Dataset
The datasets for this project was obtained from kaggle. As the project was part of a data science course, we used the Airbnb dataset for Seattle and analysed the listings in Seattle. The datasets can be obtained ![here](https://www.kaggle.com/datasets/airbnb/seattle).

## Implementation
### Step 1: Cleaning the dataset with Python
- Convert price of listings from strings to floats and also remove the '$' sign.
- Change NaN values to the integer 0.
- Removing unwanted columns from the dataset such as listing_url, scrape_id etc.
### Step 2: Analysis
- There are many factors which influence the price of a listing. Which is why we aim to find the most important factors that affect the price and more importantly the features that is common among the most expensive listings.

![The Features of a Property Affect its Price](https://github.com/trang-nguyen79/Airbnb-listing-analysis/blob/main/Dashboar%20Features.png)

- The potential neighborhoods that should be considered to invest

![Potential Locations](https://github.com/trang-nguyen79/Airbnb-listing-analysis/blob/main/Potential%20Locations.png)

## Coding Apendix
![Python](https://github.com/trang-nguyen79/Airbnb-listing-analysis/blob/main/Airbnb%20in%20Seattle%20Analysis.ipynb)
![Tableau](https://public.tableau.com/app/profile/trang.nguyen27/viz/Airbnbanalysis_17210147190610/DashboarFeatures?publish=yes)
