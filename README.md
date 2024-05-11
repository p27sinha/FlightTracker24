# FlightTracker24 API Project 
FlightRadar24 API project in Python

## Overview
This project utilizes the FlightRadar24 API to fetch historical flight data for analysis and visualization. The primary goal is to plot flight positions for a specific airline and aircraft type on a geographical map.

## Requirements
- Python 3.10
- FlightRadar24 Python API (install using pip install FlightRadar24)
- Pandas (install using pip install pandas)
- Matplotlib (install using pip install matplotlib)


## Usage
- Clone this repository to your local machine.
- Install the required Python libraries mentioned in the Requirements section.
- Obtain your FlightRadar24 API credentials (API key, etc.) from the official FlightRadar24 website.
- Update the code in main.py with your API credentials and desired parameters (airline ICAO code, aircraft type, etc.).
- Run main.py to fetch historical flight data and plot flight positions.

### Code Structure
- main.py: Main Python script that fetches flight data using the FlightRadar24 API and plots flight positions.
- FlightRadar24API.py: Python module for interacting with the FlightRadar24 API.
- README.md: Project documentation.

## Configuration
You may need to update the following variables in main.py:

API_KEY: Your FlightRadar24 API key.
airline_icao: ICAO code of the airline you want to track (e.g., "SWA" for Southwest Airlines).
aircraft_type: Type of aircraft you want to track (e.g., "B38M" for Boeing 737 MAX 8).
Plotting
The plotted flight positions are displayed using Matplotlib. The scatter plot shows the geographical locations (longitude and latitude) of flights for the specified airline and aircraft type.

## Notes
Ensure that your FlightRadar24 API key is valid and has the necessary permissions to access historical flight data.
The project currently fetches historical flight data for a single airline and aircraft type. You can modify the code to fetch data for different criteria or time periods.
# Still a work in progress
