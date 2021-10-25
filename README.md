# Phase2Project
Spice It Up!
Helping You Put the Spice into your meal!

Core Deliverables...

1. You must make a single page application (only one index.html file) using create-react-app
2. Your app should use at least 5 components in a way that keeps your code well organized
3. There should be at least 3 client-side routes using react-router (Links to an external site.)
4. Use a json-server to create a RESTful API for your backend and make both a GET and a POST request to the json server.

Using the https://www.themealdb.com/api.php API we will create a single page web application which will firstly bring the user to a Home page in which they will see a random recipe rendered on the page from a get request to www.themealdb.com/api/json/v1/1/random.php, the random meal generator. Only the title and image will be displayed upon rendering. There will be an option to "get more info" and that will drop down the recipe and etc. using Nested Routes. The user will have an option to click a button that sends a get request to get another randomly generated recipe. When the user clicks the image the state will be changed and display the associated recipe video using the youtube npm https://coderrocketfuel.com/article/embed-a-youtube-video-in-a-react-webpage. A button should also be added that allows the user to save the name, picture, and recipe to favorites database using a post request. 

Within the Home page there will be a nav bar at the top that allows the user to navigate to a favorites list and a search by country link. 

The favorites page will render all the favorited recipes. On initial display you will see just the picture and and name and with a click you can individually display the full recipe. We will also have a form to make a new recipe. 



In the search by category link a there will be a list of categories in the header (vegetarian, pork, dessert, etc). On the onlcik a GET request will be made to the search by id end point https://www.themealdb.com/api/json/v1/1/filter.php?c=Vegetarian. Food cards will then render underneath with a small picture and name. The user can then click a specific meal and have the full recipe appear on the side or underneath all the food cards. This will be done by making another fetch request using the "idMeal" number with the id number endpoint https://www.themealdb.com/api/json/v1/1/lookup.php?i=52807.  Food card should have an add to favorite button. 


