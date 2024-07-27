# QR Code Scanner App

This is a simple QR code scanner app built using Flutter. The app scans QR codes and launches the URL if the QR code contains a valid URL.

## Features

- Scan QR codes using the device camera
- Display the scanned result
- Open the scanned URL in a browser if it is valid

## Getting Started

Follow these instructions to get a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

- [Flutter SDK](https://flutter.dev/docs/get-started/install)
- [Dart SDK](https://dart.dev/get-dart)
- [Android Studio](https://developer.android.com/studio) or [Visual Studio Code](https://code.visualstudio.com/) with Flutter extension

### Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/qrcode-scanner-app.git
   cd qrcode-scanner-app

2. Install the dependencies:
   ```sh
   flutter pub get

3. Run the app:
   ```sh
   flutter run

### Permissions

The app requires camera permissions to scan QR codes. Make sure to grant camera permissions when prompted.

### Usage

- Open the app.
- Point the camera at a QR code.
- The app will automatically scan the QR code and display the result.
- If the scanned result is a valid URL, you can open it by pressing the "Open URL" button.

### Custom Icon

A custom app icon is available in the assets folder. To use the custom icon, ensure that your pubspec.yaml file includes the following:
  
  flutter:
    assets:
      - assets/icon/icon.png

Also, update your `android/app/src/main/AndroidManifest.xml` and `ios/Runner/Info.plist` files to reference the custom icon.

### Built With

- Flutter - The framework used
- QR Code Scanner - Plugin to scan QR codes
- URL Launcher - Plugin to launch URLs in the browser
- Permission Handler - Plugin to handle permissions

### Contributing

Feel free to contribute to the project by opening issues or submitting pull requests.

### License

This project is licensed under the MIT License - see the `LICENSE` file for details.

### Acknowledgments

Special thanks to the Flutter and Dart community for their amazing resources and support.







