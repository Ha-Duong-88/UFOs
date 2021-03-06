# UFOs
JavaScript, Bootstrap, HTML, D3

# Overview of Project

The objective of this project was to create an interactive webpage to allow user inputs on search filters on UFO sightings and be able to visualize the data and analysis in a dashboard utilizing JavaScript, HTML, D3, and Bootstrap.


For this project we created a webpage with HTML and a JavaScript file in Visual Studio Code IDE to create table filters from data imported a JavaScript data file, arrow functions and for loops to loop through each field in an array of objects in the data file and build the table to display the UFO sightings. We used Bootstrap components to create interface elements such as buttons and data entry forms, Bootstrap's grid system to organize the webpage's content into containers, rows, and columns, and D3, a JavaScript library to produce a dynamic visualization in an HTML web page. The DevTools Console was also used to create and test the JavaScript and HTML code. Building the webpage using JavaScript and HTML required linking several JavaScript files, including D3, app.js, data.js, CSS style sheet and images to the HTML file. 

# Results

Visualizing data in a webpage makes it easier for users to view and interact with dynamically rendered data and analysis.

Displayed below are images from the webpage with the search fields and the table to display the results. A title and concise description of the purpose of the webpage greet users when they land on the page. They are invited to explore the data.

UFO_image1.png![image](https://user-images.githubusercontent.com/80140082/120116381-bd1e2500-c13c-11eb-96c5-913f3be96171.png)

There five different filters to choose from: the date, city, state, country and shape. Users can input a criteria for one or multiple filters in the search form (field). Multiple search criteria is especially useful to further inspect the data. The HTML then displays all of the sightings in a table that match that specific search. If there is no match to the search criteria, the table will be empty.

UFO_image2.png![image](https://user-images.githubusercontent.com/80140082/120120795-881dcc80-c154-11eb-8a3a-b39e5954b126.png)


# Summary

  ### Opprtunity Areas
  There are several drawbacks with this design:
  1) There is no data on the number of people that witnessed the same UFO sighting to corrobate that they occurred.
  2) The dataset is limited to sightings reported for one month and year (January 2010) and only for a single country (US).
  3) The lack of an 'update' or 'search' button does not make it obvious to users that the search was successful and the data returned matched the criteria entered.
  4) The placeholder information in the search fields could lead users to assume that the data in the table reflects the search parameters. As the default table          displays all of the sightings, the placeholder search criteria creates ambiguity for users.
  
  ### Recommendations 
  
  The following are recommendations to deepen the analysis and improve the user experience:
  1) Expand the filter for the dataset to include a broader range of dates and years for the sightings.
  2) Expand the dataset to include different countries where sightings have been reported beyond the US to increase the sample set size and deepen the analysis that      UFO sightings are witnessed world-wide.
  3) Allow users to enter in their own sightings by adding a search entry form and include the total number of users for each sighting if there are more than one   
     user.
  4) Add an 'update' or 'search' button after each each search field or at the end of the last search field that users can click to update the table once they       
     enter their search criteria. This will make it clearer to users that the table has been refreshed to reflect the search filter(s).
  6) Add dynamic charts with D3 to show statistics for the sightings. For example, a chart to summarize the the total and average number of sightings on a  
     given date, city, country, shape and duration.
  6) Remove the search criteria placeholders from the HTML code to avoid confusion.
  7) Review the American Disability Act guidelines to ensure that the web page is ADA compliant. 
  
