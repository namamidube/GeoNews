# GeoNews

## Table of Content
* [Overview](#overview)

* [Features](#features)

* [Technologies Used](#technologies-used)

* [Project Architecture](#project-architecture)

* [Conclusion](#conclusion)

## Overview
The GeoNews project is a user-centric system designed to retrieve real-time news from various feeds and add geographic tags with precise latitude and longitude coordinates (Geo-Tags) through NLP and ML models. The application provides an interface for users to visualize news events on a geospatial map of India in real-time.

Google Maps is integrated into the UI, displaying news updates from the past six to twelve hours on the map, allowing users to quickly identify significant events and trends across the country.


## Features
* Real-Time News Retrieval: Collects news from various sources in real-time.
* Geographic Tagging: Utilizes NLP and ML models to add precise geographic tags (latitude and longitude coordinates) to news articles.
* Interactive Map Display: Integrates Google Maps into the UI to visually display news events. Shows news updates from the past six to twelve hours on the map of India.
* User Interface: Developed using Flutter to ensure smooth operation across multiple devices, providing a seamless and intuitive user experience.
* User Benefits: Allows users to visualize real-time news events on a map and enables quick identification of significant events and trends across the country.


## Technologies Used:
* FrontEnd 
    * Flutter, Google Maps
* BackEnd Database and Query Engine (PhP)
    * SpatiaLite (Light Weight Spatial Database)
* Backend Processing
    * Using Natural Language Toolkit (NLTK) and AI/ML for extracting City names for the News feeds


## Project Architecture:
![alt text](<Data Flow.png>)

## Conclusion:
GeoNews lets users track real-time news events from all over India on an interactive map, helping them stay informed and quickly understand where things are happening. By using advanced NLP and ML models, GeoNews accurately tags news with exact locations. The app's friendly interface, built with Flutter, works smoothly on different devices, and Google Maps integration makes it easy to see news updates on the map. This project not only helps users follow current events but also shows the geographic context clearly, making it a valuable tool for anyone who wants to stay updated on what's happening across India.