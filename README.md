# Match Tracker

A real-time match tracking mobile application built with React Native and Expo.

## Features

- Live match updates via WebSocket connection
- Team and player statistics tracking
- Real-time points and rankings
- Responsive design for various screen sizes

## Tech Stack

- React Native
- Expo
- Redux Toolkit (RTK Query)
- TypeScript
- WebSocket for real-time updates

## Getting Started

### Prerequisites

- Node.js
- npm or yarn
- Expo CLI

### Installation

1. Clone the repository
2. Install dependencies:
```bash
npm install
```

### Running the App

Start the development server:
```bash
npm start
```

This will open Expo DevTools in your browser. You can then:
- Run on iOS simulator
- Run on Android emulator
- Scan QR code with Expo Go app on your device

## Project Structure

```
src/
├── app/          # Application setup
├── components/   # Reusable components
├── entities/     # Domain entities (Match, Team, Player)
├── widgets/      # Complex UI components
└── utils/        # Utility functions
```

## API

The application connects to:
- REST API: `https://app.ftoyd.com/fronttemp-service`
- WebSocket: `wss://app.ftoyd.com/fronttemp-service/ws`
# Match Tracker

A real-time match tracking mobile application built with React Native and Expo.

## Features

- Live match updates via WebSocket connection
- Team and player statistics tracking
- Real-time points and rankings
- Responsive design for various screen sizes

## Tech Stack

- React Native
- Expo
- Redux Toolkit (RTK Query)
- TypeScript
- WebSocket for real-time updates

## Getting Started

### Prerequisites

- Node.js
- npm or yarn
- Expo CLI

### Installation

1. Clone the repository
2. Install dependencies:
```bash
npm install
```

### Running the App

Start the development server:
```bash
npm start
```

This will open Expo DevTools in your browser. You can then:
- Run on iOS simulator
- Run on Android emulator
- Scan QR code with Expo Go app on your device

## Project Structure

```
src/
├── app/          # Application setup
├── components/   # Reusable components
├── entities/     # Domain entities (Match, Team, Player)
├── widgets/      # Complex UI components
└── utils/        # Utility functions
```

## API

The application connects to:
- REST API: `https://app.ftoyd.com/fronttemp-service`
- WebSocket: `wss://app.ftoyd.com/fronttemp-service/ws`
