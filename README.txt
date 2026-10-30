HOLO LAUNCHER - build steps

Option A (Android Studio):
  1. Android Studio > Open > select this folder, wait for Gradle sync.
  2. Build > Build APK(s). APK: app/build/outputs/apk/debug/app-debug.apk
  3. Install it, press Home, choose "Holo Launcher" > Always.

Option B (no PC, browser only):
  1. Create a GitHub repo, upload all files of this folder (keep the .github folder).
  2. Actions tab > "Build APK" > Run workflow.
  3. When it finishes, download the artifact "HoloLauncher-debug-apk" (zip) and unzip to get the APK.

Change your name in the greeting: app/src/main/java/com/alchemyst/hololauncher/ui/Hud.kt (OPERATOR_NAME)
