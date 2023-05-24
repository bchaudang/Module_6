# Module_6
Python API Challenge 
--------------------------------------------------------
There were two parts to this challenge, WeatherPy and VacationPy.
---------------------------------------------------------

The first part of the assignment, WeatherPy, was relatively straight forward and used alot of the skills and code that was used in the previous assignment, considering the majority of this part was to create scatter plots and linear regression.
Howver, the second part of the assignment, VacationPy, I ran into quite a few roadblocks and utilized askBCS Learning Assistants, a tutor session, our course TA, as well as other classmates to help with some issues I ran into. 
For one, I was unable to retrieve any data for the hotels, my data was coming up with "no hotels found", which was extremely frustrating. I had attempted multiple different codes with aid. At the end, it was a simple error in spelling, which would have saved me hours of combing through my code. A spelling error in which none of the assistance above caught either. Overall, the assignment defintely taught me alot, especially that minor things such as an extra letter, a comma, or even a bracket are detrimental. 
Another issue I was encountering was that the csv file contained max temperatues using the Kelvin unit of measurement, and was running into issues changing the unit of measurement to the metric system. But again, with the help of an askBCS Learning Assisstant, I was able to rectify the issue.

---------------------------------------------------------

For the first part of the assignment, WeatherPy, the task was to analyze the weather conditions of over 500 cities of varying distances, selected randomly, using the OpenWeatherMap API to retieve the data.
From there, the requirements of the assignment stated to create scatter plots, and showcase the relationships bewteen the following categories:

- Latitude vs. Temperature
- Latitude vs. Humidity
- Latitude vs. Cloudiness
- Latitude vs. Wind Speed

(As shown below)
![Fig1](https://github.com/bchaudang/Module_6/assets/130397259/cca7e13c-7e37-448d-bcf2-300b02c8f546)
![Fig2](https://github.com/bchaudang/Module_6/assets/130397259/4ed22c07-fa3e-4506-a936-8e014958aa7b)
![Fig3](https://github.com/bchaudang/Module_6/assets/130397259/e23f8dfb-dcac-445d-a078-643eaae51bdc)
![Fig4](https://github.com/bchaudang/Module_6/assets/130397259/0515b0a8-c6ed-4446-bde4-abb7a9c73159)

Then, the task was to compute a linear regression for each relationship, seperated by Northern and Southern Hemispheres, for the following:

- Northern Hemisphere: Temperature vs. Latitude
- Southern Hemisphere: Temperature vs. Latitude
- Northern Hemisphere: Humidity vs. Latitude
- Southern Hemisphere: Humidity vs. Latitude
- Northern Hemisphere: Cloudiness vs. Latitude
- Southern Hemisphere: Cloudiness vs. Latitude
- Northern Hemisphere: Wind Speed vs. Latitude
- Southern Hemisphere: Wind Speed vs. Latitude

(As shown below)
![Fig5](https://github.com/bchaudang/Module_6/assets/130397259/a66d8441-470d-4939-9c2c-0c5562dd2498)
![Fig6](https://github.com/bchaudang/Module_6/assets/130397259/356ded2a-9253-49f6-a10e-bc7eab89f402)
![Fig7](https://github.com/bchaudang/Module_6/assets/130397259/7c2306ae-5158-4168-a478-87137b042eb6)
![Fig8](https://github.com/bchaudang/Module_6/assets/130397259/28cb4001-8a91-419e-ad1d-9cfad7c6c614)
![Fig9](https://github.com/bchaudang/Module_6/assets/130397259/6b2a6245-eae3-42a6-b4fb-ee5815ba61d8)
![Fig10](https://github.com/bchaudang/Module_6/assets/130397259/cbf5a224-c615-45f2-baf9-e8af01127f45)
![Fig11](https://github.com/bchaudang/Module_6/assets/130397259/993888ee-e078-41f0-be9b-011a10cc2776)
![Fig12](https://github.com/bchaudang/Module_6/assets/130397259/fd5f1c31-ad5c-438d-bb62-06229c93a13d)

---------------------------------------------------------

For the second part of the assignment, VacationPy, the task was to retrieve data using the Geoapify API to create a map that displayed a point for every city in the dataframe, with the size point set as the humidity for that corresponding city. Another detail requirement was that when hovering your mouse over the selected city, a box should appear stating the latitude, longitude, name of the city as well as the humidity.

(As shown below)
![bokeh_plot (1)](https://github.com/bchaudang/Module_6/assets/130397259/5243cb91-f5f1-4afe-b7a2-37e1eab569a6)

The second task of VacationPy, was to then clean the dataframe and produce a new one with ideal weather conditions based on the following criteria:
- A max temperature lower than 27 degrees but higher than 21
- Wind speed less than 4.5 m/s
- Zero cloudiness

Based on the cities with ideal weather conditions, using Geoapify API, to find the nearest hotel located within 10,000 meters (10 KM) radius of each city. A requirement was also to include a hover box would appear with the latitude, longitude, city, country, humidity and hotel name.

(As shown below)
![bokeh_plot](https://github.com/bchaudang/Module_6/assets/130397259/831d267e-0e00-43d5-9eba-88abd314c56b)

---------------------------------------------------------


