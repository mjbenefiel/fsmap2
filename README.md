Project: whatToDoApp | Global

Authors: Michael Benefiel | Billy Hodes | Spencer Knoll

Why we created this project:

Homework for the University of Kansas Coding Boot Camp.

Feel free to use some or all of this code if you're trying to complete a similar project.

THE PROJECT

FourSquare API

GoogleMaps API

Bootstrap v4.0.0-alpha.6 

Font Awesome 3.0.2

jQuery JavaScript Library v2.0.3

Knockout-3.2.0.js

Firebase 5.5.2

- Initialize Firebase

  - Log search terms entered

- Initialize VenueModel to store venue information of place

- If/else statements to return specific message if there's no website, phone or rating for a venue

- AppViewModel performs nearly all functionality of app

- Initiate GoogleMaps -- Zoom set to "2" so that it has a global view

- Various KO observable arrays for finding and displaying data

- searchVenueLocations performs search queries of venue location by calling FourSquare API. GoogeMaps markers are also bound within this function.

- Search queries set to &near= exploreLocationSearch(); to allow a user to search for any location within the FourSquare API

- For loop for looping through fourSquareData

- marker object set to bind all data within infoWindow

- addListeners for infoWindow -- click, mouseover, mouseout

- Suggested LL bounds for GoogleMaps API -- sets bounds according to FourSquare data response

- contentString binds all data into HTML for display when individual marker is clicked

- streetViewService variable declared so infoWindow contains Google Street Views

- getStreetView function displays the Google Street Views within infoWindow -- sets it to the contentString

- Filter array to filter locations

- panToMarker function that pans to the marker and location on click 

- function that handles data errors -- URL, Phone and Rating message

- toggleBounce function that toggles marker on click

- Clear and reset marker arrays

- Set marker colors

- openInfoWindow function