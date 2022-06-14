# chat-application_v2

This is the second version of my AdvancedJS project where all the modules are up to date. It is a fun yet simple chat application designed to be more aesthetically pleasing and using PedroTech's tutorial as a basis for the application, I have added a additional quality of life improvements to the app so the end user can send and receive messages efficiently.

## Description
<img src="ChatScreenshot.PNG" alt="picture of sample chatbox" height="300" width="200"> 

### Built With

* [React.js](https://reactjs.org/)
* [Node.js](https://nodejs.org/en/)
* [Socket.IO](https://socket.io/)
* [Express](https://expressjs.com/)
* [Nodemon](https://www.npmjs.com/package/nodemon)
* [CORS](https://developer.mozilla.org/en-US/docs/Web/HTTP/CORS)

## Getting Started

### Installation

Run the following commands (if you cannot run the project properly on your machine):
```
cd server
npm init
```
(for npm init, press enter to skip all the options and press enter for "Is this OK?")
Then, run the next command to install the packages:
```
npm i express nodemon socket.io cors
```

Navigate to the client folder and run this command:
```
npx create-react-app .
```

### Testing the Application

Copy/paste the localhost in a new browser and make sure you use the same Room ID for both browsers to properly send messages.

## Credit 
PedroTech's Realtime Chat Application: https://www.youtube.com/watch?v=NU-HfZY3ATQ

**NOTE:** If you are building this project from scratch, make sure you get rid of the React StrictMode tags in the client src folder as it duplicates the messages sent.
