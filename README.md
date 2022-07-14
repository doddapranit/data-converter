
## Overview
The data conversion project in GT WebDev for the fall of 2021! The project consists of a front-end (located in the client folder) and a back-end (located in the server folder). The front-end is a React application, and the back-end is a Node.js/Express.js server. The Node.js back-end will host API endpoints that the React application will call to do its work.

## Setting up the application
The client (React app) and the server (Node server) must be run on different ports, or through separate terminal windows when running it locally.

To get the repository onto your machine, you'll want to clone it with the following bash command:
```
git clone https://github.gatech.edu/sbuckley31/gtwebdev-data-converter-team-A.git
```

Next, you'll want to install any dependencies in both the client and server applications. To do so, you'll want to run the following:
```
cd client/data-converter && npm install && cd ../..
cd server && npm install && cd ..
```

## Running the application

To run the client application, run the following bash commands:
```
cd client/data-converter
npm start
```

To run the server application, run the following bash commands:
```
cd server
npm run dev
```

To quit these servers, click Control-C

You can test to see if the server (API) is running properly by checking the output of the following command (in another window):
```
curl localhost:3001/
```