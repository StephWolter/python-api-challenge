# python-api-challenge
Module 6 Challenge
    
## Setup

Gather data to use with api keys.  Analyze the data for world weather and hotels.

### File Structure:
     
     * Repository "python-api-challenge"
         * VacationPy.ipynb
         * WeatherPy.ipynb
         * Folder "Output Data"
             * fig1.png, fig2.png, fig3.png, fig4.png
             * cities.csv
         * gitignore.py 
         * ReadMe.md

## WeatherPy
    
    * Set up dependencies and imports
    * Create a list by gathering cities by Latitude and Longitude 
    * Create the url, call for metadata of the cities gathered, parse through the json data
    * Create a dataframe of the cities and their: Latitude, Longitude, Max Temp, Humidity, Cloudiness, Wind Speed, Country, Date
    * Check the count of the dataframe and view the data
    * Export dataframe to a csv file in the Output Data folder
    * Create a number of scatterplots
        * Latitude vs Max Tem
        * Latitude vs Humidity
        * Latitude vs Cloudiness
        * Latitude vs Wind Speed
    * Create a function for linear regression 
    * Create dataframes of just Northern and Southern data
    * Create scatterplots with linear regression lines of
        * Northern
            * Latitude vs Max Tem
            * Latitude vs Humidity
            * Latitude vs Cloudiness
            * Latitude vs Wind Speed
        * Southern
            * Latitude vs Max Tem
            * Latitude vs Humidity
            * Latitude vs Cloudiness
            * Latitude vs Wind Speed
    * Draw conclusions
    
    
    
## VacationPy

    * Set up dependencies and imports 
    * Gather data from the csv file from the WeatherPy
    * Create dataframe
    * Create a map that displaying a point for cities in the dataframe with dot size corresponding to Humidity
    * Narrow the number of cities displayed to my personal preference; somewhere between 25 degrees F to 90 degrees F
    * Drop rows with null values
    * Create a copy of the dataframe and add a column to be populated 
    * Using the api key and building a url, gather hotel data within a 10 km radius.
    * If no such hotel exists, display message to that effect
    * Populate the created dataframe with this information
    * Modify the plot on the map to display hotel information along with country and city.
    
    
    
    
    
    
    
    
    
    
    
    
