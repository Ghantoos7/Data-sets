# Airbnb Listings
This dataset consists of six files with Airbnb rental listings of six cities: Austin, Bangkok, Buenos Aires, Cape Town, Istanbul, and Melbourne. Each row represents a listing with details such as coordinates, neighborhood, host id, price per night, number of reviews, and so on. 

## Other cities

The file names for the other cities are `listings_austin.csv`, `listings_bangkok.csv`, `listings_buenoes_aires.csv`, `listings_cape_town.csv`, and `listings_istanbul.csv`. If you want data on other locations, visit the source of the dataset, [InsideAirbnb](http://insideairbnb.com)

## Data Dictionary

| Column                            | Explanation                                                                                                                                                                                        |
| --------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| id                                | Airbnb's unique identifier for the listing                                                                                                                                                         |
| name                              |                                                                                                                                                                                                    |
| host\_id                          |                                                                                                                                                                                                    |
| host\_name                        |                                                                                                                                                                                                    |
| neighbourhood\_group              | The neighbourhood group as geocoded using the latitude and longitude against neighborhoods as defined by open or public digital shapefiles.                                                        |
| neighbourhood                     | The neighbourhood as geocoded using the latitude and longitude against neighborhoods as defined by open or public digital shapefiles.                                                              |
| latitude                          | Uses the World Geodetic System (WGS84) projection for latitude and longitude.                                                                                                                      |
| longitude                         | Uses the World Geodetic System (WGS84) projection for latitude and longitude.                                                                                                                      |
| room\_type                        |                                                                                                                                                                                                    |
| price                             | daily price in local currency. Note, $ sign may be used despite locale                                                                                                                             |
| minimum\_nights                   | minimum number of night stay for the listing (calendar rules may be different)                                                                                                                     |
| number\_of\_reviews               | The number of reviews the listing has                                                                                                                                                              |
| last\_review                      | The date of the last/newest review                                                                                                                                                                 |
| calculated\_host\_listings\_count | The number of listings the host has in the current scrape, in the city/region geography.                                                                                                           |
| availability\_365                 | avaliability\_x. The availability of the listing x days in the future as determined by the calendar. Note a listing may be available because it has been booked by a guest or blocked by the host. |
| number\_of\_reviews\_ltm          | The number of reviews the listing has (in the last 12 months)                                                                                                                                      



The data for each city was compiled by [InsideAirbnb](http://insideairbnb.com) between October and November 2021.

[Source](http://insideairbnb.com/get-the-data.html) and [license](https://creativecommons.org/licenses/by/4.0/) of dataset. 

---------------------------

## Don't know where to start?

**Challenges are brief tasks designed to help you practice specific skills:**

- 🗺️ **Explore**: What is the distribution of prices across a city's neighborhoods? How does it change when you segment it further by `room_type`?
- 📊 **Visualize**: Create a map with a dot for each listing in a city and add a color scale based on `price` on the dots.
- 🔎 **Analyze**: How do listings that require a minimum stay of a week or longer differ from those that don't?

**Scenarios are broader questions to help you develop an end-to-end project for your portfolio:**

An international real estate firm has hired you to research professional hosting on Airbnb. These are hosts that have multiple listings, make considerable income from their listings, and often manage teams to operate their listings. Examples include property managers and hospitality business owners.

Using the data from all six cities, you'll have to infer listings by professional hosts based on the distribution 
of `calculated_host_listings_count`. The lead consultant is interested in whether you can identify trends across listings operated by inferred professional hosts, as well as an estimation of the percentage of listings on Airbnb operated by professional hosts.

You will need to prepare a report that is accessible to a broad audience. It will need to outline your motivation, analysis steps, findings, and conclusions.
