# VeloStore

An Android application store that allows users to browse, download, and install Android applications directly on their devices.

## Overview

VeloStore is a lightweight Android app store that provides an alternative way to discover and install Android applications. The app connects to a backend service that manages a catalog of applications, allowing users to:

- Browse available applications with icons and descriptions
- Search for specific apps
- Download and install APK files directly
- Manage app installations

The apps available in this store are created by the VeloCodes team, primarily developed by Daniel.

## Key Features

- **Direct APK Installation**: Download and install Android applications without Google Play Store
- **Multi-Architecture Support**: Supports different CPU architectures (arm64-v8a, armeabi-v7a, x86, x86_64)
- **Modern UI**: Clean Material Design interface with smooth animations
- **Search Functionality**: Easily find apps by name
- **Download Management**: Track download progress and manage downloads
- **Cache Management**: Automatically cleans up after successful installations

## Technical Architecture

### Android App
- Built with Kotlin
- Uses MVVM architecture pattern
- Implements Retrofit for REST API communication
- Utilizes Coil for image loading
- Integrates coroutines for asynchronous operations

### Backend System
- PHP-based administration panel for managing app listings
- JSON-based API for serving app metadata
- Telegram bot integration for remote app management
- Web interface for easy administration

## Prerequisites

- Android 5.0 (API level 21) or higher
- Internet connection
- Permission to install apps from unknown sources

## Installation

1. Download the APK file from releases
2. Enable "Install from Unknown Sources" in your device settings
3. Install the APK
4. Launch VeloStore and start browsing apps

## Usage

1. Launch the app to see a list of available applications
2. Tap the search icon to find specific apps
3. Select an app to view details
4. Tap "INSTALL" to download and install the app
5. Grant necessary permissions when prompted

## Development

### Building from Source

1. Clone the repository
2. Open in Android Studio
3. Sync Gradle dependencies
4. Build and run

### Dependencies

- AndroidX Libraries
- Retrofit & Gson for networking
- Coil for image loading
- Material Design Components
- Kotlin Coroutines

## Backend Administration

The backend includes:
- Web administration panel (PHP)
- Telegram bot for remote management
- JSON data storage for app listings

To set up the backend:
1. Deploy the PHP files to a web server
2. Configure the Telegram bot with your token
3. Set up the webhook for the bot
4. Access the web interface to manage apps

## About the Creator

This app store and the applications within it are developed by Daniel from the VeloCodes team.

Connect with the creator:
- Telegram ID: [@velovpn](https://t.me/velovpn)
- Telegram Channel: [@eivun](https://t.me/eivun)

## Security

- Apps are downloaded over HTTPS
- APK integrity verification
- Permission-based access control
- Admin-only backend access

## Contributing

Contributions are welcome! Please fork the repository and submit pull requests with your improvements.

## License

This project is licensed under the MIT License - see the LICENSE file for details.
