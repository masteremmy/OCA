
# Application Description

**Summary**

Restroom Locator Application using the following technologies: Google Maps API, Google Places Geocoder, End User data, HTML, CSS, Bootstrap, Javascript, JQuery, Google Firebase Databases & Storage  

Live Demo: https://masteremmy.github.io/OCA/

**Purpose**

This app aims to solve a problem many people face every day, and especially during long distance travel: the immediate need to find a decent restroom. Although Google has also used geospatial data to map places and general information related to restrooms, the OCA app magnifies its focus on images and reviews related to the interior of the restooms. By using photos with a higher pixel density and an emphasis on restroom reviews, we aim for OCA to provide a game-changing restroom experience. How would businesses react if they knew their welcoming water closet was bringing in more foot traffic? This app is also user-friendly and social, in that it allows multiple users across the country to add photos and information at any time.  

# Features 

**User Query**
  
This app will utilize the Google Maps API as well as the Google Places Geocoder to allow users to map directions to their desired location, and along the route it will pull up clickable pins for points of interest. Once clicked, the pins will display a modal with the information on the points of interest. The modal will display images and detailed information regarding publicly accessible bathrooms along the route. 

**User Write**

If submitting a location with the "Add This Bathroom" function on the second form, you must fill out all of the fields. [[We were trying to do this with having the 'required' property in our inputs, but because we are using event.preventDefault() to prevent the page from refreshing on form submit, this does not work.]]


# Current State of the Technology

Try using the search box to search for terms like 'chris', 'vinny', 'jay', 'new york', 'dc', 'philadelphia', 'walmart' and 'house'. Since we are using Firebase, there are currently only a few (approximately 12) points of interest added to the database. 
