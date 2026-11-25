# Tyson's Island — Releases

This repository holds the downloadable releases of **Tyson's Island**, a personal
Android app that puts notifications, calls, music, timers and more into a floating
island at the top of the screen.

There is no source code here. This repo exists so the app's built-in update checker
can fetch new versions: each release carries one signed APK, and the app downloads
and installs it in place, keeping all settings.

## Installing an update

1. Open Tyson's Island → **About** → turn on **Check for updates**, or tap
   **Check now**.
2. When a new version is offered, tap **Update** and confirm the system install
   prompt. The first time, Android asks you to allow installs from this app —
   allow it once and later updates go straight through.

Every APK here is signed with the same key as the installed app, and the app
verifies the signature before installing.
