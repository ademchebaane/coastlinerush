# Coastline Rush — flat Android project

This repository is intentionally flattened: there is **no `app/` folder** and no Capacitor project.

The Android application plugin is applied directly to the root Gradle project. `MainActivity.java`, `AndroidManifest.xml`, and `index.html` are all at the repository root.

## GitHub Actions

Run **Actions → Build Coastline Rush APK → Run workflow**.

The workflow installs Gradle 9.4.1 and Android SDK 36, builds the debug APK, and uploads it as `Coastline-Rush-APK`.

The game uses the original HTML/Three.js game and loads Three.js from its jsDelivr URL at runtime, so the APK needs internet access for Three.js.
