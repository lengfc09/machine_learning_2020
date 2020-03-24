# Data Selection

 ## Foursquare location data

We will need data about different venues in different neighborhoods. In order to get that information, we will use "Foursquare" for the locational information. Foursquare is a famous location data provider with various kinds of  information of the venues and nearby. For example, it will provide venue names, locations, photos, and etc. As a result, the foursquare location platform will be used as the sole data source since all the stated required information can be obtained through the API. 

In the first place, we will get the list of neighborhoods, we then use the Foursquare API to fetch information about venues in each neighborhood.

Specifically, the following information will be gathered.

* Neighborhood's name
* Neighborhood's Latitude and Longitude
* Venue's name
* Venue's Latitude and Longitude

## Longitude and Latitude Data

We need geo-locational information about that specific borough and the neighborhoods in that borough. It is "Scarborough" in Toronto. The neighborhood data required will be:

1. Latitude and longitude for the location
2. School Ratings
3. House Prices (Median)

The latitude and longitude data can be gathered using the previous project. The location data of Scarborough would be like:

| Postalcode | Borough | Neighborhood | Latitude                                        | Longitude |            |
| :--------- | :------ | :----------- | :---------------------------------------------- | :-------- | ---------- |
| 0          | M1B     | Scarborough  | Rouge, Malvern                                  | 43.811650 | -79.195561 |
| 1          | M1C     | Scarborough  | Highland Creek, Rouge Hill, Port Union          | 43.785605 | -79.158701 |
| 2          | M1E     | Scarborough  | Guildwood, Morningside, West Hill               | 43.765690 | -79.175299 |
| 3          | M1G     | Scarborough  | Woburn                                          | 43.768216 | -79.217610 |
| 4          | M1H     | Scarborough  | Cedarbrae                                       | 43.769608 | -79.239440 |
| 5          | M1J     | Scarborough  | Scarborough Village                             | 43.743085 | -79.232172 |
| 6          | M1K     | Scarborough  | East Birchmount Park, Ionview, Kennedy Park     | 43.726260 | -79.263670 |
| 7          | M1L     | Scarborough  | Clairlea, Golden Mile, Oakridge                 | 43.713213 | -79.284910 |
| 8          | M1M     | Scarborough  | Cliffcrest, Cliffside, Scarborough Village West | 43.723575 | -79.234976 |
| 9          | M1N     | Scarborough  | Birch Cliff, Cliffside West                     | 43.696690 | -79.260069 |



