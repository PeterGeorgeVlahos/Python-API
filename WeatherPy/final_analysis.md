Final Analysis

Part 1 
Weather API

- In the project, I was using a new PIP package, citipy, that randomly generated over 500 cities using 
longitude and latitude coordinates.  After generating these cities, I used OpenWeather API to call 
various weather patterns for that city.  Including, humidity as a %, cloudiness as a %, max wind speed in
miles per hour and maximum annual temperatures.

The second half of the project, using gmap developer, I was able to take the city information from citipy 
and weather data from openweather api and generate a heat map showing the humidity intensity in those cities.  
The exercise also had me look use gmap nearby function to look up hotels in cities I would most like
to vacation based on my preferred weather statistics.  I like it hot, dry and cloudless.   


I took this data with a data frame and used pandas to scatter plot the relationship between latitude
coordinates and the weather data mentioned above.  Below are several plot observations as well as 
linear regression and r value statistical calculation.  

- Plotting and linear regression showed an expected outcome in max temperature. As scatter plots
moved closer to 0 degrees latitude, temperatures increase, at a near 1 r rate.  No discernable 
pattern could be seen or supported by the r value in cloudiness, wind speed or humidity.

- Northern Hemisphere Wind Speed was the most surprising r value of 0.76. Regardless of Latitude
measurement, wind speed was fairly consistent between 0 to 10 mph. 


Part II
Vacation API

- Here is completed attempt to correct my error from Part I creating a new work book using the
citipy code block and creating a new dataframe.

- Cleaned and created a heat map using Latitude and Longitude with humidity was the heat weight.

- To look for an idea vacation spot, I chose cities that have a max temperature over 80 degrees, 
less than 40% cloudiness and less than 50% humidity.

- With the above filters, 10 total cities fit these parameters. All appearing in SouthEast Asia,
India and Australia.  

- And it appears my ideal place to vacation in Australia. 

- I was unable to get the Hotel Marker Labels to work.  


