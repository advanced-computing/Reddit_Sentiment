# Egg Prices, Bird Flu, and Cal-Main Profits

This project aims to explore the relation between the bird flu and Egg Price fluctuations. The main research aims are the following:
1) What is the relationship between the increase of bird flu outbreaks and increases in Grade A egg prices? Is there a time lag?
2) Is there a correlation between local cases of bird flu and local prices of eggs? (lmay need to change pending data availability for local egg prices)
3) How does the stock price of Cal-Main Foods (biggest egg company in USA) respond to bird flu outbreak?
4) How do consumer respond to egg price increases? What is the demand elasticity for eggs? (Need to find consumption data)

Issues


Data
[] Organize data into a folder? (Temporary until APIs ready, may not be worth it)
[] set up API for Bird Flu data (clickable link)
[] set up API for Cal-Main data (clickable link)
[] set up API for egg prices from BLS (clickable link)
[] set up API for National Agricultural Statistics Service (REST API) Keep? Integrate?
[] find additional dataset for consumption that can be used to calculate demand elasticity over time at the national level
[x] compile data onto two dataframes: one for time-series/national data and the other for geographical data
[x] add geospatial data for visualizations
[x] clean Cal-Main food price data

# Code Organization (what else can be refactored?)
[x] seperate main for app
[x] put streamlit functions into viz.py
[x] put data cleaning functions into data_prep.py
[] testing code 
    - check for date column, lng, lat
    - see if numbers are numerical
    - check for invalid data values in cols
[] test cases

# Visualizations
[x] Create time series data plotting egg prices, stock price
[x] resample time series to monthly
[x] add second y axis for stock prices
[] fix x axis for the time series plot
[x] Create US map with bird flu (modify to streamlit plot?) 
[] Add filters that allow for different time periods on both graphs

Other Considerations
[] Which states are key egg producing states
[] How to get local data for egg prices and consumption
[] Consider whether to include other egg companies or local producers (how to source/aggregate data?)
[] Check the correlation between variables and graph
[] Is there some natural experiment that could allow us to compare the outcome variable (egg prices) with a quasi-experiemntal design?
    [] What would be the counterfactual?
