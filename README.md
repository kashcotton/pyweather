<div align="center">
  <h1>PyWeather</h1>
  <p><b>A Material Design weather app with absolutely zero filter.</b></p>

[![Framework](https://img.shields.io/badge/Framework-Flutter-02569B.svg?logo=flutter)](https://flutter.dev/)
[![Web Stack](https://img.shields.io/badge/Web-HTML%20%7C%20CSS%20%7C%20JS-E34F26.svg)]()
[![Platform](https://img.shields.io/badge/Platform-Android%20%7C%20Web-3DDC84.svg?logo=android)]()
[![License](https://img.shields.io/badge/License-Apache_2.0-blue.svg)](LICENSE)
</div>

## About PyWeather

Despite the name, PyWeather has moved past its Python roots. It is now a dual-experience project: a lightweight web application built in HTML, CSS, and JavaScript, alongside a native Android application built in Flutter.

The idea is simple. We wanted a weather app that provides highly accurate, real-time data and looks incredibly clean—using Google's Material Design principles—but delivers the forecast the way someone actually talks when they step outside and it's freezing. 

By utilizing Flutter for the mobile build, the app is easier to maintain and provides a solid native experience on Android, while the web version keeps things accessible for anyone with a browser.

## Features

*   **Native Android App:** Compiled with Flutter for smooth performance on Android devices.
*   **Web App:** A straightforward, accessible counterpart built with standard web technologies.
*   **Material Design:** A clean UI that mirrors native Google applications, focusing on typography, layout, and dark mode support.
*   **Unfiltered Forecasts:** Dynamically generates aggressive, profane, and honest weather descriptions based on the current temperature, precipitation, and wind conditions.
*   **In-App Settings:** No need to configure `.env` files or API keys. All settings, including vulgarity levels, are managed directly through the app's user interface.
*   **Open-Meteo Integration:** Global, accurate weather data provided by the Open-Meteo API.

## Screenshots

| Clean Material UI | Vulgar Forecasts | Settings & Options |
| :---: | :---: | :---: |
| <img src="https://i.imgur.com/nDRYHaa.png?text=Material+UI" width="250"> | <img src="https://i.imgur.com/PvqoGKD.png?text=Vulgar+Weather+Alerts" width="250"> | <img src="https://i.imgur.com/CarI9wJ.png?text=In-App+Options" width="250"> |

## Installation & Setup

### Prerequisites
*   [Flutter SDK](https://flutter.dev/docs/get-started/install) (if you intend to build or run the Android app).
*   An Android device or emulator.

### Running the Flutter (Android) App

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/kashcotton/pyweather.git
    cd pyweather
    ```

2.  **Get dependencies:**
    ```bash
    flutter pub get
    ```

3.  **Run the application:**
    Ensure your device or emulator is running, then execute:
    ```bash
    flutter run
    ```
    *Note: You can adjust the app's behavior and vulgarity levels in the settings menu once it is running.*

### Running the Web App

Navigate to the web directory in the repository and open the `index.html` file in your browser, or host the directory on your preferred web server.

## Built With

*   **[Flutter](https://flutter.dev/) & Dart:** Used for the native Android application shell.
*   **HTML / CSS / JavaScript:** Used for the core web application logic and styling.
*   **[Open-Meteo API](https://open-meteo.com/):** For fast, keyless weather data.

## Credits & Acknowledgements

A massive thanks to **[colebolebole](https://github.com/colebolebole)** for creating the original Python and OpenWeatherMap iteration of this project. We worked on that version together, and this new Flutter/Web iteration was built directly on the foundation of that original concept. 

## Contributing

If you have ideas for new features, bug fixes, or just want to add some creative new insults to the weather generator, feel free to contribute. 

1. Fork the project.
2. Create your feature branch (`git checkout -b feature/NewFeature`).
3. Commit your changes (`git commit -m 'Add a new feature'`).
4. Push to the branch (`git push origin feature/NewFeature`).
5. Open a Pull Request.

## License

Distributed under the **Apache License 2.0**. See the `LICENSE` file for more information.

*Disclaimer: This app contains strong language and profanity by design.*
