# Mobile Development Coursework: Creating a food app - Part 4

## Sep 2024 - Jan 2025

## Associated with University of London

## Introduction

Run Online on Expo Snack - https://snack.expo.dev/@maryam222/foodapp

This React Native mini midterm project (part 4 out of 4) is a user-friendly restaurant and menu browser built with React Native and React Navigation. It offers a curated list of restaurants, each featuring a rich visual layout, estimated delivery time, and a detailed menu. Users can scroll through the home screen to explore different eateries like Joe's Gelato, Pizza Palace and Joe's Café, then tap on any restaurant to view its full menu. Selecting a menu item reveals a beautifully designed detail screen with images, descriptions, prices and nutritional info. With clean navigation and stylish components, this app delivers an intuitive food discovery experience.

## Getting Started

### Prerequisites

Before diving in, ensure you have the following installed:
1. **Node.js** (with npm - Node Package Manager)  
   You can download it from [Node.js official website](https://nodejs.org/).  
2. **Android Studio and Emulator** (if testing on an Android device)  
   Follow the official setup guide here: [Expo Docs - Android Studio Emulator](https://docs.expo.dev/workflow/android-studio-emulator/).  
3. **Expo CLI** (Command-Line Interface)  
   Used to simplify app development and testing.

### Setting Up Expo

1. Open your terminal or command prompt.
2. Install Expo CLI globally using npm:

   ```bash
   npm install -g expo-cli
   ```

3. Verify installation with:

   ```bash
   expo --version
   ```

### Running the App

1. Navigate to your project directory:

   ```bash
   cd Mobile-Development-University-of-London-Food-App-Part-4
   ```

2. Run the command to install the needed packages:

   ```bash
   npm install
   ```

3. Start the Expo development server:

   ```bash
   npm start
   ```

   This will launch the Expo developer tools in your default browser, providing you with options to test the app.

4. You can run the app in the following ways:
   - **Simulators:**  
     Use the displayed options to run the app on an Android or iOS simulator if they're set up.  
   - **Physical Device:**  
     Scan the QR code shown in the Expo developer tools as seen in the image below, using the **Expo Go** app. You can download it for [iOS](https://apps.apple.com/app/expo-go/id982107779) or [Android](https://play.google.com/store/apps/details?id=host.exp.exponent).

    ![fig](https://github.com/user-attachments/assets/c07fe067-602e-4493-8474-4099986fe7d3)

5. The app should now be running on your device or simulator!

### Troubleshooting

- If the app fails to start, ensure that no other processes are occupying the port (default is 19000). You can stop any running process by pressing `CTRL+C` in your terminal.
- For additional help, refer to the [Expo Documentation](https://docs.expo.dev/).

You should now see the app running correctly on your device/simulator!

Note: Code written between Start and End comments is my own. The rest was provided by the University of London, and other code and resources used has been credited.
