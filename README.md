# HyperGlass Android App (v1.0)

Companion APK & LSPosed module modeled for `HyperGlass13-KernelSU-v0.1.0.zip`.

## Features
- **Live Liquid Glass Preview Card** with spring-animated floating pill indicator (`Home`, `Shop`, `Inbox`, `Profile`)
- **Bening -> Frosted Intensity Slider** synced in real time to `/data/adb/modules/hyperglass13/config/settings.conf`
- **`WRITE_SETTINGS` Permission Check** + root fallback status badge
- **Per-App Hook Toggles** (`TikTok`, `Gallery`, `Themes`, `Clock`, `YouTube Music`, `WhatsApp`, `Instagram`, `YouTube`, `Claude`, etc.)
- **GitHub Actions CI Workflow** (`.github/workflows/build-apk.yml`) ready to compile `app-debug.apk` automatically on push.

## Build Instructions
1. Extract this ZIP and open the folder in **Android Studio**, or push it to a GitHub repository to let `.github/workflows/build-apk.yml` build the APK automatically.
2. Or build via CLI:
   ```bash
   gradle assembleDebug
   ```
