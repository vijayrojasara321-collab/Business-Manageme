# My Personal Business Assistant - Native Android App

## Architecture
- **Language**: Kotlin 1.9+
- **UI Framework**: Jetpack Compose with Material 3 Design
- **Local Database**: Room 2.6+ with SQLite engine (100% offline, private device storage)
- **Encryption**: Android Keystore + EncryptedSharedPreferences (AES-256 GCM)
- **Target OS**: Android 8.0 (API 26) through Android 14+ (API 34)

## How to Build the APK and Install on your Phone
1. Unzip this project directory.
2. Open **Android Studio** (Hedgehog, Iguana, Koala, Ladybug or newer).
3. Select **File > Open...** and select the unzipped `MyPersonalBusinessAssistant` folder.
4. Allow Gradle to synchronize dependencies.
5. Connect your Android phone via USB with **USB Debugging** enabled in Developer Options, or launch an Android Virtual Device (AVD).
6. Click **Run > Run 'app'** or press Shift+F10 to install directly onto your device!
7. To generate a standalone APK:
   - Go to **Build > Build Bundle(s) / APK(s) > Build APK(s)**.
   - Android Studio will output `app-debug.apk` in `app/build/outputs/apk/debug/`.
   - Transfer this `app-debug.apk` to any Android phone via WhatsApp, Drive, or USB and tap to install!

## Features Included
- Multi-business management with custom activities, bank accounts, and GST registrations.
- People management with multi-business associations (one person in multiple businesses with distinct roles and activities).
- Directory with one-tap Call, WhatsApp, and Email shortcuts.
- Priority Tasks, Timetable planner, Manual Calls, Meetings, Follow-ups, Message Templates, AES encrypted Credentials, Notes, Documents, and Orders.
- Complete Offline Local Backup & Restore.
