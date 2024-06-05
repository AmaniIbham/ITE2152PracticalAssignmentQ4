# ITE2152PracticalAssignmentQ4
Extended weather app to pull weather information based on selected location


# WeatherApp

WeatherApp is an Android application that provides weather information based on a selected city. The app fetches data from the OpenWeatherMap API and displays the current weather, temperature, humidity, wind speed, and visibility.

# Features

- Select a city from a predefined list.
- Fetch and display weather information including temperature, weather description, humidity, wind speed, and visibility.
- Display weather icon based on the weather description.
- Save the last searched city using SharedPreferences and load it when the app starts.

# Prerequisites

- Android Studio
- An Android device or emulator
- OpenWeatherMap API key

# Setup

1. Clone the repository:
    ```sh
    git clone https://github.com/your-username/WeatherApp.git
    ```

2. Open the project in Android Studio.

3. Obtain an API key from [OpenWeatherMap](https://home.openweathermap.org/users/sign_up).

4. Add your API key in `MainActivity.java`:
    ```java
    private static final String API_KEY = "YOUR_API_KEY";
    ```

5. Run the app on your device or emulator.

# Usage

1. Open the app.
2. Select a city from the dropdown list.
3. The app will automatically fetch and display the weather information for the selected city.

# Project Structure

- `MainActivity.java`: The main activity that handles the UI and weather data fetching.
- `activity_main.xml`: The main layout file that defines the UI components.
- `strings.xml`: Contains the array of city names.
- `AndroidManifest.xml`: Defines essential information about your app.

# Dependencies

- [Google Play Services Location](https://developers.google.com/android/reference/com/google/android/gms/location/package-summary)
- [Geocoder](https://developer.android.com/reference/android/location/Geocoder)
- [OpenWeatherMap API](https://openweathermap.org/api)

