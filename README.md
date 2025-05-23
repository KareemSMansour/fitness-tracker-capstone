# fitness_tracker

Fitness Tracker

## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://docs.flutter.dev/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://docs.flutter.dev/cookbook)

For help getting started with Flutter development, view the
[online documentation](https://docs.flutter.dev/), which offers tutorials,
samples, guidance on mobile development, and a full API reference.

## 🔧 Getting Started

Follow these steps to set up and run the project on your local machine.

---

### 📦 Prerequisites

Before you begin, make sure the following are installed:

- [Flutter SDK](https://docs.flutter.dev/get-started/install) (recommended version: 3.32.0 or later)
- [Android Studio](https://developer.android.com/studio)
  - ✅ Flutter plugin
  - ✅ Dart plugin
  - ✅ Android SDK
  - ✅ Android Virtual Device (AVD) Manager
- Git

Verify Flutter is installed:

flutter --version
### 🚀 Installation

Clone the repository and install dependencies:

```bash
git clone https://github.com/KareemSMansour/fitness-tracker-capstone.git
cd fitness-tracker-capstone
flutter pub get
````

> 💡 If you're on Windows and see a "file in use" error during `flutter pub get`, make sure no `dart.exe` processes are running (check Task Manager).

---

### 📱 Run on Android

1. Open **Android Studio**
2. Go to **Tools > Device Manager**
3. Create a new emulator (e.g., Pixel 5 with API 33)
4. Start the emulator

Then run:

```bash
flutter run
```

Or target a specific device:

```bash
flutter devices           # lists connected devices
flutter run -d DEVICE_ID # replace with actual ID
```

---

### 🌐 Run on Web (Chrome)

```bash
flutter run -d chrome
```

Thanks Kareem — here's the **Run on iOS** section cleaned up to match the clean code block formatting and structure used in the "Web" section:

---

### 🍎 Run on iOS (macOS only)

> ⚠️ Requires macOS with [Xcode](https://developer.apple.com/xcode/) installed

1. Install CocoaPods:

```bash
sudo gem install cocoapods
````

2. Set up iOS dependencies:

```bash
cd ios
pod install
cd ..
```

3. Connect an iOS device or launch the simulator:

```bash
open -a Simulator
```

4. Run the app:

```bash
flutter run -d ios
```

> 💡 You may be prompted to open the project in Xcode to sign it with your Apple Developer account the first time.

```





