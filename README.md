## Module 13: Mapping Earthquakes Challenge

### Overview

The objective of this project is to gather earthquake data from the U.S. Geological Survey ("USGS") website and to create interactive maps of earthquakes around the world.

- This data has been extracted and loaded as a GeoJSON file, a type of JSON data specifically designed to hold geographical information. 
- The final map contains the earthquake data represented as circular markers with their size and color corresponding to the magnitude of the earthquake. Each marker also has a popup that displays the magnitude and location of the earthquake. 
- The map also contains multiple viewing layers and information about the earthquakes, which can all be selected using the toggle feature at the top right corner of the website.  

### Resources

- Data Source: Earthquakes GeoJSON, Earthquakes above 4.5mag GeoJSON, Tectonic Plate GeoJSON
- Coding language and librairies: HTML/CSS, JavaScript, Visual Studio, Leaflet 1.7.1, D3.js 6.2.0

### Results

To access the website, please [Click Here](https://bluckoo.github.io/Mapping_Earthquakes_Challenge/).

The map is interactive and the user can select the following from the toggle button:

- Type of view:
  - Streets - daylight map showing a map of the world with the country names;
  - Satellite - satellite view of world map showing the landscape features;
  - Dark - a dark version of the world map.

- Earthquake information:
  - Earthquakes - shows all earthquakes around the world, with a bubble marker whose color and size depends on the magnitude of the earthquake;
  - Tectonic plates - a red overlay indicating the location of the tectonic plates around the world;
  - Major Earthquakes - major earthquakes with a magnitude of 4.5 and above are illustrated as bubbles of different size and color depending on their magnitudes.
  
The toggle elements for earthquake information can each be selected separately or in combination to illustrate the elements.

### Example of Interactive Map Views


1. Street view showing all earthquakes:


<p align="center">
<img width="953" alt="Street view showing all earthquakes" src="https://user-images.githubusercontent.com/82583576/126418327-83da8d69-6f16-42e6-b8c7-5c0fe98c6c86.PNG">
</p>


2. Satellite Street view showing major earthquakes, a popup showing the magnitude & location, and the tectonic plates:


<p align="center">
<img width="949" alt="Staellite view showing major earthquakes and tectonic plates" src="https://user-images.githubusercontent.com/82583576/126418884-a58060e1-7557-405a-8785-da91f1134e14.PNG">
</p>


3. Dark view showing all earthquakes, the tectonic plates and a popup with the magnitude and location of the earthquake.

<p align="center">
<img width="957" alt="Dark view with all earthquakes and tectonic plates" src="https://user-images.githubusercontent.com/82583576/126423812-8dedb9f8-0c1e-45ec-87f8-71cb75dba3f1.PNG">
</p>



This project was very informative - please try the interactive maps and learn more about earthquakes!!
