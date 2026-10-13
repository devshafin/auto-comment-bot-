# AutoComment Bubble (Android)

A floating bubble inside the X app. Open a reply box, tap the bubble, a short reply is typed into the box. You press Reply yourself.

## Build the APK (pick one)

**A) GitHub (no Android Studio needed)**
1. Make a free GitHub account, create a new repository.
2. Upload ALL files and folders from this zip (including the hidden `.github` folder) to the repository.
3. Open the repository's **Actions** tab, choose **Build APK**, press **Run workflow**.
4. When it turns green, open the run and download the artifact **AutoComment-Bubble-APK**. Unzip it to get `app-debug.apk`.

**B) Android Studio**
Open this folder, wait for sync, then Build > Build APK(s).

## Install and turn on
1. Copy `app-debug.apk` to the phone and install it (allow "install unknown apps" for your file manager or browser).
2. Open **AutoComment Bubble**, paste your Groq / Gemini / OpenRouter key, press **Test my setup**.
3. Tap **Open Accessibility settings**, find **AutoComment Bubble**, switch it on.
   Android 13+: if the switch is greyed out, open the app info page, tap the three dots (top right) and choose **Allow restricted settings**, then try again.

## Use
Open X, tap Reply under a post, tap the bubble (drag it where you like), wait for the check mark, read the text, press Reply.

The bubble only shows inside the X app. The service reads the screen only when you tap the bubble, and only inside X. It never presses Reply or posts anything.
