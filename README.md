# python-api-challenge
Requirement 1: Create Plots to Showcase the Relationship Between Weather Variables and Latitude
To fulfill the first requirement, you'll use the OpenWeatherMap API to retrieve weather data from the cities list generated in the starter code. Next, you'll create a series of scatter plots to showcase the following relationships:

Latitude vs. Temperature

Latitude vs. Humidity

Latitude vs. Cloudiness

Latitude vs. Wind Speed

Requirement 2: Compute Linear Regression for Each Relationship
To fulfill the second requirement, compute the linear regression for each relationship. Separate the plots into Northern Hemisphere (greater than or equal to 0 degrees latitude) and Southern Hemisphere (less than 0 degrees latitude). You may find it helpful to define a function in order to create the linear regression plots.

You should create the following plots:

Northern Hemisphere: Temperature vs. Latitude

Southern Hemisphere: Temperature vs. Latitude

Northern Hemisphere: Humidity vs. Latitude

Southern Hemisphere: Humidity vs. Latitude

Northern Hemisphere: Cloudiness vs. Latitude

Southern Hemisphere: Cloudiness vs. Latitude

Northern Hemisphere: Wind Speed vs. Latitude

Southern Hemisphere: Wind Speed vs. Latitude

After each pair of plots, explain what the linear regression is modeling. Describe any relationships that you notice and any other findings you may uncover.

art 2: VacationPy
In this deliverable, you'll use your weather data skills to plan future vacations. Also, you'll use Jupyter notebooks, the geoViews Python library, and the Geoapify API.

The code needed to import the required libraries and load the CSV file with the weather and coordinates data for each city created in Part 1 is provided to help you get started.

Your main tasks will be to use the Geoapify API and the geoViews Python library and employ your Python skills to create map visualizations.

To succeed on this deliverable of the assignment, open the VacationPy.ipynb starter code and complete the following steps:

Create a map that displays a point for every city in the city_data_df DataFrame as shown in the following image. The size of the point should be the humidity in each city.
Narrow down the city_data_df DataFrame to find your ideal weather condition. For example:

A max temperature lower than 27 degrees but higher than 21

Wind speed less than 4.5 m/s

Zero cloudiness

note
Feel free to adjust your specifications but make sure to set a reasonable limit to the number of rows returned by your API requests.

Create a new DataFrame called hotel_df to store the city, country, coordinates, and humidity.

For each city, use the Geoapify API to find the first hotel located within 10,000 meters of your coordinates.


Requirements
The requirements for "Part 1: WeatherPy" are the following
Create Plots to Showcase the Relationship Between Weather Variables and Latitude (30 points)
Use the OpenWeatherMap API to retrieve weather data from the cities list generated in the started code (10 points)

Create a scatter plot to showcase the relationship between Latitude vs. Temperature (5 points)

Create a scatter plot to showcase the relationship between Latitude vs. Humidity (5 points)

Create a scatter plot to showcase the relationship between Latitude vs. Cloudiness (5 points)

Create a scatter plot to showcase the relationship between Latitude vs. Wind Speed (5 points)

Compute Linear Regression for Each Relationship (40 points)
Linear regression scatter plot for Northern Hemisphere: Temperature (C) vs. Latitude (5 points)

Linear regression scatter plot for Southern Hemisphere: Temperature (C) vs. Latitude (5 points)

Linear regression scatter plot for Northern Hemisphere: Humidity (%) vs. Latitude (5 points)

Linear regression scatter plot for Southern Hemisphere: Humidity (%) vs. Latitude (5 points)

Linear regression scatter plot for Northern Hemisphere: Cloudiness (%) vs. Latitude (5 points)

Linear regression scatter plot for Southern Hemisphere: Cloudiness (%) vs. Latitude (5 points)

Linear regression scatter plot for Northern Hemisphere: Wind Speed (m/s) vs. Latitude (5 points)

Linear regression scatter plot for Southern Hemisphere: Wind Speed (m/s) vs. Latitude (5 points)

The requirements for "Part 2: VacationPy" are the following (30 points)
Create a map that displays a point for every city in the city_data_df DataFrame (5 points)

Narrow down the city_data_df DataFrame to find your ideal weather condition (5 points)

For each city in the hotel_df DataFrame, use the Geoapify API to find the first hotel located within 10,000 metres of your coordinates (10 points)

Add the hotel name and the country as additional information in the hover message for each city in the map. (10 points)
