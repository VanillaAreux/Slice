# Slice — Desktop App Releases

This repo only holds built installers for **Slice**, the desktop app for
[slicesocial.netlify.app](https://slicesocial.netlify.app). There's no source
code here — the app's source lives in the main `loop` repo. This repo exists
so the installer binaries don't bloat that repo's git history.

## Download

Grab the latest installer from the [Releases](../../releases) page:
`Slice-Setup.exe` (Windows only, 64-bit).

Windows SmartScreen will likely warn that the app is from an unrecognized
publisher the first time you run it — that's expected, since it isn't
code-signed. Click **More info → Run anyway** to continue.

## What it is

Slice desktop is a lightweight wrapper around the Slice web app: its own
window, taskbar and Start Menu shortcuts, a tray icon, and real Windows
notifications for messages and calls. It always loads the live site, so
the app itself never needs updating for ordinary feature changes — only
for changes to the wrapper (icon, tray behavior, notification handling,
etc.).

## Publishing a new release

1. Build the installer from the `loop` repo's `loop-desktop/` project:
   ```
   npm install
   npm run dist
   ```
   Output: `dist/Slice Setup <version>.exe`.
2. Draft a new release here, tag it (e.g. `v1.0.1`), and upload the `.exe`
   as a release asset.
3. Update the download link on the site if the version number in the URL
   changed.
