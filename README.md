# Navigator – Android App

A GPS navigation app with map, routing, search, and turn-by-turn directions.

## Features
- 📍 Real GPS location access
- 🔍 Search any destination worldwide
- 🗺️ Tap map to set destination
- 🚗 Car routing with distance & drive time
- 📋 Turn-by-turn directions
- 🌙 Dark immersive UI

## Build Instructions

### Requirements
- [Android Studio](https://developer.android.com/studio) (free, ~1 GB)
- JDK 17+ (bundled with Android Studio)
- Android SDK (installed via Android Studio)

### Steps

1. **Open in Android Studio**
   - Launch Android Studio
   - Click "Open" and select this folder (`navigator-android/`)
   - Wait for Gradle sync to finish (~2–5 min first time)

2. **Build APK**
   - Menu: `Build → Build Bundle(s) / APK(s) → Build APK(s)`
   - APK will be at:
     `app/build/outputs/apk/debug/app-debug.apk`

3. **Install on phone**
   - Enable "Unknown sources" on your Android phone
     (Settings → Security → Install unknown apps)
   - Copy the APK to your phone and open it, OR
   - With USB debugging: `adb install app-debug.apk`

### Direct USB install (fastest)
```bash
# Connect phone via USB with USB Debugging enabled
adb install app/build/outputs/apk/debug/app-debug.apk
```

## Permissions
- `ACCESS_FINE_LOCATION` – for your GPS position
- `INTERNET` – for map tiles, search, and routing

The app will request location permission on first launch.
