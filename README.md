# DEV-CONNECTOR

A Software developers social network connection website build with React, Redux, Express, NodeJS, JavaScript, and MongoDB.

## Project Status

This project is completed enough to showcase my skills. The website include a Landing page, Posts page, Developers' Profiles page, Dashboard page, Sign-in and Sign-out pages, Github repos component. Functionalites like User Authentication & Authorization, Image Uploading, Create/Edit/Adding to Profile, Create/Comment/Like/Dislike/Delete Posts.

The project is live at: https://phih-dev-connector.herokuapp.com/

## Reflection

I built this project as a learning experience and to improve my MERN stack development skill.

The project was mean to be a simple social network website that can display and create developers' profiles, a dashboard page to edit user profile, show developer's github repos, create, comment, like and dislike a developer's post, and user authentication.

The notable technologies implemented in this project are Redux for State Management, JWT for User Authentication, and Image Uploading.

## Installation

1. Clone this repo. You will need node and npm installed on your machine
2. Open the project in your IDE and run the following command on your command line:
```
npm install
cd client
npm install
```
3. Add a default.json in config folder with the following:
```
{
  "mongoURI": "<your_mongoDB_Atlas_uri_with_credentials>",
  "jwtSecret": "secret",
  "githubToken": "<yoursecrectaccesstoken>"
}
```
4. Then you can run the below command to run the project:
```
npm run dev
```
