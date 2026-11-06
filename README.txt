3-Phase Energy Meter Android project

This project wraps your supplied HTML dashboard in an Android WebView.
Firebase endpoint and the 5-second refresh logic are preserved.

Build APK:
1. Install Android Studio (current stable) and Android SDK Platform 35.
2. Extract this ZIP.
3. Android Studio > Open > select the ThreePhaseEnergyMeter folder.
4. Wait for Gradle sync to finish.
5. Build > Build Bundle(s) / APK(s) > Build APK(s).
6. APK output: app/build/outputs/apk/debug/app-debug.apk

Notes:
- Phone needs an internet connection to read Firebase.
- Firebase Realtime Database must allow the app's read request under its security rules.
- The dashboard initially offers device ID 01, as in your HTML. You can edit the HTML asset to add more device IDs.
- Application ID: com.example.threephaseenergymeter
