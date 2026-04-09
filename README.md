# 🚀 Flash Chat

[![Flutter](https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white)](https://flutter.dev/)
[![Firebase](https://img.shields.io/badge/Firebase-039BE5?style=for-the-badge&logo=Firebase&logoColor=white)](https://firebase.google.com/)
[![Dart](https://img.shields.io/badge/Dart-0175C2?style=for-the-badge&logo=dart&logoColor=white)](https://dart.dev/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](https://opensource.org/licenses/MIT)

A modern, real-time chat application built with Flutter and Firebase. Experience seamless messaging with beautiful animations and secure authentication.

![Flash Chat Preview](https://via.placeholder.com/800x400/4A90E2/FFFFFF?text=Flash+Chat+App+Preview)

## ✨ Features

- 🔐 **Secure Authentication**: User registration and login with Firebase Auth
- 💬 **Real-time Messaging**: Instant message delivery with Cloud Firestore
- 🎨 **Beautiful UI**: Modern design with smooth animations using Animated Text Kit
- 🌙 **Dark Theme**: Eye-friendly dark mode interface
- 📱 **Cross-Platform**: Works on iOS, Android, Web, and Desktop
- 🚀 **Fast & Responsive**: Optimized performance with Flutter

## 📸 Screenshots

| Welcome Screen                                                             | Login Screen                                                           | Chat Screen                                                          |
| -------------------------------------------------------------------------- | ---------------------------------------------------------------------- | -------------------------------------------------------------------- |
| ![Welcome](https://via.placeholder.com/200x400/4A90E2/FFFFFF?text=Welcome) | ![Login](https://via.placeholder.com/200x400/4A90E2/FFFFFF?text=Login) | ![Chat](https://via.placeholder.com/200x400/4A90E2/FFFFFF?text=Chat) |

## 🛠️ Installation

### Prerequisites

- Flutter SDK (latest stable version)
- Dart SDK
- Firebase account and project
- Android Studio / VS Code with Flutter extensions

### Setup

1. **Clone the repository**

   ```bash
   git clone https://github.com/your-username/flash-chat.git
   cd flash-chat
   ```

2. **Install dependencies**

   ```bash
   flutter pub get
   ```

3. **Firebase Configuration**

   a. Create a new Firebase project at [Firebase Console](https://console.firebase.google.com/)

   b. Enable Authentication and Firestore Database

   c. Add your app to Firebase project (iOS/Android/Web)

   d. Download `google-services.json` (Android) and `GoogleService-Info.plist` (iOS)

   e. Place the config files in the appropriate directories:
   - Android: `android/app/google-services.json`
   - iOS: `ios/Runner/GoogleService-Info.plist`

4. **Run the app**
   ```bash
   flutter run
   ```

## 🚀 Usage

1. Launch the app
2. Register a new account or login with existing credentials
3. Start chatting in real-time with other users
4. Enjoy the animated welcome screen and smooth messaging experience

## 🏗️ Architecture

```
lib/
├── main.dart                 # App entry point
├── rounded_button.dart       # Custom button component
├── styles.dart              # App styling constants
└── Screen/
    ├── welcome_screen.dart   # Welcome/landing screen
    ├── login_screen.dart     # User login
    ├── registration_screen.dart # User registration
    └── chat_screen.dart      # Main chat interface
```

## 📦 Dependencies

- **firebase_core**: Firebase initialization
- **firebase_auth**: User authentication
- **cloud_firestore**: Real-time database
- **animated_text_kit**: Text animations
- **google_fonts**: Custom typography
- **flutter_progress_hud**: Loading indicators

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Built with ❤️ using Flutter
- Firebase for backend services
- Google Fonts for beautiful typography
- Animated Text Kit for smooth animations

## 📞 Support

If you have any questions or issues, please open an issue on GitHub or contact the maintainers.

---

**Made with Flutter & Firebase** ⚡

- 📱 **Cross-Platform**: Works on iOS, Android, Web, and Desktop
- 🚀 **Fast & Responsive**: Optimized performance with Flutter

## 📸 Screenshots

| Welcome Screen                                                             | Login Screen                                                           | Chat Screen                                                          |
| -------------------------------------------------------------------------- | ---------------------------------------------------------------------- | -------------------------------------------------------------------- |
| ![Welcome](https://via.placeholder.com/200x400/4A90E2/FFFFFF?text=Welcome) | ![Login](https://via.placeholder.com/200x400/4A90E2/FFFFFF?text=Login) | ![Chat](https://via.placeholder.com/200x400/4A90E2/FFFFFF?text=Chat) |

## 🛠️ Installation

### Prerequisites

- Flutter SDK (latest stable version)
- Dart SDK
- Firebase account and project
- Android Studio / VS Code with Flutter extensions

### Setup

1. **Clone the repository**

   ```bash
   git clone https://github.com/your-username/flash-chat.git
   cd flash-chat
   ```

2. **Install dependencies**

   ```bash
   flutter pub get
   ```

3. **Firebase Configuration**

   a. Create a new Firebase project at [Firebase Console](https://console.firebase.google.com/)

   b. Enable Authentication and Firestore Database

   c. Add your app to Firebase project (iOS/Android/Web)

   d. Download `google-services.json` (Android) and `GoogleService-Info.plist` (iOS)

   e. Place the config files in the appropriate directories:
   - Android: `android/app/google-services.json`
   - iOS: `ios/Runner/GoogleService-Info.plist`

4. **Run the app**
   ```bash
   flutter run
   ```

## 🚀 Usage

1. Launch the app
2. Register a new account or login with existing credentials
3. Start chatting in real-time with other users
4. Enjoy the animated welcome screen and smooth messaging experience

## 🏗️ Architecture

```
lib/
├── main.dart                 # App entry point
├── rounded_button.dart       # Custom button component
├── styles.dart              # App styling constants
└── Screen/
    ├── welcome_screen.dart   # Welcome/landing screen
    ├── login_screen.dart     # User login
    ├── registration_screen.dart # User registration
    └── chat_screen.dart      # Main chat interface
```

## 📦 Dependencies

- **firebase_core**: Firebase initialization
- **firebase_auth**: User authentication
- **cloud_firestore**: Real-time database
- **animated_text_kit**: Text animations
- **google_fonts**: Custom typography
- **flutter_progress_hud**: Loading indicators

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Built with ❤️ using Flutter
- Firebase for backend services
- Google Fonts for beautiful typography
- Animated Text Kit for smooth animations

## 📞 Support

If you have any questions or issues, please open an issue on GitHub or contact the maintainers.

---

**Made with Flutter & Firebase** ⚡
