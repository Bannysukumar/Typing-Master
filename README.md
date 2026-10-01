<!-- readme-seo: bannysukumar-professional-v4 -->

# Typing Speed Test

Typing Speed Test is an Android app. The Java package is `com.TypingMaster.Max`, and `MainActivity` loads an HTML typing page from `app/src/main/assets/index.html`.

## Overview

The bundled page title is "Typing Speed Test Game | CodingNepal". The HTML comment credits CodingNepal. The page shows a text field, typing text, and a time-left result. This repository packages that page inside an Android Gradle project. The GitHub repository name stays `Typing-Master`.

## Features

- Android entry point `MainActivity`
- Typing page in `app/src/main/assets/index.html` with a timer and result details

## Tech Stack

| Technology | Where it shows up |
|---|---|
| Java | `app/src/main/java/com/TypingMaster/Max/MainActivity.java` |
| Android Gradle | `build.gradle`, `settings.gradle`, `gradlew` |
| HTML | `app/src/main/assets/index.html` |

## Architecture

Android activity → HTML asset bundled in the app.

## Project Structure

```text
Typing-Master/
├── app/src/main/java/com/TypingMaster/Max/
├── app/src/main/assets/index.html
├── build.gradle
├── settings.gradle
└── gradlew
```

## Prerequisites

- Android Studio, or a JDK plus the Gradle wrapper

## Installation

```bash
git clone https://github.com/Bannysukumar/Typing-Master.git
cd Typing-Master
```

The default branch is `master`. Open the project in Android Studio.

## Usage

Run the `app` module. The typing UI is the HTML asset, which includes a time-left display.

## Contributing

Read [CONTRIBUTING.md](CONTRIBUTING.md) before opening a pull request.

## License

Licensed under MIT. See [LICENSE](LICENSE). The HTML file credits CodingNepal.

## Author

Banny Sukumar

GitHub: https://github.com/Bannysukumar
