# World_Weather_Analysis/map/travel

## Weather_Database
- Generates 2,000 random latitudes and longitudes and retrieves the nearest city. Gathers Weather data from OpenWeatherMap API. Stores it into a DataFrame and outputs the DataFrame as a csv file.

## Vacation_Search
- Gets input from customers of their weather preferences (using weather_database's csv file as data source). Uses thoes preferences to narrow down potential travel destinations and nearby hotels. Shows pop-up markers of the locations.

## Vacation_Itinerary
- Uses the Google Directions API to create a travel itinerary that shows the route between four cities chosen from the customer’s possible travel destinations. Shows pop-up markers of each city on the itinerary.
