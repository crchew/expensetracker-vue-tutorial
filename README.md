# Spotify Homepage Clone
## Overview
This project is a simple Spotify clone that recreates the user profile home page using HTML, CSS, and JavaScript. It utilizes the Spotify Web API to access user data and displays personalized information such as User Top Items, New Releases, and Featured Playlists.

### Features

User Top Items: Display the user's most-listened-to tracks based on their recent listening history.

New Releases: Showcase the latest music releases, including albums and singles available on Spotify.

Featured Playlists: Highlight curated playlists recommended for the user.

### Usage
Upon opening the application, users will be prompted to log in with their Spotify credentials.

Once authenticated, the home page will display the user's top items, new releases, and featured playlists.

Spotify Web API Authorization
This project uses OAuth 2.0 for user authentication. The authorization flow is handled through JavaScript functions in the script.js file.

### API Endpoints
The application fetches data from the following Spotify Web API endpoints:

User Top Items: https://api.spotify.com/v1/me/top/tracks

New Releases: https://api.spotify.com/v1/browse/new-releases

Featured Playlists: https://api.spotify.com/v1/browse/featured-playlists

### Project Structure
index.html: HTML file for the main structure of the application.

style.css: CSS file for styling the application.

script.js: JavaScript file containing functions for authorization, data fetching, and display.

### Acknowledgments
This project was created for educational purposes and inspired by the Spotify music streaming platform.

### License
This project is licensed under the MIT License.

