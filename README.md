

# Travel Cost Comparison Map

## Overview
This interactive map simplifies the decision-making process for travelers by comparing accommodation costs in various locations. It visualizes the price differences between Airbnb options and hotels, helping users choose the most cost-effective solution based on their destination.

## Methodology
Using `pandas`, a powerful data manipulation library in Python, we processed a dataset containing information on Airbnb and hotel prices along with their geographic coordinates. We calculated the average hotel price and compared it with Airbnb listings, categorizing them into "Private Rooms" and "Entire Homes/Apartments."

To match Airbnb listings with nearby hotels, we utilized latitude and longitude data. A specific threshold radius was set to determine "closeness," ensuring that comparisons were locationally relevant. This geospatial analysis was crucial in accurately pairing accommodations for price comparison.

## Interactive Map Creation
The interactive map was generated with `folium`, a Python library that enables the creation of Leaflet.js maps. With `folium`, we plotted each accommodation as a marker on the map, employing different icons and colors to distinguish between hotels, private rooms, and entire homes. Clickable popups attached to each marker provide price details, allowing for easy on-map comparisons.

## Usage
Travelers can interact with the map to explore accommodation options in their chosen area. By considering both location and price, users can make informed decisions that align with their budget and preferences.

## Tools Used
- Python: For data analysis and processing.
- Pandas: To manipulate the dataset and perform calculations.
- Folium: To create the interactive map with geospatial data.
- GitHub Pages: To host the interactive map, making it accessible to users.

---

