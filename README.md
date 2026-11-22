# RADMIR Launcher — Android starter

A simple launcher UI with the supplied background, server address, and a button that attempts to open the installed `com.hassle.online` app. It does **not** modify the game's server list or connect to the specified server itself.

## Build APK in GitHub Actions (no Android Studio needed)
1. Create a GitHub repository and upload the contents of this folder to the repository (branch `main`).
2. Open the repository's **Actions** tab.
3. Select **Build Android APK**, then **Run workflow** (or push to `main`).
4. When the workflow finishes, open it and download the artifact named `RADMIR-Launcher-debug`.
5. Extract the artifact and install `app-debug.apk` on Android. You may need to allow installation from this source.

## Build locally
Install Android Studio and SDK 35, open this folder, sync Gradle, then Build > Build APK(s).

## Server
Displayed: `80.242.59.112:5309`. The launcher shell does not implement a game protocol connection.
