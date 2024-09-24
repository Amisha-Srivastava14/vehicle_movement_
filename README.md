# vehicle_movement_
DEPLOYMENT LINK- https://66f2dd8ce2000e05e177c478--glistening-kleicha-7e3a91.netlify.app/


#Project Overview
This project is a web application that demonstrates real-time vehicle movement on a map using the Leaflet.js library and OpenStreetMap. The application simulates a vehicle moving along a predefined route, with the user controlling the movement by clicking a "Start" button.

#Features
Interactive Map: Displays a map using OpenStreetMap.
Real-Time Vehicle Movement: A car icon moves along a predefined route on the map.
Customizable Speed: The speed of the vehicle movement can be easily adjusted in the app.js file.
Start Button: Movement starts only when the "Start" button is clicked, providing control over the animation.

#How It Works
Map Initialization:

The Leaflet map is initialized with a default center at specific latitude and longitude coordinates.
OpenStreetMap is used for the map tiles, providing a detailed background map layer.
Vehicle Route:

The vehicle follows a set of predefined coordinates, simulating movement across the map.
A blue polyline represents the route on the map.
Vehicle Movement:

A custom car icon is placed at the starting point of the route.
Clicking the "Start" button triggers the vehicle's movement along the route.

#Project Files
index.html: Contains the structure of the webpage and includes the map container and the "Start" button.
style.css: Defines the styling for the map, button, and basic layout.
app.js: Handles the map initialization, vehicle movement logic, and button functionality.
sport-car.png: The custom icon used for the vehicle. OR you can use image icon url directly.
