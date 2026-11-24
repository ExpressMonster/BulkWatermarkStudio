# Bulk Watermark Studio — Android

Android Studio project for the client-side Bulk Watermark Studio app.

## Requirements
- Android Studio (current stable)
- Android SDK Platform 35
- JDK 17
- Android phone running Android 8.0 (API 26) or later

## Build APK
1. Open Android Studio.
2. Choose **Open** and select this project folder.
3. Allow Gradle sync and install Android SDK Platform 35 if prompted.
4. Select **Build → Build Bundle(s) / APK(s) → Build APK(s)**.
5. APK output: `app/build/outputs/apk/debug/app-debug.apk`.

## Features
- Multi-image selection (JPG/JPEG/PNG/WEBP)
- Transparent logo upload
- Position presets and custom drag placement
- Logo size, opacity, margin, output format and quality controls
- Live preview, batch processing, progress and cancel
- Individual saves and ZIP download
- Processing is performed locally in the Android WebView; image files are not uploaded to a server.

## Notes
- This is the Android Studio source project, not a precompiled APK.
- The app targets Android 8.0+ (API 26). Device-specific WebView or memory limits may affect exceptionally large images.
- Android 10+ saves output to `Downloads/Watermarked`. On Android 8–9 it saves in the app-specific Downloads folder.
