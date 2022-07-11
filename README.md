
## About
![WhatsApp Image 2022-07-12 at 2 01 52 AM](https://user-images.githubusercontent.com/88125901/178353301-3b0ebd97-bafb-40d8-bd24-c8f164809578.jpeg)

WeatherApp is a simple weather forecast app, which uses [OpenWeatherMap](https://openweathermap.org/) API to fetch 5 day / 3 hour forecast data based on given location. This application, developed in the Android Studio environment, processes the temperature, wind, pressure, weather and humidity data fetched in JSON format and displays them to the user.

### Features
Some of the features the project includes:

- Weather info by current location
- 5 Day Forecast
- Current humidity, wind and real feel info
- Search weather by location
- Secure API key

### Built with

- [Android Studio](https://developer.android.com/studio) - Android Studio is the official Integrated Development Environment (IDE) for Android app development, based on IntelliJ IDEA.
- [OpenWeatherMap](https://openweathermap.org/) - OpenWeatherMap is an online service that provides global weather data via API, including current weather data, forecasts, nowcasts and historical weather data for any geographical location.

## Usage

In order to use the project, you first need your own OpenWeatherMap API key:

1. Sign up on [OpenWeatherMap](https://openweathermap.org/) to get your api keys.
2. Once you've registered go to your Account > My API keys. The 'Default key' is what you'll need.
3. Set the `ApiKey` property in [`gradle.properties`](./gradle.properties) file to your api key.
```properties
ApiKey = YOUR_OPENWEATHERMAP_API_KEY
```



