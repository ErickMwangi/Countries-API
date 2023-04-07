## Setup Requirements
  • Git
  • Github
  • Node.js
  • JSON Server

  ## Built with
  • Semantic HTML5 markup
  • CSS custom properties
  • JavaScript
  • REST API

 ## Run 
  'npm install -g json-server' command to install the JSON Server.
  'json-server --watcher db.json to start the JSON Server'

  To view server navigate to   
  Resources
  http://localhost:3000/posts
  http://localhost:3000/comments
  http://localhost:3000/profile

  Home
  http://localhost:3000

  To run the application, open the index.html file on your browser using a suitable code editor ie https://code.visualstudio.com/

## About
The code is creating a webpage that displays information about countries using data from "https://restcountries.com/v3.1/all". It fetches data about all countries and creates a display for each country containing its name, flag, population, region, and capital. It also allows the user to click on a country's name to show more detailed information about that country, such as its native name, subregion, and borders.

The 'GetCountries()' function fetches data about all countries from the API and creates a display for each country. it first uses the 'fetch()' function to get the data, and then uses the 'then()' method to process the data. if the response is OK, it returns the JSON data, otherwise it throws an error. Then, it loops through the data and creates a 'div' element for each country containing its name, flag, and details. It also sets attributes for the element to store the country's name and region

The 'ShowMore()' function fetches data about the country using its name, then creates a display to show the country's details. it first creates a 'div' element to store the display, sets its class attribute to "ShowMore", and creates a 'button' element to store the country's flag and details sets its class attribute to "showContainer", and creates a 'div' element for the country's details, setting its class attribute to "details".

Next, it creates 'p' element for each piece of information to be displayed, such as the native name, population, region, subregion, and capital, and adds them to the details 'div'. Finally it appends the flag, name, details, and back button to showContainer 'div', and appends the showContainer 'div' to the showMore 'div'. The 'Back()' function is not provided in the code, but it is expected to take the user back to the previous page when called. 

## known Bugs
There are no known bugs of this project at the moment.

## Support and contact details
For any contributions towards this project
• Email: rickthetri20@gmail.com