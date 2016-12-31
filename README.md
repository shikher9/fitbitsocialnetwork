# Fitbit Social Network
# Introduction

This project is about fitness tracking and social networking among fitness enthusiasts. We have integrated with Fitbit API and are tracking the fitness levels of individuals, display the fitness data in user’s dashboard in presentable form like graphs and charts etc. We have also introduced a concept of social networking among friends with news feed containing fitness data about your friends. In this project we have made use of Fitbit developer API and OAuth 2.0.The demo link below only shows the UI, which are just static pages. Just use any credentials to log in, it does not verify. Check out the source code if you want to know more. The images and other resources for the application have been taken from Pixabay, and are free for non commercial use.

# Technology

The server for the application was build using Spring MVC 4 with Maven. A token based authentication is used for authenticating users using JJWT (https://github.com/jwtk/jjwt). Password encryption has been done using BCrypt. The application has one custom thread for fetching data from Fitbit. All the application functionality is exposed using REST Api. The UI for the application was made using HTML, CSS (Flexbox for layout), JavaScript, some bootstrap, and Jquery. The UI is mobile responsive.

# HTML 5 Features Used

The application front-end uses a lot of HTML5 features. The features used are,
Geolocation API - The application uses HTML5 geolocation api for determining the latitude and longitude of the user while signup. The location is stored for a particular user and used for friend suggestions and analysis.


Local Storage - We have used local storage for storing user token and some other things. Local Storage is a new HTML 5 feature which lets you store key value pair for an application. It is persisted for multiple sessions. All the variables which are stored in local storage and are removed when user logs out.


Data List - The datalist element is used in the search bar of the search page, it will list all the existing searched items. Data list eases a lot of task and improves the UI as well. It also makes the UI more feature rich.


Input tag with type email - The input which accepts email has type of email. This input is much better than normal text type. The input tag makes it compulsory to validate email on form submission. Automatic validation of email is done and form is submitted only when email is in right format.


Nav html tag - We are using nav tag as a container for storing navigation links. Using this tag is much better than using a normal div as it increases accessibility. This tag tells the browser that it contains navigation links.