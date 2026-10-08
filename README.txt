3li bira - Android project

OPTION A - no install, free (GitHub builds the APK for you):
1. Make a free account at github.com and create a new repository.
2. Upload everything from this zip (keep the folders, including the hidden .github folder).
3. Open the Actions tab -> 'Build APK' -> wait ~3 minutes until it is green.
4. Open the finished run, download the artifact '3li-bira-apk', unzip it and install app-debug.apk on your phone (allow 'install unknown apps').

OPTION B - Android Studio:
1. File > Open > select this folder, wait for Gradle sync.
2. Build > Build Bundle(s)/APK(s) > Build APK(s). The file is in app/build/outputs/apk/debug/app-debug.apk

The game itself is app/src/main/assets/index.html
