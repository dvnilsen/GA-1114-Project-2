# GA-1114-Project-2

## Pitch
An application for watch enthusiasts to track their collection of watches and bands (which are interchangable).  Users can input information about each watch and band, enter a review of their watch in a text field, and call timezone information to help them reset their watch when they travel (timezone data will be stored with the watch entry). 

## User Story
As a user, I want to:
1. Add watch and band information to a list to track my collection.
2. Write a personal review of my watches to capture my feelings about the design, user experience, what the piece means to me, etc. 
3. Be able to easily edit my entries (especially my reviews, with new thoughts about each watch over time) and delete entries when I sell or no longer want to use a watch.  

## Tech stack:
HTML, CSS, JS, SQL, Express, EJS, Sequelize, API calls. 

## API:
https://api-ninjas.com/api/timezone - The Timezone API provides timezone data for any latitude/longitude coordinates or city in the world. 

Example: 
url = "https://api.api-ninjas.com/v1/timezone?city=sandiego" 
Screenshots:
![API_1](https://github.com/dvnilsen/GA-1114-Project-2/blob/main/Assets/API_1.png "API_1") 
![API_2](https://github.com/dvnilsen/GA-1114-Project-2/blob/main/Assets/API_2.png "API_2") 

## ERD and Restful:
![ERD](https://github.com/dvnilsen/GA-1114-Project-2/blob/main/Assets/ERD.png "ERD")  
![RESTFUL](https://github.com/dvnilsen/GA-1114-Project-2/blob/main/Assets/RESTFUL.png "RESTFUL")  

## Wrireframes:
![1](https://github.com/dvnilsen/GA-1114-Project-2/blob/main/Assets/wireframe_1.png "1")  
![2](https://github.com/dvnilsen/GA-1114-Project-2/blob/main/Assets/wireframe_2.png "2")
![3](https://github.com/dvnilsen/GA-1114-Project-2/blob/main/Assets/wireframe_3.png "3")
![4](https://github.com/dvnilsen/GA-1114-Project-2/blob/main/Assets/wireframe_4.png "4")

## MVP goals:
1. Allow users to create a username and password to sign up and log into the app. 
3. Store all information about the user's collection in a database and display the information in the app.  
4. Allow users to update and delete entries in their collection. 
5. Let users search for the correct timezone information based on their current city and attach that information to a watch.  

## Stretch goals:
1. Allow users to add their own photos of their watches and bands.
2. Store older timezone data so that users can track where they've worn each watch. 




