# python_api_challenge

## Description
_Module 6 Challenge - University of Adelaide - Data Analytics BootCamp_

Welcome to my analysis of whether the weather gets hotter as we approach the equater. 

The analysis was performed using pandas and matplotlib.

The WeatherPY analyses the weather conditions based on latitude of a random sample of world cities. It supports the weather being hotter closer to the equater you are, but humdity, cloudiness and wind speed is not impacted by latitude.

While the VacationPY determines 10 possible future vacations based on my preferred weather conditions as follows:
- A maximum temperature lower than 27 degrees but higher than 18;
- Humidity below 45%
- Wind speed below 10 m/s
- Cloudiness below 50%

## Details on coding used
_WeatherPY_

I was provided with base source code to utilise that included the relevant libraries.
The code first takes a sample of cities across the world. Then using the weather data (from the OpenWeatherMap API) relevant to those cities, I then created plots to showcase the relationship between the weather variables and latitude of the cities.

_VacationPY_

I was provided with base source code to utilise that included the relevant libraries.
The cities data from the WeatherPy analysis was used to create a map that displayed each city.

Code was written to then determine my possible future vacations based on the above criteria with the responses drawn on a new map, including the first hotel name (where found).

More than half of my cities proposed did not have hotels found in the search.  This could be due to the spelling of city names used by citipy compared to geoapify. In future updates to this code, there could be datamatching of the cities to format them consistently.

## How to Install and Run the Project

Please clone the repository to your local drive and then run via Jupyter or Visual Studio Code.
Note that you will get different results from those currently included in the outputs folder, due to the nature of the WeatherPY code (see Details on coding used)

## How to Use the Project

This project can be used to find some different places for a holiday destination based on your desired weather outcomes.

## Credits

Code used was drawn from in class and google searches to find why code wasn't working.  

Specific useful sites
- The code used for the function was sourced from https://www.w3schools.com/python/python_ml_linear_regression.asp
- Python time Module - https://www.programiz.com/python-programming/time
- Colouring scatter plots - https://www.machinelearningplus.com/plots/python-scatter-plot/
- How to write a good readme file - https://www.freecodecamp.org/news/how-to-write-a-good-readme-file/




