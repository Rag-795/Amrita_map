<h1 align="center"> Offline Navigator Web App </h1>
<img align="center" src="./Res/amrita_map.png"/>

# Features
- [x] Zoomable, Pannable and Rotatable Map  Based on Fabric.js
- [x] On the way - Dynamic Places With Description and Model Detailed Description with Image Carousel
- [x] Colour Code Based Path Marking 
 -  `Yellow`: Completed
 -  `Orange`: Returned Back
 -  `Red`: Yet To Cover
- [x] <b>Toolbar:</b> Map Refresh, Rotate 90°, Back To 100% Zoom and 0° Rot Buttons
- [x] Dynamic Compass
- [x] Dynamic Directions Based on current Compass direction and Map Rotation
- [x] Destination Reached Alert Model
- [x] Custom Animated Hamburger Menu and Navbar (In Progress)

# Instructions 
<img align="center" src="./Res/basic.png"/>

- Select Start and destination points and tap on Go
- You now get a navigation instructor and Places On the Way List View

# Navigation
<img align="center" src="./Res/navigation.png"/>

- The initial `Red` path on the map is the path to cover
- Tap on the Next button for directions to the next place on the way (You get an `Yellow` path on the map to indicate Covered path)
- Tap on the Back button if you accidentally pressed Next (You get an `Orange` path on the map to indicate Returned path)

# Interacting with the Map
<img align="center" src="./Res/interact.png"/>

- `Zoom` by using Two Fingers
- `Rotate` by using 3 fingers
- The Red Needle of the Compass always points towards north of the map
- When you rotate the map, the direction arrow rotates automatically to adapt to the new changes.
> Rotate Functionality is only supported in touch screen displays as of now, and not yet supported in laptop trackpads.

## Map Toolbar
<div align="center">
<img align="center" height="250px" src="./Res/toolbar.png"/>
</div>

# On Your Way
<div align="center">
<img align="center" height="600px" src="./Res/on_your_way.png"/>
</div>

- Below the navigation instructor, you get a list view of places on the way from your current location to your destination.
- Tap on any place to see the full description, images, timings, things to do and must-tries in that place.

# End Navigation and New NavBar
<div align="center">
<img align="center" height="600px" src="./Res/exit_and_navbar.png"/>
</div>

# Motivation Behind the Project
 When I moved to Amrita Vishwa Vidyapeetham University Campus in 2022 (After COVID Lockdown), I faced a lot of trouble not knowing routes to places, taking long routes and getting lost sometimes.
The existing Paper maps weren't very effective althogh they helped a little. Google maps didn't have all places and routes in the campus at that time. That is when I felt the need to make a navigator for the campus.

 One Year Later, I took up that idea for my Data Structures and Algorithms Course Project and completed the current version of the prototype. I received permission from my university authorities to go ahead into expanding the project for the entire campus so i started working on designing our campus's map in `Autocad`.

<img align="center" src="./Res/map-min.webp"/>

