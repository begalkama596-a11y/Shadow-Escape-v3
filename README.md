# SHADOW ESCAPE (Android)
Package: com.alkama.shadowescape  |  WebView app, fully offline (game is in app/src/main/assets/index.html)
v2.0: 50 levels, cosmetics shop, settings, saves (SharedPreferences bridge + localStorage), vibration, Android back button.

## Option A - Android Studio (PC)
1. Open this folder in Android Studio (Hedgehog or newer). Let Gradle sync finish.
2. Build > Generate Signed App Bundle / APK > APK > create a new keystore > choose "release" > Finish.
3. APK appears in app/release/. Copy to phone and install.
Quick test: Build > Build APK(s) gives a debug APK in app/build/outputs/apk/debug/.

## Option B - GitHub Actions (phone only, no PC)
Upload this folder to a new GitHub repo, open the Actions tab > "Build APK" > Run workflow.
When it finishes, download the "ShadowEscape-APK" artifact (zip) and install the .apk inside.
