
# Mapty App

## Demo  <a href="https://somnath64.github.io/mapty-app/">link</a>

## Project Overview

<img src="https://github.com/Somnath64/mapty-app/blob/main/images/Mapty%20-app%20.png" alt="project image">

Welcome to the Mapty Application! This project is a fitness logging application that allows users to log their workouts and view them on an interactive map. Users can input details such as workout type (running or cycling), distance, duration, and additional parameters like steps per minute or elevation gain. The application uses geolocation to automatically fetch the user's current position and displays the workouts as pins on the map. 

## Features
<p><h3>Interactive Map:</h3> The application features a map that is loaded from a third-party service and centered on the user's current location using geolocation.</p>

<p><h3>Workout Logging:</h3> Users can input their workout details, such as type (running or cycling), distance, duration, and additional parameters like steps per minute or elevation gain.</p>

<p><h3>Workout Pins:</h3> Each logged workout is displayed as a pin on the map, allowing users to visualize their workout locations.</p>

<p><h3>Persistent Data:</h3> The application uses browser storage to store workout data locally, ensuring that logged workouts persist even after closing and reopening the app or opening it in a new tab.</p>

<p><h3>Remove workout:</h3> Delete workout from sidebar </p>

## Tech Stack
 HTML, CSS, JavaScript, and a mapping library (Leaflet javascript library)for displaying the interactive map.

## Usage
Allow the application to access your current location to load the map centered on your position.
Log your workouts by filling out the workout form with the required details.
Click "Enter" to add the workout to the sidebar list and display it as a pin on the map.
Click on a workout pin to view its details in a popup.
Use the sidebar list to scroll through and find specific workouts on the map.
