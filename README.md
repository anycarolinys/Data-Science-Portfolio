# Data Science Portfolio


## Airbnb Project

This project aims to analyze the Airbnb listings in three steps:

<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/6/69/Airbnb_Logo_B%C3%A9lo.svg/2560px-Airbnb_Logo_B%C3%A9lo.svg.png" alt="Airbnb Logo" width="450" height="150">  

Airbnb Logo. Font: Wikipedia.

### 1. Implement Quality Assurance on Data by:

- Import/Open the Listings.csv file
- Cast any date columns as a datetime format
- Filter the data down to rows where the city is Paris, and keep only the columns 'host_since', 'neighbourhood', 'city', 'accommodates', and 'price' in your dataframe
- Check for missing values, and calculate the minimum, maximum, and average for each numeric field


### 2. Prepare Data for Visualization by:
- Create a dataframe named paris_listings_neighbourhood, that groups Paris listings by `neighbourhood' and calculates the mean price for each neighborhood sorted from lowest to highest average price
- Create a dataframe named paris_listings_accomodations. This dataframe should be filtered down to the most expensive neighborhood in Paris, grouped by the 'accommodations' column, and contain the mean price for each value of 'accommodates' sorted from lowest to highest average price
- Create a dataframe called paris_listings_over_time, which is grouped by the year of the 'host_since' column. Calculate a count of rows, representing total number of new hosts, and the average price for each year

### 3. Visualize data by:

- Create a horizontal bar chart of the average price by neighborhood in Paris. 
- Create a horizontal bar chart of the average price by 'accommodates' in Paris' most expensive neighborhood.
- Create two line charts: one of the count of new hosts over time, and one for average price, make sure to set the y-axis limit to O, add a title, and change axis labels as needed.
- Create a dual axis line chart that contains both new hosts and average price over time.