# Async Weather Tracker – Project Notes

## 1. Project Overview
The Async Weather Tracker is a web application that fetches real-time weather
information for a searched city using an external API. The project demonstrates
the use of asynchronous JavaScript, API handling, and browser storage.

## 2. Technologies Used
- HTML5 for structuring the webpage
- CSS3 for styling and layout
- JavaScript (ES6) for logic and interactivity
- OpenWeatherMap API for weather data
- Browser LocalStorage for saving search history

## 3. Working of the Application
The user enters a city name and clicks the search button. The application sends
an asynchronous request to the weather API using the fetch method and async/await.
Once the response is received, weather details are displayed on the screen.

## 4. Asynchronous JavaScript
The getWeather() function is declared as async. It uses the await keyword to wait
for the API response without blocking the main thread. This ensures a smooth user
experience.

## 5. Event Loop Explanation
The console section of the application demonstrates the JavaScript event loop.
Log messages show the sequence of execution during asynchronous operations such
as fetching data from the API.

## 6. LocalStorage Usage
LocalStorage is used to store previously searched city names. This allows users
to quickly search for cities again by clicking on the stored buttons.

## 7. Error Handling
Try-catch blocks are used to handle errors such as invalid city names or network
issues. Appropriate error messages are displayed to the user.

## 8. Conclusion
This project helps in understanding asynchronous programming, API integration,
and client-side storage, which are essential concepts in modern web development.

### Async & Await
Async/await simplifies handling of promises in JavaScript.

### Event Loop
JavaScript uses an event loop to handle asynchronous operations.

**Assignment completed and ready for submission.**