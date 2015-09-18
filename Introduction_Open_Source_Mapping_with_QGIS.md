#Introduction to Open-Source Mapping with QGIS

##Summary
A one-day course covering the basics of geospatial analysis with open-source tools, including loading, visualizing, and gaining insight from spatial data for operational decision making. The course involves hands-on exercises with open data to answer real-world problems.

##Target Audience
City employees of all levels with some familiarity with geospatial information systems (GIS) and work with spatial data in either proprietary or open-source platforms.

##Course Overview
This course introduces participants to the essential elements of the QGIS open source geospatial information system (GIS) application. Topics include how to install and configure the application, as well as loading raster and vector data into QGIS and styling the data for analysis and visualization. Additional topics include spatial joins, buffering features, and other spatial analysis operations, including generating heatmaps and other spatial visualizations. This course is designed for participants with a background in GIS who are interested in using the QGIS platform to work with city data.

##Goals
+ Review the fundamentals of analyzing and visualizing spa.al data
+ Introduce basic spa.al opera.ons in QGIS
+ Provide a real-world scenario for using QGIS
+ Demonstrate how to connect to a spa.al database (PostgreSQL/PostGIS)

##Key Takeaways
+ Participants will understand how to load and visualize data in QGIS
+ Participants will understand how to perform basic spa.al analysis tasks in QGIS
+ Participants will understand how to work with data stored in a PostgreSQL/PostGIS database

##Schedule
+ Introduction (9:00 - 9:15)
+ Overview of GIS (9:15 - 9:25)
	+ GIS review
	+ Vector types
		+ Point
		+ Line
		+ Polygon
	+ Raster types
		+ Base maps
		+ Images
	+ Projections
	+ Geocoding
	+ Overview of Geospatial Information Systems (GIS)
	+ Overview of geodatabases
	+ Data formats
		+ [CSV](https://en.wikipedia.org/wiki/Comma-separated_values)
		+ [JSON](https://en.wikipedia.org/wiki/JSON)
		+ [GeoJSON](http://geojson.org/)
		+ [XML](https://en.wikipedia.org/wiki/XML)/[KML](https://en.wikipedia.org/wiki/Keyhole_Markup_Language)
+ Overview of QGIS: the Good, the Bad, and the Buggy (9:25 - 9:35)
+ Loading Data into QGIS and Styling (9:35 - 9:50)
	+ Adding base maps
	+ Adding shapefile
	+ Styling layers
	+ Adding data labels
	+ Exercise 1: Style the polygons and labels in the NYC boroughs shapefile 
+ Break (9:50 - 10:00)
+ Loading CSV data into QGIS and styling (10:00 - 10:40)
	+ Load CSV data
	+ Select [Coodinate Reference System](https://en.wikipedia.org/wiki/Spatial_reference_system)
	+ Introduction to [Spatial Reference Identifiers (SRIDs)](https://en.wikipedia.org/wiki/SRID)
	+ Filtering data
	+ Saving CSV data as shapefile
	+ Exercise 2: In your small groups, style the 311 data for your assigned borough
+ Loading data from a PostgreSQL/PostGIS spatial database (10:40 - 10:50)
+ Break (10:50 - 11:00)
+ Creating Heat Maps in QGIS (11:00 - 12:00) 
	+ Introduction to heat maps
	+ Enabling the Heatmap plug-in
	+ Creating a heat map in QGIS
	+ Styling a heat map in QGIS
	+ Exercise 3: In your group, create a heat map of 311 Service Requests for your assigned borough
+ Lunch (12:00 - 1:00)
+ Spatial analysis with QGIS (1:00 - 1:50)
	+ Joining data in QGIS
	+ Buffering features
	+ Exercise 4: Calculate the number of bicycle injuries that occur on or near bike paths in NYC
	+ Working with SRID map units
	+ Reprojecting data
	+ Select by location
	+ Using the Spatial Query plug in
+ Break (1:50 - 2:00)
+ Spatial analysis with PostGIS (2:00 - 2:50) 
	+ Introduction to SQL
	+ Spatial joins with SQL
	+ Buffering in PostGIS SQL
	+ Geometry vs Geography
+ Break (2:50 - 3:00)
+ Group exercise creating a map in QGIS (3:00 - 3:50)
	+ Exercise 5: Create a heat map of bicyclist injuries on and off bike paths in your assigned borough
	+ Group presentations
+ Wrap-up and course evaluations (3:50 - 4:00)
+ Dismissal (4:00)

##Exercise Descriptions
###Exercise 1: Style the polygons and labels in the NYC boroughs shapefile 
+ Task to Participants
	+ Style data from the NYC boroughs shapefile, including the polygon colors, label font, and placement
+ Desired outcomes
	+ Participants practice styling data in QGIS

###	Exercise 2: In your small groups, style the 311 data for your assigned borough
+ Task to Participants
	+ Filter the 311 data for your borough and create a simple map showing the locations
	+ Feel free to play with the styling of the data to make it clear, concise, and visually compelling
+ Desired outcomes
	+ Participants practice styling a point file in QGIS
	+ Participants become more comfortable with the QGIS user interface

###Exercise 3: In your group, create a heat map of 311 Service Requests for your assigned borough
+ Task to Participants
	+ Create a heat map of 311 complaints in your borough
	+ Where are the complaints concentrated? 
	+ Adjust the seqngs and create multiple maps
	+ Which work the best?
+ Desired outcomes
	+ Participants practice creating heat maps in QGIS
	+ Participants gain experience manipulating settings in the Heatmap plug-in

###Exercise 4: Calculate the number of bicycle injuries that occur on or near bike paths in NYC
+ Task to Participants
	+ Calculate the number of bicycle injuries that occur on or near bike paths in NYC using the point shapefile of injury locations and the line shapefile of bike paths in NYC
+ Desired outcomes
	+ Participants practice 

###Exercise 5: Create a heat map of bicyclist injuries on and off bike paths in your assigned borough
+ Task to Participants
	+ Working on your own or in groups, create for your assigned borough
		+ A heat map of bicycle injuries occurring on or near bike paths		+ A heat map of bicycle injuries occurring away from bike paths	+ Prepare to present your (rough) spatial analysis to the class
+ Desired outcomes
	+ 