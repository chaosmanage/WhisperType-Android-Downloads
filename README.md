# WhisperType for Android — official signed downloads

**Private, offline-first AI voice typing for Android 13+ (arm64).** WhisperType 1.3.0 introduces four on-device speech recognition engines with **Gemini Live as an optional cloud alternative**, not the default requirement.

## Download

[**Latest official APK**](https://github.com/chaosmanage/WhisperType-Android-Downloads/releases/latest/download/app-release.apk) · [**Latest SHA-256 checksum**](https://github.com/chaosmanage/WhisperType-Android-Downloads/releases/latest/download/app-release.apk.sha256) · [**All releases**](https://github.com/chaosmanage/WhisperType-Android-Downloads/releases)

**Upgrade in place** from an existing official installation; don't uninstall first, because that can erase settings, dictionaries and stored credentials. Check the APK SHA-256 against the published checksum. Android asks for installation approval; updates are never installed silently.

## New in 1.3.0

- **Local AI (after one-time model download):** Parakeet 110M, Parakeet Realtime EOU 120M, Moonshine English Base, Moonshine Small Streaming. Offline dictation stays on the device, requires no Gemini key and has no automatic cloud fallback.
- **Optional Gemini Live:** when deliberately selected, live audio is sent directly to Google's API; needs internet access and your own Gemini API key.
- Floating microphone and MiniBar with secure text-field insertion, optional encrypted local history, custom dictionary and optional encrypted saved recordings.
- Streamlined model management and native memory optimizations. Performance varies across Android devices; the four engines have not all completed the same device acceptance matrix.

The APK contains native runtime libraries and a verified Moonshine decoder-projection derivative, **not full offline-model checkpoints**. The model files are separately downloaded into the app's private storage and verified before use. An internet connection is needed for the initial download and app updates, not ongoing offline recognition.

This repository is a **public download-and-update feed only**. WhisperType's source repository is private; no source, signing keys, recordings, or API credentials are published here.
