PHOTO TO WORD - ANDROID APK BUILD USING GITHUB ACTIONS

Files included:
- www/index.html = your webapp
- package.json = Capacitor dependencies
- capacitor.config.json = Android app name/package
- .github/workflows/build-android-apk.yml = automatic APK builder

IMPORTANT:
- The APK built is a DEBUG APK. It is free and installable on your phone.
- It is not for Play Store upload.
- Android may ask you to allow installing unknown apps.

PHONE STEPS:
1. Create a new PUBLIC GitHub repo named: photo-to-word-android
2. Open the repo in GitHub Codespaces.
3. Upload this extracted folder's files into the repo.
4. Commit and push.
5. Go to GitHub repo -> Actions -> Build Android APK -> Run workflow.
6. Wait for the green tick.
7. Open the completed workflow run.
8. Download artifact: Photo-to-Word-APK.
9. Extract the downloaded ZIP.
10. Install app-debug.apk on Android.
