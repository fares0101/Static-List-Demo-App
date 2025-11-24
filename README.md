# Static List Demo App (Flutter)

A simple Flutter application that displays a predefined static list of items stored locally inside the app. This project is suitable for demonstrating basic UI layout, static data rendering, and clean code structure.

## Features

* Displays a list of 3–5 static items
* Data fetched from a local hardcoded `List<String>`
* Single-screen UI
* Clean and minimal design
* No backend, no user input, no storage

## Screenshots

Place your screenshots inside a folder called `screenshots/`.

Example structure:

```
project_root/
  lib/
    main.dart
  screenshots/
    list_screen_1.png
    list_screen_2.png
    list_screen_full.png
  README.md
```

## How It Works

The app contains a simple array:

```
final List<String> items = [
  "Item 1: Welcome",
  "Item 2: Example Data",
  "Item 3: Static Content",
  "Item 4: Local List",
  "Item 5: Simple Display",
];
```

This list is rendered using a `ListView.builder` and displayed inside `Card` widgets.

## Getting Started

### 1. Clone the Repository

```
git clone <your-repo-link>
cd static-list-demo
```

### 2. Run the App

Make sure Flutter SDK is installed:

```
flutter pub get
flutter run
```

### 3. Build APK

```
flutter build apk --release
```

The APK will be found here:

```
build/app/outputs/flutter-apk/app-release.apk
```

## Project Structure

```
lib/
  main.dart
screenshots/
  list_screen_1.png
  list_screen_2.png
  list_screen_full.png
README.md
```

## Requirements

* Flutter SDK
* Dart SDK
* Android Studio or VS Code (optional)

## License

You may include MIT, Apache 2.0, or leave it without a license depending on your preference.

---

This project is ideal for showcasing simple mobile development skills such as layout, static data handling, and clean UI implementation.
