# VYBE Android APK build files

These files create a basic Android WebView wrapper for the hosted VYBE app:
https://vybe-dating-app.hatchable.site

## Upload to GitHub
Upload the contents of this folder (including the hidden `.github` folder) to the root of your NEW VYBE repository, on the `main` branch.

## Build the APK
1. Open the repository's Actions tab.
2. Select `Build VYBE Android APK`.
3. Tap `Run workflow` and choose `main`.
4. Wait for the run to finish with a green check.
5. Open the completed run and download the `VYBE-Android-debug-APK` artifact.
6. Extract the ZIP and install `app-debug.apk` on your Android phone.

This is a basic test APK wrapper. It loads the hosted VYBE website and needs an internet connection. It is not a Play Store release or a signed production APK.
