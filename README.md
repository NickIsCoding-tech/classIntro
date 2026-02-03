# React Hello World (Dockerized)

This project is a simple React “Hello World” application created for the class intro assignment. The original Create React App starter code was removed and replaced with a custom styled Hello World user interface. The application is containerized using Docker.

# Tech Stack
React (Create React App)
Docker
Git & GitHub

# Dependencies
Make sure the following are installed on your system:

Node.js & npm  
Docker  
Git

# Installation
Clone your forked repository and navigate into the project directory:

git clone <your-repository-ssh-url>
cd classIntro


Install project dependencies:

npm install

# Run Locally (Without Docker)

Start the React development server:

npm start


Open the application in your browser:

http://localhost:3000

# Run with Docker
Build the Docker image:

docker build -t hello-world-react .


Run the Docker container:

docker run --rm -p 3000:3000 hello-world-react


Open the application in your browser:

http://localhost:3000

# Project Structure

src/App.js – main Hello World React component

src/App.css – styling for the application

Dockerfile – Docker configuration file

.dockerignore – excludes unnecessary files from Docker builds

# Submission Materials

Screenshot of a successful git push to the forked repository

Screen share / demo of the working Dockerized React application