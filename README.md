# Flutter issue using iframe with Safari mobile

This project describe a Flutter issue on Safari mobile when the app is embedded on iframe.

## Follow this instruction to reproduce the issue

### 1. Run the Flutter App on port 5000 in release mode

`$ cd flutter_app`

`$ flutter run -d chrome --web-port 5000 --release`

    - The flutter_app is a default Flutter application without any changes.

### 2. Use [Web Server for Chrome](https://chrome.google.com/webstore/detail/web-server-for-chrome/ofhbbkphhbklhfoeikjpcbhemlocgigb) to provide the Host Website on [http://127.0.0.1:8887](http://127.0.0.1:8887)

    - Choose the host_website folder to provide on Web Server for Chrome

### 3. Open iOS Simulator (iOS 15.4) and select the iPhone 13

### 4. Open Safari in iOS Simulator and enter on [http://127.0.0.1:8887](http://127.0.0.1:8887)

### 5. Try to click on increment button and see that we can't click on buttons