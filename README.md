# Coastline Rush Android APK

This is a flat Android Gradle project: there is no `app/` directory and no Capacitor.

## GitHub Actions

Push these files to the root of the repository, then run:

Actions -> Build Coastline Rush APK -> Run workflow

The workflow uses Android Gradle Plugin 9.4.0, Gradle 9.6.0, Java 17, Android SDK 36, and Build Tools 36.0.0.

On success, the `Coastline-Rush-APK` artifact contains the debug APK.
If the build fails, the workflow uploads `Coastline-Rush-Gradle-Log` with the complete Gradle output.
