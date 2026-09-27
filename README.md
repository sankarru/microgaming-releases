# MicroGaming releases

Public download host for the MicroGaming Android app (package `com.microgaming`).

The app's in-app updater reads `version.json` and downloads the APK asset attached to
the newest GitHub release. Releases here are intentionally public: the updater performs
an unauthenticated GET, so a private repo would return 404.

The app's **source** is kept in a private repository and is not published here.

| Field | Value |
|---|---|
| Package | `com.microgaming` |
| Asset | `MicroGaming-<version>.apk` |
