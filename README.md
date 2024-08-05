# python_api_challenge
Module 6 Challenge- APIs
User: Lauren Graves, laureng97

Project Name: Module 6 Challenge- API's; python_api_challenge
Contributers: Molly Fox, classmate that assisted with unit specification for WeatherPy. Expert Learning Assistant- for code debugging and overall structure. Base code provided by BootCamp.

File Information:
This repository contains a folder labeled "WeatherPy". Within this folder there are two separate code files, "WeatherPy (jupyter source filed)" and "VacationPy (jupyter source file)". Both of these code files contain the code written to analyze data for weather among the selected cities, and ideal vacation spots based on the weather data gathered. Within the "WeatherPy" folder, there is an additional folder labeled "output_data", this will contain my csv file "cities" and four figures that were created by the "WeatherPy" code file. 



Overview: 
Data's true power is its ability to definitively answer questions. So, let's take what you've learned about Python requests, APIs, and JSON traversals to answer a fundamental question: "What is the weather like as we approach the equator?"
Now, we know what you may be thinking: “That’s obvious. It gets hotter.” But, if pressed for more information, how would you prove that?

Requirements: 
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
