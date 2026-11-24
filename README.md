# Test (Android WebView)

Application Kotlin qui affiche https://scarlethub.infy.click/ en plein écran (mode immersif).

- Package : `com.scarlethub.test`
- Activité de lancement : `.MainActivity`
- Nom affiché : `Test`
- Android 8.0+ (minSdk 26)

## Compiler l'APK debug

Prérequis : JDK 17+, Android SDK (platform 34 + build-tools), Gradle 8.9+.

    gradle :app:assembleDebug

Résultat : `app/build/outputs/apk/debug/app-debug.apk` (à renommer en `Test.apk`).

Sans environnement local : poussez ce dossier sur GitHub puis lancez le workflow
« Build Test.apk » (onglet Actions). L'APK est téléchargeable dans les artefacts.
