# Weather Station
This repository contains a Rust program that fetches and displays weather information from the OpenWeatherMap API based on user input for city name and country code.

Description
The program prompts the user to input the name of a city and its country code. It then sends a request to the OpenWeatherMap API to fetch weather information for the specified location. The retrieved data includes weather description, temperature, humidity, pressure, and wind speed. The program then displays this information to the user in a formatted and colored output.

Dependencies
serde - A Rust library for serializing and deserializing data structures
colored - A Rust library for terminal text coloring
reqwest - A Rust library for making HTTP requests
Usage
Clone the repository to your local machine.
Make sure you have Rust installed. You can install it from Rust's official website.
Navigate to the cloned directory in your terminal.
Compile and run the program using the following command:
