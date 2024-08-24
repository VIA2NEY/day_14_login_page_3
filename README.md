## Flutter Beautiful Login Page UI Design and Animation - Day 14


### [Watch it on Youtube](https://youtu.be/txvyAO894DY)


## Development Setup
Clone the repository and run the following commands:
```
flutter pub get
flutter run
```

## ScreenShot

<img src="assets/screenshot/one.png" height="500em" />




Here's the README.md documentation for your Login_UI version 3 project:

markdown
Copier le code
# Login_UI Version 3

A modern and visually appealing login interface built with Flutter. This project demonstrates the use of animations and responsive design to create an engaging user experience.

## Project Structure

```plaintext
lib/
├── main.dart
├── home_page.dart
└── animation/
    └── fade_animation.dart
main.dart
The entry point of the application. This file initializes the Flutter app and sets up the HomePage as the main screen.

home_page.dart
This file defines the UI for the login page. The page is divided into two sections:

Header Section: A gradient background with text animations.
Form Section: Contains text fields for email/phone and password, along with buttons for login and social media options.
Key Components:

A gradient background using LinearGradient.
Animated text for the "Login" and "Welcome Back" messages.
A form with input fields for the user's credentials.
Social media buttons for alternative login options.
fade_animation.dart
A custom animation widget that applies a fade and translate effect to its child widgets. It uses the simple_animations package to create smooth transitions.

Key Components:

FadeAnimation: A widget that wraps around any child widget to apply the fade and translation effects with a specified delay.
Assets
Ensure that the following assets are included in your assets directory and listed in the pubspec.yaml file:

background.png
background-2.png
Installation
Clone the repository:
bash
Copier le code
git clone https://github.com/yourusername/Login_UI_v3.git
Navigate to the project directory:
bash
Copier le code
cd Login_UI_v3
Install the dependencies:
bash
Copier le code
flutter pub get
Run the app:
bash
Copier le code
flutter run
Dependencies
flutter: SDK for building the application.
simple_animations: A package for creating custom animations.
Make sure to add the simple_animations dependency to your pubspec.yaml:

yaml
Copier le code
dependencies:
  flutter:
    sdk: flutter
  simple_animations: ^4.0.0
Screenshots
Include screenshots of your login UI here to showcase the design and animations.