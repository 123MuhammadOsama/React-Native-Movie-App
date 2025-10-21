# Movie App

A mobile application built with React Native and Expo that allows users to browse, search, and save their favorite movies.

## 📱 Features

- Browse trending and popular movies
- Search functionality for finding specific movies
- Detailed movie information pages
- User profile management
- Save favorite movies
- Tab-based navigation
- Responsive design with TailwindCSS/NativeWind

## 🛠 Tech Stack

- React Native
- Expo Router
- TypeScript
- TailwindCSS/NativeWind
- Appwrite (Backend)

## 📂 Project Structure

```
├── app/                   # Main application routes
│   ├── (tabs)/           # Tab-based navigation
│   └── movie/            # Movie detail pages
├── assets/               # Static assets
├── components/           # Reusable UI components
├── constants/            # Constants and assets mapping
├── interfaces/           # TypeScript interfaces
├── services/            # API and data fetching logic
└── types/               # TypeScript type definitions
```

## 🚀 Getting Started

### Prerequisites

- Node.js
- npm or yarn
- Expo CLI

### Installation

1. Clone the repository:
```bash
git clone <repository-url>
```

2. Install dependencies:
```bash
npm install
# or
yarn install
```

3. Create a `.env` file with necessary environment variables

4. Start the development server:
```bash
npx expo start
```

## 📱 Running the App

- iOS: Press `i` in the terminal or run on iOS simulator
- Android: Press `a` in the terminal or run on Android emulator
- Web: Press `w` in the terminal to run in web browser

## 🔧 Configuration Files

- `app.json` - Expo configuration
- `babel.config.js` - Babel configuration
- `tailwind.config.js` - TailwindCSS configuration
- `tsconfig.json` - TypeScript configuration
- `metro.config.js` - Metro bundler configuration

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details