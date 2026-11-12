# St Sava Church Register

Touchscreen sales register for St Sava Church West Ealing. Includes product management, cash sales, secure staff sign-in, shared iPad/Android data, and a Staff Access sales activity dashboard.

## Staff sign-in and shared data

Sign in with the existing **Head Admin** staff account on both devices. The staff PIN is entered in the app and is not stored in this repository.

The iPad web app and Android APK connect to the same shared register:
- Products and product changes sync between signed-in devices.
- Confirmed cash sales are saved to the shared database.
- The Staff Access dashboard shows sales counts by day and device, plus each sale's date/time, device, items, and quantities.
- The Staff Access dashboard does **not** display money totals or earnings.
- The dashboard refreshes periodically while the register is open; use its Refresh button for an immediate update.

A working internet connection and a valid staff session are required to sync. If the register reports a sync error, do not assume a sale or product change has been saved.

## Android app

The Android APK is built automatically from changes to the register.

- **[Download the latest Android APK](https://github.com/lukakrivosic100-finance/Church-iPad-Register/releases/download/church-register-android-latest/app-debug.apk)**

On your Android device, open the download link, download the APK, then tap the downloaded file to install it. Android may ask you to allow your browser or file manager to install apps from that source.

The iPad version remains available as a Safari Home Screen web app.
