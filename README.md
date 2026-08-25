# Spring Training Travel Planner

An API-driven baseball travel application that helps fans find MLB Spring Training games, locate stadiums, and discover nearby hotels in Arizona and Florida.

## Overview

Spring Training Travel Planner was developed as part of a University of Arizona software development program.

The application was designed around a simple problem: Spring Training fans often need to coordinate game schedules, stadium locations, tickets, and lodging across multiple websites.

Our goal was to create a more connected experience where a fan could find a Spring Training game, identify the stadium where it was being played, and search for nearby lodging without having to independently research each part of the trip.

## User Story

> As a baseball fan, I want to search the MLB Spring Training schedule and find a hotel near the stadium so that I can plan a trip to watch my favorite team play.

## How It Works

The application combines MLB Spring Training data, stadium locations, Google Maps, and hotel search data to help fans plan trips around the games they want to attend.

1. MLB schedule, team, and stadium data are loaded into the application.
2. Users browse available Spring Training games.
3. Selecting a game connects that game with its stadium and location.
4. Google Maps displays the corresponding geographic area.
5. Users can search for hotels near the selected stadium.

Team and stadium information is cached locally to reduce unnecessary API requests. Because schedules can change more frequently, schedule data is retrieved again when the application is refreshed.

Once the baseball data has loaded and rendered, the map is initialized and connected to the game-selection interface.

## My Contribution

I served as the **primary developer** on this three-person University of Arizona software development project and completed the majority of the application's design and technical implementation.

My work included:

- Developing the primary application interface and user experience
- Building JavaScript functionality and application logic
- Integrating MLB schedule, team, and stadium data
- Integrating Google Maps and Places functionality
- Connecting selected games with stadium locations and nearby hotel searches
- Developing the user flow from game discovery to travel planning
- Working with API responses and translating external data into usable interface elements
- Implementing responsive front-end layouts
- Testing, debugging, and refining the application
- Contributing to the overall product concept and technical architecture

The completed project received an **A** in the University of Arizona program.

## APIs & Data

### SportsData.io API

SportsData.io was used to retrieve MLB data required by the application, including Spring Training schedules, teams, and stadiums.

Team and stadium data is cached locally because that information changes relatively infrequently. Schedule data is retrieved on refresh because game information can change more frequently.

### Hotels.com API

The Hotels.com API was used to retrieve lodging information for destinations near selected Spring Training stadiums.

This allowed the application to connect game and stadium data with nearby hotel options so users could move from choosing a game to planning lodging within the same travel workflow.

### Google Maps & Places

Google Maps and Places functionality connects the baseball data with geographic information.

After selecting a game, users can view the corresponding stadium area and search for nearby hotels. Users can also navigate the map and perform searches around a selected location.

## Product & Technical Considerations

Building the application required combining data from separate systems into one coherent user experience.

Baseball schedules, teams, stadiums, geographic locations, maps, and nearby lodging results needed to work together while remaining understandable to the user.

The project provided hands-on experience with:

- API-driven product development
- Data flow between external services and user interfaces
- Designing interfaces around structured baseball data
- Translating technical constraints into product decisions
- Location-aware user experiences
- Client-side data caching
- Responsive interface development
- Iterative testing and debugging

## Technologies

- HTML5
- CSS3
- JavaScript
- jQuery
- Tailwind CSS
- SportsData.io API
- Hotels.com API
- Google Maps / Places API
- Local browser storage
- Git / GitHub

## Screenshots

### Spring Training game and stadium discovery

<img width="1384" alt="Spring Training Travel Planner game and stadium interface" src="https://user-images.githubusercontent.com/109550438/218866188-d11485c3-5060-4239-8715-606ca85cb462.png">

### Game selection and nearby hotel search

<img width="1384" alt="Spring Training Travel Planner hotel search interface" src="https://user-images.githubusercontent.com/109550438/218866206-9f7287bf-14d6-4f5d-a7de-13fe78a8f137.png">

### Stadium mapping and travel planning

<img width="1429" alt="Spring Training Travel Planner stadium map" src="https://user-images.githubusercontent.com/109550438/218866339-7a795d8b-53d0-4040-a5b3-0da4e6fd9968.png">

### Additional application views

![Spring Training Travel Planner application view](https://user-images.githubusercontent.com/109550438/218929735-cc8fc25f-b1de-4b87-abfc-f2f25bddf314.png)

![Spring Training Travel Planner application view](https://user-images.githubusercontent.com/109550438/218929899-4758b581-1a3c-4e85-a058-6c8ef304d018.png)

## Original Team

This application originated as a three-person project in a University of Arizona software development program.

- [Aaron DeVandry](https://github.com/adevandry), Primary Developer
- [Amanda Hardin](https://github.com/AHardin77)
- [Jeanna Vasquez-Garza](https://github.com/jeannav)

The original repository and complete development history are preserved through this GitHub fork.

## Project History

This repository is maintained as a portfolio copy of the original team project. GitHub's fork relationship preserves the original repository, commit history, branches, and contributor attribution.
