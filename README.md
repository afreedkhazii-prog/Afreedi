# SK Medical Store - Native Android & Flutter Application

A complete, production-ready Pharmacy Stock Management System with AI Bill Scanning, SQLite offline storage, and MLKit OCR.

## Features
- 📷 **Google MLKit OCR Camera**: Real-time invoice text scanning.
- 🗄️ **SQLite Persistence**: Offline local database with sqflite.
- 📦 **Stock Management**: Track expiry dates, batch numbers, and reorder levels.
- 🔔 **Android Notifications**: Local low-stock and expiry alerts.

## How to Build the Release APK
1. Ensure **Flutter SDK 3.22+** and **Android Studio (API 34)** are installed.
2. Open terminal in the project root directory and run:
   ```bash
   flutter pub get
   ```
3. Connect your Android mobile device via USB with ADB Debugging enabled.
4. Execute the release build command:
   ```bash
   flutter build apk --release
   ```
5. Locate the compiled release package at:
   `build/app/outputs/flutter-apk/app-release.apk`
