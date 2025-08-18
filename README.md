### Web crawler

## Tech Stack:

- This application has a frontend and a backend, for the frontend we used:

# TypeScript

# React

# Tailwindcss

and for the backend:

# Java

# Spring

## How to use:

To use the app, clone the repo: git clone https://github.com/FilipAndric33/web_crawler
Open two terminals, on one type: cd backend -> .\start.ps1. This will start the backend server on port 8080.

# For unix based OS like mac run:

cd backend -> ./mvnw spring-boot:run

In the second terminal type: cd frontend -> npm install -> npm run dev. This will start the frontend server on port 5173.

Open up a browser and type in the following URL: http://localhost:5173/ .
The explanation on how to use the app is provided on the web page. The threads are set to search for links for 10 seconds and then they have 10 more to execute the tasks in the queue. Essentially, once you pressed the search button you need to wait for 20 seconds to get the result.
