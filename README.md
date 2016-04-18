# WebRTC Cordova

Cordova crossplatform application to test WebRTC camera API on mobile device based on [GitHub samples](https://github.com/webrtc/samples/tree/gh-pages/src/content/devices/input-output)

## Requirements
```
npm install -g cordova
```

To build and run application on android:
- Android API 22 with "ANDROID_HOME" env variable set to android sdk path
- JDK 1.8 with "JAVA_HOME" env variable set


## Setup project
```
cordova prepare
```

This command will:
- Install platforms declared in config.xml
- Download plugins declared in config.xml

## Build and run application
To run the application on an android phone plugged to your computer
```
cordova run android
```
To run the application on a browser
```
cordova run browser
```