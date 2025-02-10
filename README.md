# **Project Title**: Location Route Analysis

## **Project Goal**: 
To map and visualize the distribution of sponsored McDonald's locations in Phoenix, Arizona for Pokemon GO using crowdsourced and verified location data. This visualization will enable trainers to easily identify high-concentration areas for optimized route planning during sponsored events.

## **Project Background**:
In December, [Pokémon GO & McDonald's](https://pokemongolive.com/post/mcdonalds-us/) announced a sponsorship featuring exclusive in-game Raids and Lure Modules at participating McDonald's locations. The lack of clarity regarding featured Pokémon during the one-hour event windows & the unexpected appearance of the Legendary Kyurem highlighted the need for better information sharing among players. This project addresses this need for Pokémon GO trainers in Phoenix, Arizona with a readily accessible resource to identify participating McDonald's locations and plan efficient routes.

## **Project Breakdown**:
The project followed a multi-stage process:

- Data Collection:  McDonald's locations in Phoenix, Arizona participating in the Pokémon GO sponsorship were crowdsourced using Niantic's Campfire application and associated community resources.  The initial data consisted of city and cross-street information, lacking precise addresses.

- Data Verification and Cleaning: The raw data was cleaned and verified using Excel.  Each location was cross-referenced with Campfire's map, filtered by Gym locations, to confirm its status as an active raid location within Pokémon GO. This step ensured the accuracy of the data by excluding non-raid locations (e.g., PokéStops).

- Address and Coordinate Acquisition: Verified raid locations were cross-referenced with Google Maps to obtain their precise street addresses.  Longitude and latitude coordinates were also extracted for each location, enabling accurate map visualization.

- Map Generation and Visualization: The compiled data, including addresses and coordinates, was used to generate an interactive map using Python and the Folium library.  This map visually represents the distribution of sponsored McDonald's locations, allowing players to easily identify clusters and plan their routes.

- Deployment and Sharing: The interactive map will be hosted and shared with the Arizona Pokémon GO community, providing a valuable tool for route optimization during sponsored event dates.

## **Conclusion**
This project's adaptable design allows for easy expansion to include future sponsored locations. With Niantic's announcements of partnerships with retailers like [Best Buy, GameStop, Target](https://pokemongolive.com/post/tcg-prismatic-evolutions?hl=en), and [Walmart](https://pokemongolive.com/post/walmart-us-partnership), the existing framework can be readily updated with new location data. 
