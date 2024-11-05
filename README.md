JDBBen Setup Kit
This project is a preconfigured starter kit using Expo, NativeWind, and React Native, designed to simplify the setup for developers looking for a fast, flexible environment to build mobile apps with a modern design system. This package is available on GitHub, making it easy start for your project 

Features
Expo for seamless cross-platform development.
NativeWind for Tailwind CSS-like styling with React Native.
React Native core configurations to streamline app creation.
Preconfigured CSS and Utility Classes to speed up development.
Installation
To install the setup kit in your new project, you can clone this repository, which has only the necessary base for a new project:
bash
Copy code
git clone https://github.com/jdbben/expo-Nativewind.git
cd expo-Nativewind

Important
After cloning the repository, make sure to create a file called expo-env.d.ts and add the following line:
typescript
Copy code
/// <reference types="expo/types" />

This will provide you with all required dependencies and configurations.
Getting Started
Install Required Dependencies: If the package doesn't automatically install all dependencies, run:
bash
Copy code
npx expo install nativewind tailwindcss react-native-reanimated react-native-safe-area-context


Initialize Tailwind Configuration: If Tailwind CSS requires additional configuration, initialize it by running:
bash
Copy code
npx tailwindcss init
Then, replace the content of the generated tailwind.config.js with the provided configuration in this kit.
Running on WSL: If you're using WSL (Windows Subsystem for Linux), use the following command to start your Expo project and ensure it connects with your Android or iOS device:
bash
Copy code
npx expo start --tunnel


Usage

Contributing
If you'd like to contribute, please fork the repository, make your changes, and submit a pull request. Contributions are welcome!
