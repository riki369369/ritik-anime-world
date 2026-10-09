# RITIK ANIME WORLD — Android APK starter

This wraps the existing web prototype in an Android app using Capacitor.

## Build a test APK using GitHub Actions
1. Extract this ZIP.
2. Create a GitHub repository and upload the files from this folder, including `.github/workflows/android-apk.yml`.
3. Open the repository's Actions tab and enable Actions if asked.
4. Choose **Build Android Debug APK** and select **Run workflow**, or push a commit to `main`.
5. When the workflow finishes, open the run and download the `ritik-anime-world-debug-apk` artifact.
6. Extract that downloaded ZIP and install `app-debug.apk` on your phone. Android may ask you to allow installs from the file app or browser.

## Notes
- This is a debug/testing APK, not a Play Store release.
- The catalog contains demo entries. Only add video/artwork you own or have permission to distribute.
- Admin changes stay on this device. There is no secure login or shared cloud database yet.
- Keep the repository private if you don't want to publish your source code publicly.
