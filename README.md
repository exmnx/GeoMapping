# GeoMapping
This was created for fun to help with travel plans I had. The map graphs all locations on the data sheet, and creates 1 mile circles for every ward listed per prefecture using latitude and longitude. 

**Excel Sheet:**
The excel sheet will be updating. The geomap using folium only includes the first sheet of the excel workbook. The sheets are as listed below:
  - Trip Overview: Main data that includes region, prefectures, place name, GPS location, time opened, time closed, Closed on what days, price, currency, price in
                   usd, price in yen, included in the osaka amazing pass, type of place, located in, ward, time spend, total cost, hours of operation notes and notes
  - Location Sheet: Shows a pivot table based on the trip overview data. Groups name of place based on columns: Wards and Located in
  - Trip Itinerary: The trip itinerary showing how many nights and days staying
  - Habitation: Lists Possible places to stay  
  - Prices: a hypothesized price sheet 
  - Other: Items needed while there

**.ipynb File:**
This shows the python code used to create the map. 
- Includes new columns added such as latitude, and longitude. If the Name of Place had errors with the geolocator, a nearby latitude and longitude were added
  in respect to the Nearby alternative column created to resolve this issue. This column is created via manual input. 
