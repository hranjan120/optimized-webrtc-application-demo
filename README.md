# Optimized WebRTC Application architecture with Mediasoup WebRTC Server

<p align="center">
  <a href="https://mediasoup.org/" target="blank"><img src="https://mediasoup.org/images/mediasoup-banner.png?v=v0.6236987703750863" width="400" alt="Mediasoup Logo" /></a>
</p>

This repo is the Implementation of Mediasoup, a server-side WebRTC library.

# About

Mediasoup, a server-side WebRTC library, revolutionizes the development of scalable real-time applications. Known for its superior codec support, Mediasoup offers a creative platform for building advanced real-time media streaming services.

Building on WebRTC’s capability to enable browser-based interactions like video calls and data transfers without plugins, Mediasoup enhances this with a strong server-side solution for large-scale media handling.

- It’s a Node.js library that works with C++ subprocesses called Workers, each running on a separate CPU core to handle media streams.
- In these Workers, Routers manage audio and video RTP packet exchanges, similar to managing multi-party conference rooms.
- As the number of users increases, especially in large broadcast events with hundreds or thousands of viewers, Mediasoup allows for adding more Workers or spreading rooms across several hosts for smooth media flow.

## Installation and Setup

### General Setup

1. Clone this repository to your machine.
2. Open a terminal and navigate to the cloned repository's root directory.

### Backend Server

1. Change directory to the backend folder: `cd backend`.
2. Run `npm install` to install all necessary dependencies.
3. Start the backend by executing `npm run local`.
4. Verify that the backend is active on `localhost:8000`.

**Important Note**: Start the backend server first before starting the frontend.

### Frontend Application

1. Open a new terminal and navigate to the repository's root directory.
2. Change to the frontend folder: `cd frontend`.
3. Execute `npm install` to install dependencies.
4. After confirming the backend server is running, start the frontend with `npm run dev`.
5. Access the frontend at `localhost:3000`.

## Usage

With both the backend and frontend running, you can now explore the functionalities of Demo Application via your web browser
on `localhost:3000`.