# MIHIR - Chat Application 
This repository contains the backend for a real-time chat application built with the MERN stack. The backend utilizes Node.js, Express, MongoDB, and Socket.IO to provide chat functionality.

## Installation Guide
### Requirements
Before you start, ensure you have the following installed:
Node.js
MongoDB
Ensure MongoDB is running in the background.

### Installation
npm install
npm init

#### First Method
```shell
git clone https://github.com/mihirkasodariya/Real-Time-Chat-React-Nodejs.git
```
Now rename env files from .env.example to .env
```shell
cd public
mv .env.example .env
cd ..
cd server
mv .env.example .env
cd ..
```

Now install the dependencies
```shell
cd server
yarn
cd ..
cd public
yarn
```
We are almost done, Now just start the development server.

For Frontend.
```shell
cd public
yarn start
```
For Backend.

Open another terminal in folder, Also make sure mongodb is running in background.
```shell
cd server
yarn start
```
Done! Now open localhost:3000 in your browser.

#### Second Method
- This method requires docker and docker-compose to be installed in your system.
- Make sure you are in the root of your project and run the following command.

```shell
docker compose build --no-cache
```
after the build is complete run the containers using the following command
```shell
docker compose up
```
now open localhost:3000 in your browser.

### Project Structure
server/: Contains the backend code (Node.js, Express, MongoDB, Socket.IO).
public/: Contains the frontend code (React).
