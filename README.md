# NS Browser

Open-source Chromium-based Android browser build project.

## Build

The workflow checks out Chromium at a pinned revision, applies NS Browser patches, builds an ARM64 release APK, runs basic APK checks, and publishes the APK as a GitHub Release asset.

Chromium and depot_tools are downloaded from their upstream repositories. This repository does **not** redistribute Chromium source.

## Important

`CHROMIUM_REVISION` must be a real Chromium Git commit or tag that is compatible with the patches in this repository. Update it deliberately when rebasing.

The browser target is `chrome_public_apk`. A WebView build is a separate target (`system_webview_apk`) and is not automatically a valid Android WebView provider.

## License

Chromium is distributed under its upstream open-source licenses. NS Browser-specific files in this repository should carry an appropriate open-source license and preserve all Chromium notices.
