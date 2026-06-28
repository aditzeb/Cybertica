# Cybertica: The Local Talent Arena

[![Flutter Version](https://img.shields.io/badge/Flutter-3.38.5+-02569B?style=for-the-badge&logo=flutter&logoColor=white)](https://flutter.dev)
[![Dart Version](https://img.shields.io/badge/Dart-3.10.4+-0175C2?style=for-the-badge&logo=dart&logoColor=white)](https://dart.dev)
[![License](https://img.shields.io/badge/License-MIT-green.svg?style=for-the-badge)](LICENSE)
[![Google Solution Challenge](https://img.shields.io/badge/Challenge-Google%20Solution%20Challenge%202023-4285F4?style=for-the-badge&logo=google&logoColor=white)](https://developers.google.com/community/solutions-challenge)

Cybertica is an interactive mobile/web application designed to cultivate the readiness of the younger generation to become experts in technology. Developed originally for the **Google Solution Challenge 2023** (by GDSC UNKLAB), Cybertica provides a "Local Talent Arena" where young digital innovators can build competent portfolios, collaborate with peers, and showcase their talents.

---

## 🌟 About Cybertica

Many graduates find themselves lacking the exact competencies and qualifications required by modern tech companies, leading to companies recruiting foreign workers. At the same time, the lack of a structured local digital talent network hinders brilliant innovations from coming to life.

**Cybertica** addresses this gap by:
- **Accelerating Digital Talent**: Providing structured paths and challenges for early-stage tech students and enthusiasts.
- **Enabling Collaboration**: Helping young innovators find teammates and build a community around their ideas.
- **Bridging the Industry Gap**: Developing portfolios through active participation in regional competitions and talent-building programs.

---

## 🚀 Key Features

- **Home Page**: A curated, personalized dashboard displaying user progress, upcoming events, and achievements.
- **Competition Arena**: A space where students and tech enthusiasts can participate in local hackathons, UI design challenges, and coding competitions.
- **Rich UI Animations**: Smooth visual feedback and animations powered by `flutter_animate` to keep users engaged.
- **Responsive Layout**: Native compatibility across mobile (iOS & Android) and web viewports.
- **Internationalization**: Configured with internationalization support for multi-language accessibility.

---

## 🛠️ Technical Stack & Architecture

This application is built on top of **Flutter** and **Dart**:

- **Routing & Navigation**: [GoRouter](https://pub.dev/packages/go_router) for declarative, URL-based routing.
- **State Management**: [Provider](https://pub.dev/packages/provider) for clean, reactive state updates.
- **Local Persistence**: [Sqflite](https://pub.dev/packages/sqflite) for structured local storage and offline capabilities, and [Shared Preferences](https://pub.dev/packages/shared_preferences) for local key-value preferences.
- **Typography & Assets**: [Google Fonts](https://pub.dev/packages/google_fonts) (Poppins, Roboto) and [Font Awesome](https://pub.dev/packages/font_awesome_flutter) icons.
- **Animations**: [Flutter Animate](https://pub.dev/packages/flutter_animate) for micro-interactions and transitions.

---

## 💻 Getting Started

### Prerequisites

Make sure you have Flutter installed on your machine.
- Flutter SDK: `^3.38.5` (or any compatible Dart SDK `^3.10.4`)
- Target platforms: Android, iOS, Web

### Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/aditzeb/cybertica-front-end.git
   cd cybertica-front-end
   ```

2. **Retrieve dependencies**:
   ```bash
   flutter pub get
   ```

3. **Run the application**:
   - For mobile/desktop/web:
     ```bash
     flutter run
     ```
   - To build for web output:
     ```bash
     flutter build web
     ```

---

## 🤝 Contributing

We welcome contributions to Cybertica! Please read [CONTRIBUTING.md](CONTRIBUTING.md) to learn how to:
- Report bugs or request enhancements.
- Propose code changes.
- Adhere to code styles and formatting rules.

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
