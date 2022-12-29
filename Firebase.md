
# Firebase App

This app supported all type of the firebase functionality like Authentication, Analytic, Crashlytics and Storage.

## Firebase Installtion Guide

React Native Firebase requires a few steps. Installing the NPM module and Adding the Firebase config files

Follow the installtion Guide for iOS and Android https://rnfirebase.io/


## Initial Install

 - [Node.js](https://nodejs.org/en/)
 - [React Native CLI](https://www.npmjs.com/package/react-native-cli)
 - [npm](https://docs.npmjs.com/downloading-and-installing-node-js-and-npm/)


## App setup on Firebase

Log in to the [Firebase console](https://console.firebase.google.com/), then click Add project. 
Enter your App name and click on continue. Follow the link for [iOS](https://firebase.google.com/docs/ios/setup) and [Android](https://firebase.google.com/docs/android/setup) configuration on the firebase console.

## Install package for firebase

We are use the [react-native-firebase](https://github.com/invertase/react-native-firebase) module for React Native.It supports both iOS & Android platforms for all Firebase services. Check installation guild https://rnfirebase.io/.


## Authentication

#### Phone Authentication

You should install the below @react-native-firebase/auth packge for authentication.

```http
# Install & setup the app module
yarn add @react-native-firebase/app

# Install the authentication module
yarn add @react-native-firebase/auth

# If you're developing your app using iOS, run this command
cd ios/ && pod install
```

You should enable for phone authentication service on firebase. Go to Authentication > Sign-In Method > Add Provider > Phone > Enable the service.

![App Screenshot](https://i.ibb.co/bKbMZbY/Screenshot-2022-12-29-at-4-59-49-PM.png)


#### Email Authentication

You should install the below @react-native-firebase/auth packge for authentication.

```http
# Install & setup the app module
yarn add @react-native-firebase/app

# Install the authentication module
yarn add @react-native-firebase/auth

# If you're developing your app using iOS, run this command
cd ios/ && pod install
```

Enable email authentication service on firebase. Go to Authentication > Sign-In Method > Add Provider > Phone > Enable the service.

![App Screenshot](https://i.ibb.co/cch5wkp/Screenshot-2022-12-29-at-5-17-09-PM.png)


#### Google Authentication

Install the below @react-native-google-signin/google-signin packge for google signin.

```http
# Install & setup the app module
@react-native-google-signin/google-signin

# If you're developing your app using iOS, run this command
cd ios/ && pod install
```

Referral the link for more information https://rnfirebase.io/auth/usage

## Analytics

Analytics collects usage and behavior data for the app. Install the @react-native-firebase/analytics sdk for tracking and custom events.

```http
# Install the analytics module
yarn add @react-native-firebase/analytics

# If you're developing your app using iOS, run this command
cd ios/ && pod install
```

You can check the custom event data on the debugView and Dashbord.

Note: The initial data logged usually takes up to 24 hours to display and 3-4 hours delay for the succeeding data. DebugView on the other hand, shows you data   

