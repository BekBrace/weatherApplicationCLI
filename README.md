# Weather Station
This repository contains a Rust program that fetches and displays weather information from the OpenWeatherMap API based on user input for city name and country code.
![image](https://github.com/BekBrace/weatherApplicationCLI/assets/60483846/281078b5-e646-4211-b6b8-460eddf5b258)

Description
The program prompts the user to input the name of a city and its country code. It then sends a request to the OpenWeatherMap API to fetch weather information for the specified location. The retrieved data includes weather description, temperature, humidity, pressure, and wind speed. The program then displays this information to the user in a formatted and colored output.

Dependencies
serde - A Rust library for serializing and deserializing data structures
colored - A Rust library for terminal text coloring
reqwest - A Rust library for making HTTP requests
Usage
1- Clone the repository to your local machine.
2- Make sure you have Rust installed. You can install it from Rust's official website.
3- Navigate to the cloned directory in your terminal.
4- Compile and run the program using the following command:
```bash
cargo run
```
1- Follow the prompts to enter the city name and country code for which you want to fetch weather information.
2- View the displayed weather information.
3- Optionally, you can search for weather in another city by typing 'yes' when prompted.

# API Key
To use this program, you need to obtain an API key from OpenWeatherMap and replace the placeholder API key in the code with your own.
```rust
let api_key = "YOUR_API_KEY_HERE";
```
# License
This project is licensed under the MIT License
