Homework #17: Geo-Mapping Homework (d3/Leaflet) - **Visualizing Data with Leaflet**

Please access my deployed website via the following link: https://colleen547.github.io/leaflet-challenge/

- - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - -

## Background
![1-Logo](Images/1-Logo.png)
Welcome to the United States Geological Survey or USGS for short! The USGS is responsible for providing scientific data about natural hazards, the health of our ecosystems and environment, and the impacts of climate and land-use change. Their scientists develop new methods and tools to supply timely, relevant, and useful information about the Earth and its processes. As a new hire, you will be helping them out with an exciting new project!

For this project, assume that the USGS is interested in building a new set of tools that will allow them to visualize their earthquake data. They collect a massive amount of data from all over the world daily but lack a meaningful way of displaying it. Visualizing their data will allow them to better educate the public and other government organizations (and hopefully secure more funding..) on issues facing our planet.

### Before You Begin

1. Create a new repository for this project called `leaflet-challenge`. **Do not add this project to an existing repository**.

2. Clone the new repository to your computer.

3. This project utilizes both **html** and **Javascript**, so be sure to add all the necessary files. These will be the main files to run for analysis. Please use a directory structure similar to previously used; e.g., `static/js`.

4. IMPORTANT: Keep your API Key in a separate file and don't push it to GitHub. Remember to update your `.gitignore` accordingly. 

5. Push the above changes to GitHub.

## Required Task

### Level 1: Basic Visualization

![2-BasicMap](Images/2-BasicMap.png)

The first task is to visualize an earthquake data set.

1. **Get data set**

   ![3-Data](Images/3-Data.png)

   The USGS provides earthquake data in several different formats, updated every 5 minutes. Visit the [USGS GeoJSON Feed](http://earthquake.usgs.gov/earthquakes/feed/v1.0/geojson.php) page and pick a data set to visualize. When you click on a data set, for example, 'All Earthquakes from the Past 7 Days', you will be given a JSON representation of that data. You will be using the URL of this JSON to pull in the data for the visualization.

   ![4-JSON](Images/4-JSON.png)

2. **Import & Visualize the Data**

   Create a map using Leaflet that plots all of the earthquakes from the data set based on their longitude and latitude.

   * The data markers should use size to indicate the earthquake's magnitude and color to indicate the earthquake's depth. Earthquakes with higher magnitudes should appear larger and earthquakes with greater depth should appear darker in color.

   * **HINT:** The depth of the earth can be found as the third coordinate for each earthquake.

   * Include popups that provide additional information about the earthquake when clicking a marker.

   * Create a legend that will provide context for the map data.

   * The visualization should look something like the map below.

- - -

### Level 2: More Data (Advanced)

![5-Advanced](Images/5-Advanced.png)

The USGS wants to plot a second data set on the map to illustrate the relationship between tectonic plates and seismic activity. You will need to pull in a second data set and visualize it alongside the original data set. Data on tectonic plates can be found at <https://github.com/fraxen/tectonicplates>.

In this step you are going to..

* Plot a second data set on our map.

* Add several base maps to choose from as well as separate out our two different data sets into overlays that can be turned on and off independently.

* Add layer controls to our map.

- - -

### SUCCESS CRITERIA

* Completion of assigned tasks

* Visual appearance

* Professionalism


### Copyright

Trilogy Education Services © 2019. All Rights Reserved.
