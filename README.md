Homework #17: Geo-Mapping Homework (d3/Leaflet)

Please access my deployed website via the following link: https://colleen547.github.io/leaflet-challenge/

## Background
![1-Logo](Images/1-Logo.png)
Welcome to the United States Geological Survey or USGS for short! The USGS is responsible for providing scientific data about natural hazards, the health of our ecosystems and environment, and the impacts of climate and land-use change. Their scientists develop new methods and tools to supply timely, relevant, and useful information about the Earth and its processes. As a new hire, you will be helping them out with an exciting new project!

For this project, assume that the USGS is interested in building a new set of tools that will allow them to visualize their earthquake data. They collect a massive amount of data from all over the world daily but lack a meaningful way of displaying it. Visualizing their data will allow them to better educate the public and other government organizations (and hopefully secure more funding..) on issues facing our planet.

### Before You Begin

1. Create a new repository for this project called `leaflet-challenge`. **Do not add this homework to an existing repository**.

2. Clone the new repository to your computer.

3. This project utilizes both **html** and **Javascript**, so be sure to add all the necessary files. These will be the main files to run for analysis. Please use a directory structure similar to the ones used previously; e.g., `static/js`.

4. Be sure to keep your API Key in a separate file and don't push it to GitHub. Remember to update your `.gitignore` accordingly. 

5. Push the above changes to GitHub.


TASK:
Level 1: Basic Visualization
2-BasicMap

The first task is to visualize an earthquake data set.

Get your data set

3-Data

The USGS provides earthquake data in a number of different formats, updated every 5 minutes. Visit the USGS GeoJSON Feed page and pick a data set to visualize. When you click on a data set, for example 'All Earthquakes from the Past 7 Days', you will be given a JSON representation of that data. You will be using the URL of this JSON to pull in the data for our visualization.

4-JSON

Import & Visualize the Data

Create a map using Leaflet that plots all of the earthquakes from your data set based on their longitude and latitude.

Your data markers should use size to indicate the magnitude of the earthquake, and color to indicate the depth of the earthquake. Earthquakes with higher magnitudes should appear larger and earthquakes with greater depth should appear darker in color.

HINT the depth of the earth can be found as the third coordinate for each earthquake.

Include popups that provide additional information about the earthquake when a marker is clicked.

Create a legend that will provide context for your map data.

Your visualization should look something like the map below.

Level 2: More Data (Optional)
5-Advanced

The USGS wants you to plot a second data set on your map to illustrate the relationship between tectonic plates and seismic activity. You will need to pull in a second data set and visualize it along side your original set of data. Data on tectonic plates can be found at https://github.com/fraxen/tectonicplates.

In this step, plot a second data set on our map.

Add optional base maps to choose from as well as separate out our two different data sets into overlays that can be turned on and off independently.

Add layer controls to the map.

CRITERIA FOR SUCCESSFUL COMPLETION:
The final product will be assessed on the following metrics:

Completion of assigned tasks

Visual appearance

Professionalism

Good luck!

Copyright
Trilogy Education Services © 2019. All Rights Reserved.
