# Ad Display App

This is a **simple Kotlin Android app** designed to **display AdMob banner and interstitial ads**.

## Features
- Banner ad at the bottom of the main screen
- Interstitial ad loads and displays automatically on app launch
- Fully customizable with your own AdMob App ID and Ad Unit IDs

## Your AdMob Settings
- **App ID**: `ca-app-pub-xxxxxxxxxxxxxxxx~xxxxxxxxxxx`
- **Banner Ad Unit**: `ca-app-pub-xxxxxxxxxxxxxxxx/xxxxxxxxxxx`
- **Interstitial Ad Unit**: `ca-app-pub-xxxxxxxxxxxxxxxx/xxxxxxxxxxx`

## How to Build
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/AdDisplayApp.git
   cd AdDisplayApp
   ```
2. Open the project in **Android Studio**.
3. Let Gradle sync the project.
4. Connect a device or start an emulator.
5. Click **Run** ▶️ to build and install the app.

## GitHub Actions
This project includes a GitHub Actions workflow to automatically build the APK on each push to `main`.  
You can find the built APK in the GitHub Actions artifacts after the workflow completes.

---

**Note:** Make sure you follow AdMob policies when publishing the app.
