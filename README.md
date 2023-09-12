![image](https://github.com/stzivel/worldwise/assets/58048079/9d949783-8535-4f99-83b1-59511e43eb4f)
![image](https://github.com/stzivel/worldwise/assets/58048079/d1aa1d44-d324-4631-9339-6e454691ae4e)
![image](https://github.com/stzivel/worldwise/assets/58048079/f8adb5fb-7af8-4574-a2a7-81322808bcb5)

# Worldwise app

This app is a modern web application built with Vite and React. It leverages various technologies and libraries for a seamless user experience. Here's a brief description of its key features and components:

## React and Vite: The app is built using React, a popular JavaScript library for building user interfaces, and Vite, a fast build tool for modern web development.

## React Router: It utilizes React Router for managing client-side routing. This allows users to navigate between different pages of the app without the need for full-page refreshes.

## Context API: The app employs the Context API for state management. Two main contexts are used - CitiesContext and AuthContext - to manage city data and user authentication, respectively.

## Leaflet: For displaying an interactive map, the app utilizes the Leaflet library. Users can mark locations they've visited and view cities represented as markers on the map.

## JSON Server: The app simulates a back-end server using JSON Server. This allows it to make API requests to fetch and manipulate data, such as adding, deleting, and retrieving cities.

## CSS Modules: CSS Modules are used for styling components, ensuring that styles are scoped to their respective components and preventing global CSS conflicts.

## Custom Geolocation Hook
The useGeolocation hook is employed to effortlessly retrieve and manage geolocation data. This feature allows users to easily incorporate their current location into their map interactions.

The primary purpose of this app is to serve as a travel diary.  Users can interact with the map to mark locations they have visited around the world.  These locations are saved as cities and countries, along with additional information like the date of the visit 
and any notes. Users can also log in and log out using fake authentication.

In summary, this app combines React, React Router, Leaflet, and JSON Server to create an engaging and interactive travel tracking tool. It provides an immersive way for users to document their travel experiences and visualize them on a map.
