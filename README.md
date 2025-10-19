# React Native Wallet App

A mobile wallet application built with React Native and Expo that allows users to manage their finances, track transactions, and monitor their balance.

## 📱 Live Demo Video

[Watch the live app](https://drive.google.com/file/d/1bV5ymKcjmM1jvFVYztmN26wBsSrBw_aQ/view?usp=sharing) - 

## 🔗 Related Repositories

- [Backend Repository](https://github.com/DjazzGh/React_Native_Wallet) - Link to the backend repository will be added here.

## ✨ Features

- User authentication and account management
- Real-time balance tracking
- Transaction history with detailed information
- Secure financial data handling
- Modern and intuitive UI design

## 📋 Prerequisites

- Node.js (v14 or higher)
- npm or yarn
- Expo CLI
- iOS Simulator or Android Emulator (optional for local testing)

## 🚀 Getting Started

1. Clone the repository
   ```bash
   git clone <repository-url>
   cd mobile
   ```

2. Install dependencies
   ```bash
   npm install
   # or
   yarn install
   ```

3. Set up environment variables
   - Create a `.env` file in the root directory based on the `.env.example` template
   - Fill in the required API endpoints and credentials

4. Start the development server
   ```bash
   npx expo start
   ```

5. Run on your preferred platform
   - Press `i` for iOS simulator
   - Press `a` for Android emulator
   - Scan the QR code with Expo Go app on your physical device

## 📁 Project Structure

```
mobile/
├── app/                 # Main application code
│   ├── (auth)/          # Authentication screens
│   ├── (root)/          # Main app screens
│   └── _layout.jsx      # App layout configuration
├── assets/              # Static assets like images and styles
├── components/          # Reusable UI components
├── constants/           # App constants and configuration
├── hooks/               # Custom React hooks
└── lib/                 # Utility functions and helpers
```

## 🛠️ Technologies Used

- [React Native](https://reactnative.dev/) - Mobile app framework
- [Expo](https://expo.dev/) - React Native toolchain
- [Expo Router](https://docs.expo.dev/router/introduction/) - File-based routing for Expo



