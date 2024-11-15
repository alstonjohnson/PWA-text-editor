# Text Editor PWA

##Description

This project is a Progressive Web Application (PWA) text editor that works seamlessly both online and offline. The application allows users to create, save, and retrieve notes or code snippets, ensuring reliable access even without an internet connection. It is bundled with webpack, includes a service worker for asset caching, and supports installation as a desktop application. Built with next-generation JavaScript, it uses IndexedDB for storage and Workbox for service worker functionality.

## Table of Contents

Installation
Usage
Features
Deployment
Technologies Used
License

## Installation

Install dependencies:
npm install
Build the application:
npm run build
Start the application:
npm run start

## Usage

Open the application in your browser by visiting the deployed URL or running it locally.
Use the text editor to write and save content.
The application automatically saves your input when the DOM window is unfocused.
Reopen the application to retrieve your saved content from IndexedDB.
Install the application as a PWA by clicking the Install button.
Use the app offline to create and retrieve notes or snippets.

## Features

IndexedDB Integration: Creates an object store with GET and PUT methods to save and retrieve data.
Offline Functionality: Works without an internet connection by caching static assets and saving data locally.
Automatic Save: Content is saved automatically when the window loses focus.
Webpack Bundling: Bundles JavaScript files for efficient loading.
Service Worker: Uses Workbox to cache static assets and subsequent pages.
PWA Support: Includes a generated manifest.json for installation as a desktop app.
Modern JavaScript: Supports async/await through Babel.
User-Friendly UI: Clean, polished interface for an intuitive user experience.

## Deployment

Live Application: Text Editor PWA on Render
GitHub Repository: GitHub Repo

## Technologies Used

JavaScript
Webpack
Workbox
IndexedDB
Babel
Service Worker
Node.js
Express.js

## License

This project is licensed under the MIT License.

