# Real-Time Tracking Application

![Real-Time Tracking](https://img.shields.io/badge/Real--Time-Tracking-brightgreen)

## Overview
The Real-Time Tracking Application is a web-based solution that allows users to track their real-time location on an interactive map. Built using Node.js, Express, and Socket.io for the backend and Leaflet.js for the frontend, this application demonstrates a full-stack approach to handling real-time data and dynamic map rendering.

## Features
- Real-time location tracking using WebSocket with Socket.io
- Interactive map with dynamic marker updates
- Responsive design for seamless use across devices
- Simple and intuitive user interface

## Technologies Used
### Frontend
- **HTML5**
- **CSS3**
- **JavaScript**
- **Leaflet.js**

### Backend
- **Node.js**
- **Express**
- **Socket.io**

## Installation
To run this project locally, follow these steps:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yaaaashvii/Real-Time-Tracking-App.git
   cd realtime-tracker
2. **Install dependencies:**
 ```bash
npm install
```
3. **Start the Server:**
   ```bash
   npm start
   ```
4. **Open your browser and navigate to http://localhost:3000**

*How It Works*
1. Geolocation Tracking: The application uses the browser's Geolocation API to fetch the user's current location.
2. Real-time Communication: Socket.io establishes a WebSocket connection between the client and the server to send and receive location data in real time.
3. Map Rendering: Leaflet.js dynamically renders the map and updates the user's location with markers.
   
   
