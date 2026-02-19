# smart-labo-2

A Flutter application with a feature-based folder structure.

## Project Structure

```
lib/
├── features/
│   ├── clock/
│   │   └── clock_screen.dart
│   └── settings/
│       └── settings_screen.dart
└── main.dart
```

## Features

- **Clock Screen**: A page displaying "Clock Page"
- **Settings Screen**: A page displaying "Settings Page"
- **Navigation**: Bottom navigation bar to switch between Clock and Settings pages

## Getting Started

1. Ensure Flutter is installed on your system
2. Run `flutter pub get` to install dependencies
3. Run `flutter run` to launch the application

## Navigation

The app uses a `BottomNavigationBar` to navigate between the two features:
- Clock (with clock icon)
- Settings (with settings icon)