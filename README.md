# Food Fast Delivery - Mobile Application

## Overview

**Food Fast Delivery** is a mobile application built with **React Native**, **Expo**, **Tailwind CSS**, and **NativeWind** that provides fast food delivery services to users. It allows users to browse menus, place orders, track deliveries, and more—all from the convenience of their mobile devices.

This repository contains the source code for the mobile app.

## Technologies Used

- **React Native**: A popular framework for building cross-platform mobile applications using JavaScript and React.
- **Expo**: A framework and platform for universal React applications, making it easier to build, test, and deploy React Native apps.
- **Tailwind CSS**: A utility-first CSS framework for rapid UI development.
- **NativeWind**: A library that allows using Tailwind CSS classes directly in React Native applications.

## Features

- Browse a variety of food menus from different restaurants
- Add items to the cart and customize orders
- Real-time order tracking
- User authentication and profile management
- Push notifications for order status updates
- Payment integration (e.g., with Stripe or other services)
- Responsive and clean user interface with Tailwind CSS

## Installation

Follow the steps below to get the project up and running on your local machine.

### 1. Clone the repository

```bash
git clone https://github.com/your-username/food-fast-delivery.git
cd food-fast-delivery
```

## 2. Install dependencies
Make sure you have Node.js and npm installed. Then, run the following command to install all required dependencies:
npm install

Alternatively, if you prefer using Yarn, you can run:
```bash
yarn install
```
##3. Install Expo CLI (if not already installed)
If you don't have Expo CLI installed, you can install it globally using npm:
```bash
npm install -g expo-cli
```

##4. Start the development server
To start the project locally, run the following command:
```bash
expo start
```
This will start the development server and open the Expo DevTools in your browser. You can use a physical device or an emulator to preview the app.

##5 Running on a Physical Device
To run the app on a physical device, follow these steps:

Install the Expo Go app from the App Store (iOS) or Google Play (Android).
Scan the QR code displayed in the Expo DevTools to open the app on your device.
Folder Structure
Here’s a high-level overview of the project structure:
/food-fast-delivery
├── /assets             # Images and static assets
├── /components         # Reusable components (e.g., buttons, card components)
├── /constants          # Configuration constants (e.g., theme, API URLs)
├── /navigation         # React Navigation setup
├── /screens            # Application screens (e.g., Home, Profile, Cart)
├── /services           # API and data handling logic
├── /styles             # Tailwind and NativeWind styles
├── App.js              # Main entry point of the application
└── package.json        # Project dependencies and scripts

License
This project is licensed under the MIT License - see the LICENSE file for details.

Acknowledgements
React Native
Expo
Tailwind CSS
NativeWind
