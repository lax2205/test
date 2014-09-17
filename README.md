Screening Test
====

## Instructions:

* Execute each one of the below 5 tasks. If you leave any task incomplete, comment your code to reflect where it is incomplete along with the reason

* Keep your code clean and organized. Comment your code liberally. 
* Make sure that your code works on Google Chrome and Firefox


### 1. jQuery UI

* Add a new page /jqui.html, along with a menu item on the left menu called "jQuery UI"  
* Create two columns in the page with different color backgrounds
* Add 5 draggable elements on the left column using jqueryui
* Make the right column droppable and accept elements from the left column



### 2. Ajax

* Create another page /ajax.html, along with a menu item on the left menu called "Ajax"
* On page load, wait for 5 seconds. Then make a search request using Ajax to the open weather api. Use regular Ajax or jquery ajax. 
* The request must search for weather in "bangalore" and JSON format
* http://openweathermap.org/current
* Get the response data and display each parameter in a separate line in the page along with the parameter name


### 3. File upload

* Create a page called /file-upload.html
* Add a file input which accepts images only
* When the file is selected, draw a thumbnail preview on the page

### 4. Javascript Classes

* Create a javascript file in the /js directory called locate.js
* In the file, create a class called LocateMe which accepts two variables, first_name and last_name with defaults as "John" and "Doe"
* In the constructor of the class initialize two variables, first_name to your first name, and last_name to your last_name
* Add two more default values - latitude and longitude and initialize them to 0 in the constructor 
* Create a class function called getLocation which gets the latitude and longitude from the browser using HTML5 api
* Create a html view /mylocation.html along with a menu item on the left menu 
* In mylocation.html, create 2 text inputs, firstname, and lastname, and a submit button
* On submit, use the text input values and create an instance of the class. Use the getLocation from the class to get your location
* Print your location using the class instance to the page in this format "<first_name> <last_name> is currently located at <latitude>, <longitude>"



### 5. Maps & basic js, jquery

* Create a menu item called "Maps" on the left menu with two sub items, as below:

Maps 

1. Polygon

2. Polyline


* Add two pages: /map-polygon.html and map-polyline.html
* Polygon navigates to /map-polygon.html
* On this page, add a large map using leaflet.js, and open street maps. Use the leaflet api to draw a square polygon on the map


* Polyline navigates to /map-polyline.html
* On this page, add a large map using leaflet.js, and open street maps. 
* Auto generate 10 latitude, longitude pairs. Draw a polyline using leaflet.js
* Add one regular marker to the beginning of the polyline, and one to the end
