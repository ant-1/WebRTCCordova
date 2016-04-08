# WebRTC Cordova

Cordova crossplatform application to test WebRTC API on mobile device

## Requirements
```
npm install -g cordova
```

To build and run application on android:
- Android API 22 with "ANDROID_HOME" env variable set to android sdk path
- JDK 1.8 with "JAVA_HOME" env variable set

## Adding platform (android, browser,...)
```
cordova platform add android
```
or/and
```
cordova platform add browser
```

## Update new plugin referenced in config.xml
```
cordova prepare
```

## Build and run application
To run the application on an android phone plugged to your computer
```
cordova run android
```
To run the application on a browser
```
cordova run browser
```