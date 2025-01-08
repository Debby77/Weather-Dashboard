This is one of my very first DevOps projects.
Topic: Building a weather data collection system using AWS S3 and OpenWeather API
Source: 30 days DevOps Challenge- Weather Dashboard

Project Overview
This project combines
a. External API Integration (Open Weather API)
b. AWS S3
c. IaaC
d. Version Control (Git)
e. Python Development
f. Error/Bug fixes
g. Environment Management

Features
This fetches real time weather data for multiple cities (This project focused on Seattle, New York and Philadelphia)
This displays temperature in °F, Humidity, and Weather Conditions
This automatically stores weather data in AWS S3
This project supports weather tracking for multiple cities
This project timestamps all data for historical tracking

Technical Architecture
Language: Python 3.x
CLoud Provider: AWS
External API: Openweather API
Dependencies:
boto3(AWS SDK)
python-dotenv
requests

# Project Structure

weather-dashboard/
src/
**init**.py
weather_dashboard.py
tests/
data/
.env
.gitignore
requirements.txt

Day 1 Project Reaction

## Setup Instructions

1. Clone the repository:
   --bash
   git clone
