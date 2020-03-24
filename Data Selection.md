# Data Selection

 ## Foursquare location data

We will need data about different venues in different neighborhoods. In order to get that information, we will use "Foursquare" for the locational information. Foursquare is a famous location data provider with various kinds of  information of the venues and nearby. For example, it will provide venue names, locations, photos, and etc. As a result, the foursquare location platform will be used as the sole data source since all the stated required information can be obtained through the API. 

In the first place, we will get the list of neighborhoods, we then use the Foursquare API to fetch information about venues in each neighborhood.

Specifically, the following information will be gathered.

* Neighborhood's name
* Neighborhood's Latitude and Longitude
* Venue's name
* Venue's Latitude and Longitude

