## ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png) Project 2: Site Selection Analysis for 7-Eleven in Bangkok | README


---

### Introduction

Bangkok’s rapid urbanization, particularly along mass transit lines, has transformed consumer behavior and shopping preferences. As residents increasingly prioritize convenience and shorter commute times, there has been significant migration toward central Bangkok’s SkyTrain and subway corridors which caused the increasing number of condominiums around each station. In response to ongoing urbanization in Bangkok, players in the modern trade industry, especially convenience stores, have been competing for market share within the segment. Nevertheless, competition is stiffening from other segments, in particular from discount stores which are opening smaller branches that are very similar to convenience stores. Examples of these include Big C Mini, Lotus’s go fresh and Top’s daily, these reduced-sized discount stores are now fighting over much the same customer base as convenience stores.Looking at the latest data on the amount of each major convenient stores outlets in ThailandThe market leader in this segment is 7-Eleven, which operates 72% of all convenience stores in Thailand. 7-Eleven is followed in importance by Lotus’s go fresh (10% of the market), Big C Mini (7%) and CJ More (5%).

---

### Problem Statement

While 7-Eleven maintains its position as Thailand’s largest retail chain, several underserved areas remain in this evolving urban landscape. This presents both an opportunity and challenge: how can 7-Eleven strategically expand its footprint to capture these underserved markets before competitors, while maintaining its competitive advantage in convenience retail ?

---

### Procedures

- Categorized Bangkok districts into zones based on land use criteria from the Department of City Planning and Urban Development of Bangkok Metropolitan.
- Mapped 7-Eleven branches and housing data, focusing on condominium properties in each Bangkok zone.
- Analyze the number of 7-Eleven branches near condominiums to identify underserved areas.


---
### Data Dictionary

Here is the table of data dictionary:

| Column                    | Data Type     | Description                                                                       |
|---------------------------|---------------|-----------------------------------------------------------------------------------|
| id	                    | int	        | ID of selling item                                                                |
| province	                | string        | province name: this dataset only includes Bangkok, Samut Prakan and Nonthaburi    |
| district	                | string	    | district name                                                                     |
| subdistrict	            | string	    | subdtistrict name                                                                 |
| address	                | string	    | address e.g. street name, area name, soi number                                   |
| property_type	            | string	    | type of the house: Condo, Townhouse, or Detached House                            |
| total_units	            | float	        | the number of rooms/houses that the condo/village has                             |
| bedrooms	                | int	        | the number of bedrooms                                                            |
| baths	                    | int	        | the number of baths                                                               |
| floor_area	            | float	        | total area of inside floor                                                        |
| floor_level	            | int	        | floor level of the room                                                           |
| land_area	                | float	        | total area of the land                                                            |
| latitude	                | float	        | latitude of the house                                                             |
| longitude	                | float	        | longitude of the house                                                            |
| nearby_stations	        | int	        | the number of nearby stations (within 1km)                                        |
| nearby_station_distance	| list	        | list of (station name, distance[m]).                                              |
| nearby_bus_stops	        | int	        | the number of nearby bus stops                                                    |
| nearby_supermarkets	    | int	        | the number of nearby supermarkets                                                 |
| nearby_shops	            | int	        | the number of nearby shops                                                        |
| year_built	            | int	        | year built                                                                        |
| month_built	            | string	    | month built: January-December                                                     |
| price	                    | float         | selling price                                                                     |


