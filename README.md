# Curatio
A solution to contact free healthcare for Metro Hacks 2022

![alt text](https://user-images.githubusercontent.com/93969295/202902410-21acfb9f-de4d-4e4b-9892-2c9fd99ba7a2.jpg)


## Inspiration
We wanted to come up with a simple solution for contactless healthcare.

## What it does
Curatio helps patients connect to doctors and receive information regarding healthcare according to the patients needs as much as possible without physically being in contact with the doctor or be at a hospital

## Tech Stack
1) Flask
2) Node.js
3) Google Maps API
4) Square API

## Challenges we ran into
We had a difficult time building a database management system for the logging in module for the webapp. We also faced some challenges when implementing the video calling feature but much research and trials, we managed to make it work. Another challenge we were facing was trying to find the user location for our map based features but in the end we managed to overcome all of them.

## Accomplishments that we're proud of
We are proud of what we have built so far and believe that it is a well thought out solution for contactless healthcare. It was an amazing learning experience for us.

## What we learned
1) To make a low level database and manage it 
2) How to build a login and sign up system from scratch 
3) How to use flask 
4) How to use google maps API to find nearest locations of specific type of places (pharmacies/hospitals) 
5) How to create a search filter 
6) How to use node.js
7) How to build a video calling webpage using webRTC

## What's next for Curatio
We hope to build it into an even more well designed and full of features webapp that can help both doctors and patients during this time of social distancing.

## RUNNING THE WEBAPP:

** The computer needs to have Python and pip installed **

1) First we need to create a virtual environment by opening a terminal and directing it to the directory of the app.
2) We then run "pipenv update" to get the the necessary dependencies installed.
2) Then we can run "pipenv flask run"
3) Run "npm start" on a separate terminal that is redirected to "Curatio/Video Module"
4) Run /misc/remove_doctor_db.py to clear all "customers" data


## DEPENDEINCEIS USED:

1) pipenv
2) flask
3) flask_googlemaps
4) googleplaces
5) ipinfo
6) squareup
