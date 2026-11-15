MANUAL CAR SIMULATOR - ANDROID PROJECT
=====================================

This is an Android Studio project wrapper for the supplied HTML game.
The original game file is included at:
  app/src/main/assets/index.html

BUILD APK
---------
1. Install Android Studio on a computer.
2. Open this folder as an existing project.
3. Allow Android Studio to download the Android Gradle Plugin,
   Android SDK 35, and AndroidX WebKit dependencies.
4. Choose Build > Build Bundle(s) / APK(s) > Build APK(s).
5. The APK will be created at:
   app/build/outputs/apk/debug/app-debug.apk

APP DETAILS
-----------
App name: Manual Car Simulator
Package: com.manualcarsimulator.app
Minimum Android: Android 6.0 (API 23)

IMPORTANT
---------
The HTML is packaged inside the app. The original HTML loads Three.js
from cdnjs.cloudflare.com, so an internet connection is required for
the 3D engine unless that library is separately bundled locally.
This folder is an Android Studio project, not a compiled APK. A compiled
APK cannot be produced in this environment because Android SDK/build
tools are not installed.
