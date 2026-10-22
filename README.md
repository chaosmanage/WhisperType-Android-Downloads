# WhisperType — Official Android Downloads

**Private, offline-first AI voice typing for Android.** WhisperType inserts recognized speech into ordinary Android text fields using a floating microphone or MiniBar. Use one of four on-device speech models, or explicitly select **Gemini Live** for cloud transcription.

**Latest official version: 1.3.0** — major offline-AI release, upgrading production **1.2.34**. Android 13+; the current optimized native models target ARM64 devices.

## Download the verified APK

- [Latest official WhisperType APK](https://github.com/chaosmanage/WhisperType-Android-Downloads/releases/latest/download/app-release.apk)
- [SHA-256 checksum](https://github.com/chaosmanage/WhisperType-Android-Downloads/releases/latest/download/app-release.apk.sha256)
- [Release notes and previous versions](https://github.com/chaosmanage/WhisperType-Android-Downloads/releases)

Compare the APK's SHA-256 with the published checksum before installing. Android will ask you to approve APK installation. **Do not uninstall your existing WhisperType app to upgrade**; doing so can erase local settings, dictionary, and encrypted data. The official 1.3.0 APK retains the existing `com.whispertype.android` package and production signing certificate.

## Speech engines and privacy

The following local models can transcribe entirely **on-device after their first verified download**: Parakeet 110M Q4_K, Parakeet Realtime EOU 120M Q4_K, Moonshine English Base, and Moonshine Small Streaming. Offline mode does not need a Gemini API key or an internet connection during dictation, and it never silently sends recordings to Gemini if an offline model fails.

**Gemini Live is optional.** If selected, voice audio is sent directly to Google's Gemini API over TLS and requires internet and a user-provided key. Model downloads, release checks, and app updates also use the network. WhisperType has no relay server, user accounts, or telemetry. Optional local transcript history and saved audio are encrypted and user-controlled.

## About this repository

This public repository distributes **only official signed release APKs and corresponding SHA-256 files**. The source code and signing material are kept separately in the private source repository. Device-dependent accuracy, memory usage, and performance vary by model; see the 1.3.0 release notes for outstanding acceptance limitations.

Screenshots will be updated using real device captures when supplied. No AI-generated replacement screenshots are included.
