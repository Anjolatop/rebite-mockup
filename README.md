# Rebite – Smart Food Rescue

A gamified marketplace mobile app that matches surplus/imperfect food from farmers and restaurants to consumers, aligned with UN SDGs 2 & 12.

## 🎯 Project Overview

Rebite is a React Native mobile app prototype that demonstrates a sustainable food marketplace concept. The app connects farmers and restaurants with consumers to reduce food waste while making healthy food more accessible and affordable.

### Key Features

- **Onboarding Flow**: User registration, goal setting, allergy preferences, and diet preferences
- **Food Marketplace**: Browse and purchase surplus/imperfect food items
- **Smart Cart System**: Recipe suggestions and missing ingredient recommendations
- **Gamification**: Badges, rewards, and progress tracking
- **Vendor Dashboards**: Separate interfaces for farmers and restaurants
- **USSD Integration**: Low-fidelity interface for feature phone users

## 🚀 Get Started

### Prerequisites

- Node.js (v16 or higher)
- npm or yarn
- Expo CLI
- iOS Simulator (for iOS development) or Android Emulator

### Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/rebite-mockup.git
cd rebite-mockup
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npx expo start
```

4. Open the app:
   - **iOS**: Press `i` in the terminal or scan the QR code with Expo Go app
   - **Android**: Press `a` in the terminal or scan the QR code with Expo Go app
   - **Web**: Press `w` in the terminal

## 📱 App Structure

### Onboarding Screens
- **Splash Screen** (`01-Splash.tsx`)
- **Sign In** (`02-SignIn.tsx`)
- **Sign Up** (`03-SignUp.tsx`)
- **Goals Picker** (`04-GoalsPicker.tsx`)
- **Allergies Picker** (`05-AllergiesPicker.tsx`)
- **Diet Preferences** (`06-DietPrefs.tsx`)
- **Tracker Sync** (`07-TrackerSync.tsx`)
- **Value Summary** (`08-ValueSummary.tsx`)

### Main App Screens
- **Home Feed** (`index.tsx`) - Browse food items
- **Food Detail** (`11-FoodDetail.tsx`) - View item details
- **Cart** (`13-Cart.tsx`) - Shopping cart with recipe suggestions
- **Checkout** (`15-Checkout.tsx`) - Purchase flow
- **Dashboard** (`16-Dashboard-Overview.tsx`) - User overview
- **History** (`17-History.tsx`) - Purchase history
- **Badges** (`18-Badges.tsx`) - Achievement system
- **Rewards Store** (`19-Rewards-Store.tsx`) - Points redemption

### Vendor Screens
- **Farmer Home** (`20-Farmer-Home.tsx`) - Farmer dashboard
- **Add Produce** (`21-Add-Produce.tsx`) - Product listing
- **Analytics** (`22-Analytics.tsx`) - Sales analytics
- **Restaurant Home** (`23-Restaurant-Home.tsx`) - Restaurant dashboard

### Edge Cases
- **USSD Interface** (`24-USSD.tsx`) - Low-fidelity interface
- **Empty States** (`25-Empty-States.tsx`) - Error and empty states

## 🎨 Design System

### Colors
- Primary: `#4CAF50` (Green)
- Secondary: `#FF9800` (Orange)
- Accent: `#2196F3` (Blue)
- Background: `#F5F5F5` (Light Gray)
- Text: `#333333` (Dark Gray)

### Typography
- **Winky Rough**: Playful, friendly font for headings
- **Concert One**: Clean, readable font for body text
- **Space Mono**: Monospace font for technical elements

### Components
- **Button**: Primary, secondary, and outline variants
- **Card**: Food item cards with images and details
- **Chip**: Filter and tag components
- **ProgressBar**: Progress indicators
- **Dialog**: Modal dialogs
- **BottomSheet**: Slide-up panels
- **TabBar**: Navigation tabs

## 🧪 Testing

Run the test suite:
```bash
npm test
```

## 📦 Build

### For iOS
```bash
npx expo build:ios
```

### For Android
```bash
npx expo build:android
```

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- UN Sustainable Development Goals (SDGs 2 & 12)
- React Native and Expo communities
- Food waste reduction initiatives worldwide

## 📞 Contact

For questions or support, please open an issue in this repository.

---

**Note**: This is a mockup/prototype for demonstration purposes. The app uses fake data and simulated functionality to showcase the user experience and design concepts. 
