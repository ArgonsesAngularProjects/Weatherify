# Weatherify

Weatherify is a simple Angular project that allows you to check the weather for a specific city. It utilizes the OpenWeather API to fetch weather data based on the city name you provide.

## Features

- **City Weather:** Enter the name of a city, and Weatherify will display the current weather conditions for that location.

## Getting Started

To get started with Weatherify, follow these steps:

1. Clone the repository:

`git clone https://github.com/ArgonsesAngularProjects/Weatherify.git`

2. Navigate to the project directory:

`cd Weatherify`

3. Install dependencies:

`npm install`

4. Obtain an API key from [OpenWeather](https://openweathermap.org/api) and replace `apiKey` in the `src/app/weather.service.ts` file with your API key.

5. Build and run the project:

<b> ng serve</b>

6. Open your web browser and visit `http://localhost:4200/` to use Weatherify.

## Usage

1. Enter the name of the city for which you want to check the weather in the input field.

2. Click the "Get Weather" button.

3. Weatherify will fetch and display the current weather conditions for the specified city.

## Credits

Weatherify uses the [OpenWeather API](https://openweathermap.org/api) to retrieve weather data.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
