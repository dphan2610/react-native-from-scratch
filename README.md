# react-native-tutorial-from-scratch

IMPORTANT NOTE: this is OLD, a lot of things are discontinued, or no longer avaialble.

Distilled step-by-step guide to build and deploy React Native apps on Android and iOS.

- Step 1: Buy a Mac computer (Macbook, iMac, Mac Pro), and buy an iPhone

- Step 2: Download Node.js (macOS Installer): https://nodejs.org/en/download/

- Step 3: Open the downloaded .pkg file, and follow instructions on screen to install

- Step 4: Open Terminal and enter:

```
node -v
```
Verify the version is latest (for example, v14.17.0)

- Step 5: Install Expo CLI (using Terminal):
```
sudo npm install -g expo-cli
```

- Step 6: Create your React Native project:
```
expo init LegendaryProject
```

- Step 7: cd to your project, then start:
```
cd LegendaryProject
npm start
```
Verify that you can see QR code on your terminal or browser

- Step 8: Go to your iPhone, download Expo Go app: https://expo.io/client

- Step 9: Open Camera app on your iPhone, and scan the QR code in step 7.



-----------------------
Build and deploy (iOS):
- Step 1: Create an Expo account: https://expo.io/signup

- Step 2: Create Apple account: https://appleid.apple.com/account

- Step 3: Enroll in Apple Developer Program (costs $99)

- Step 4: Run:
```
expo build:ios -t archive
```

- Step 5: Go to App Store Connect, click the plus icon and create a New App

- Step 6: Download the .ipa file from your Expo (generated from step 4)

- Step 7: Install Transporter on your Mac

- Step 8: Drop .ipa file in Transporter


-----------------------------------
Run on Simulator (iOS):
- Step 1: Run:
```
expo build:ios -t simulator
```

- Step 2: Download and unzip the build file from your Expo

- Step 3: Use xCode to open Simulator

- Step 4: Drag and drop the downloaded .app file to the Simulator

-----------------------
Build and deploy (Android)
- Step 1: Register for developer account on Google Play (costs $25)

- Step 2: Run:
```
expo build:android -t app-bundle
```

- Step 3: Download the .apk file from Expo web

- Step 4: Go to Google Play Console, and have fun. Things to remember:
+ Drop .apk file there
+ Enter app details, like description, screenshots, etc.

-----------------------
Run on Simulator (Android):

- Step 1: Download and install Android Studio and SDK: https://developer.android.com/studio

- Step 2: Run:
```
expo build:android -t apk
```

- Step 3: Download the .apk build file from your Expo

- Step 4: Open an emulator from Android Studio, Tools -> AVD Manager

- Step 5: Drop .apk file into emulator

------------------------
Run on device (Android):

- Step 1: Download Expo Go app

- Step 2: Open Expo Go app, and scan QR code

-----------------
References:
- https://reactnative.dev/docs/environment-setup
