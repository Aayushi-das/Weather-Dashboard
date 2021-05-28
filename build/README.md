# Web-Design-Challenge
Weather Data Visualization Dashboard

An application used to compare weather conditions with time ranges, built with React, HTML, JavaScript, and CSS.
The purpose of this project was to analyze the weather trend at varying distances from the equator. To accomplish this, I created a sample of 10000+ datasets and pull the weather data from the OpenWeatherMap API to assemble a dataset.

Project Screen Shot(s)

https://user-images.githubusercontent.com/59438172/120016859-c2775480-c002-11eb-937d-9bcd31236468.png
https://user-images.githubusercontent.com/59438172/120016919-d458f780-c002-11eb-97d2-f0a64d6ce1bc.png

# Installation and Setup Instructions:

Clone down this repository. You will need node and npm installed globally on your machine.

Installation:

npm install

To Run Test Suite:

npm test

To Start Server:

npm start

To Visit App:

https://weather-dashboard-88be1.web.app/comparison.html


# Reflection

This was a project for an Internship the Project goals includes using technologies like ReactJS and deploying on Firebase.

Originally I wanted to build an application that allowed users to see comaprison between time-ranges and weather conditions. I started this process by using the create-react-app boilerplate, then adding react-router-4.0.

One of the main challenges I ran into was Authentication. This lead me to spend a long time on a research spike into OAuth, Auth0, and two-factor authentication using Firebase or other third parties. Due to project time constraints, I had to table authentication and focus more on data visualization from parts of the API that weren't restricted to authenticated users.

At the end of the day, the technologies implemented in this project are React, React-Router 4.0, LoDash and a significant amount of VanillaJS, JSX, and CSS. I chose to use the create-react-app boilerplate to minimize initial setup and invest more time in diving into weird technological rabbit holes.
