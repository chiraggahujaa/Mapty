# Mapty
Mapty is an interactive activity tracking website developed using JavaScript, CSS, HTML, and the Leaflet Maps API. The project allows users to log and visualize their running and cycling activities, recording essential metrics such as location, distance, duration, cadence, elevation gain, and calories burned. The user-friendly interface provides comprehensive insights into tracked activities, enhancing the overall fitness tracking experience.

# Project Structure
The project is organized into classes and functions to handle different aspects of the application, including the creation of running and cycling workouts, rendering markers on the map, and managing the user interface.
  - Workout Class: Defines a base class for workouts, including common properties like date, ID, and clicks.
  - Running Class: Extends the Workout class and adds specific properties and methods for running workouts, such as cadence and pace calculation.
  - Cycling Class: Extends the Workout class and includes properties and methods specific to cycling workouts, such as speed and elevation gain calculation.
  - App Class: Manages the overall application, including map initialization, handling user inputs, rendering workouts on the map, and storing data in local storage.

# Features
  - Interactive Map: Utilizes the Leaflet Maps API to display an interactive map where users can log their activities.
  - Workout Logging: Users can log running or cycling workouts, providing details such as distance, duration, and additional metrics based on the activity type.
  - Map Markers: Each workout is represented by a marker on the map, providing a visual overview of the user's activity history.
  - User-Friendly Form: A form allows users to input workout details, with dynamic fields based on the selected activity type (running or cycling).

# Usage
  - Open the index.html file in a web browser.
  - Allow the browser to access your geolocation when prompted.
  - Use the form to log your running or cycling workouts, providing necessary details.
  - View the logged workouts on the map and in the list below.

# Getting Started
To run the project locally, simply open the index.html file in a web browser. The application will prompt you to allow geolocation access to display the map.
