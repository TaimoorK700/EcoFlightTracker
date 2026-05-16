# EcoFlightTracker

Eco Flight Tracker is a simple web-based calculator that estimates the carbon dioxide emissions produced by a flight. The project was initially written in Python and was later converted into a static HTML website with the help of AI so that it could be deployed and accessed online.

## Live Website

View the live website here:

[https://taimooork2007.github.io/eco-flight-tracker/](https://taimoork700.github.io/eco-flight-tracker/)

## About the Project

Air travel produces a significant amount of carbon emissions, but these numbers can be difficult to understand in practical terms. Eco Flight Tracker helps make flight emissions easier to interpret by converting estimated CO2 output into practical comparisons.

The website estimates a flight's CO2 emissions and compares the result to:

- the number of trees needed to absorb the emissions in one year
- the equivalent emissions from household electricity use
- the amount of time a small city would need to rely on renewable electricity to offset the flight

The goal of this project is not to provide perfectly exact aviation emissions data, but to make the environmental impact of flights easier to visualize and understand.

## Features

- Calculate estimated flight emissions by entering a custom flight range in kilometers
- Calculate estimated emissions for selected destination cities from Dubai, UAE
- Choose from multiple aircraft types
- Estimate total CO2 emissions in kilograms
- Convert emissions into tree absorption equivalents
- Compare flight emissions to typical household electricity-related emissions
- Estimate how long a small city would need to use renewable electricity to offset the flight emissions
- Runs directly in the browser as a static website

## How It Works

The user first selects a calculation method.

### Calculate by Range

The user enters the flight distance in kilometers.

### Calculate by City

The departure city is set to Dubai, UAE, and the user selects a destination city from a predefined list.

After choosing the calculation method, the user selects an aircraft. Each aircraft has an approximate fuel-burn factor. The website uses this factor along with the flight distance to estimate total CO2 emissions.

The calculator then displays the result in several more understandable forms, including tree absorption equivalents, household electricity comparisons, and small-city renewable energy comparisons.

## Technologies Used

- Python for the original version
- HTML for the deployed web version
- AI-assisted conversion from Python to a static website

## Project Structure

eco-flight-tracker/

- index.html
- README.md

## How to Run Locally

To run the project on your own computer:

1. Download or clone this repository.
2. Open index.html in any modern web browser.
3. Use the form to calculate estimated flight emissions.

No installation or external setup is required.

## Notes on Accuracy

The calculations used in this project are approximate and should not be treated as official aviation emissions data. Actual flight emissions depend on many factors, including aircraft configuration, passenger load, weather, routing, altitude, engine performance, airline operations, and airport conditions.

This project is intended for educational and awareness purposes.

## Author

Made by Taimoor Khawaja.
