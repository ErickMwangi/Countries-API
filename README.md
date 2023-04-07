# Quotes Website
___
## Contributors of this Project
___
## By Erick Mwangi on 7th April 2023
___
## Description
___

Moringa Phase 1 Independent Project on a Quotes website that allows users to 

  • View all quotes `GET/quotes`
  • Create their own quote `POST/quotes`
  • like a quote `PATCH/quotes/:id`
  • Delete a quote `DELETE/QUOTES/:id`

## Setup Requirements
___

  • Git
  • Github
  • Web Browser (Chrome or Firefox)
  • Node.js
  • JSON Server  
  
  ## Getting started
___

Install JSON Server
`npm install -g json-server`

create a `db.json` file with some data

Start JSON Server
`json-server --watch db.json`

## Introduction

 This code creates a web page that displays information about countries using data fetched from `https://restcountries.com/v3.1/all`. The page has features for filtering and searching through the list of countries displayed.

The code starts by defining variables using `document.querySelector()` to access HTML elements. There are variables for buttons, containers, and other elements needed for the filtering and searching features.

There is a function called `toggleMode()` which toggles the class "light" on the `document.documentElement` element. This function is used to switch between dark and light mode.

There is another function called `showItem()` which toggles the class "open" on the .filter__icon element and calculates the height of the list container to show or hide it. This function is used to expand and collapse the filter list.

There is also a function called `scrollToTop()` which scrolls the window to the top of the page using `window.scrollTo()` method. It is triggered when the user clicks on the "to top" button.

The code then fetches data from the API using fetch() and adds a click event listener to the filter items to filter the countries by region. It also adds an input event listener to the search input to filter the countries by name.

The `filter()` function takes an array of countries and filters them by region or by search term, depending on which filter is active. The `show()` function takes an array of countries and two filtered arrays and shows or hides each country element based on whether it is in the intersection of the two filtered arrays.

## Known Bugs
___

There are no known bugs of this project at the moment.
Overall, the code seems to be well-organized and efficient for displaying and filtering a large list of countries.

## Support and Contact details
___

For any contributions towards this project:
  • Email rickthetri20@gmail.com
  
## Like this Project
___
if you are feeling gorgeous by me a coffee!