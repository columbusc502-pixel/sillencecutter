# Silence Cutter
Offline batch silence remover for Android. No ads, accounts, paywall or Google Play dependencies.

## Build
1. Install Android Studio and open this folder (it creates the Gradle wrapper for you).
2. Build > Build APK(s), or run `gradle assembleRelease`.
3. Install app/build/outputs/apk/release/app-release.apk. Outputs go to Movies/SilenceCutter.

## Tuning
- Threshold -35 dB works for most speech. If it cuts too little, raise it (-30). If it clips words, lower it (-42).
- Minimum silence 0.5 s keeps natural pauses.
