# NS Browser — Chromium v152 Android build scaffold

GitHub Actions project for an open-source Chromium-based Android browser.
Target: Chromium 152.0.7977.42 (the workflow verifies the tag and stops if absent).
APK target: Android ARM64 / arm64-v8a.
Features scaffold: AdBlock/custom filters, regional filters, script injection,
translation integration hook, and GPU acceleration through Chromium defaults.

Full Chromium source is intentionally not bundled; the Action fetches it during CI.
