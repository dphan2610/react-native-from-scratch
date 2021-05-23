# react-native-tutorial-from-scratch

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

- Step 2: Download the build file from your Expo

- Step 3: Run:
```
xcrun simctl install booted <path to .app>
```


-----------------------
Build and deploy (Android):
- Step 1:






-----------------
References:
- https://reactnative.dev/docs/environment-setup
