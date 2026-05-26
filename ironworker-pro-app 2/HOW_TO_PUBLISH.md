# IronWorker Pro — Publishing Guide
## Created by Antonio Pebworth © 2026

---

## YOUR PROJECT IS READY

All the hard setup is done. Here is exactly what you do on your Mac.

---

## STEP 1 — INSTALL THESE ON YOUR MAC (one time only)

1. Node.js — nodejs.org — download LTS and install
2. Android Studio — developer.android.com/studio — download and install
3. Xcode — Mac App Store — search Xcode and install (iOS only)

---

## STEP 2 — COPY THIS FOLDER TO YOUR MAC

Copy this entire `ironworker-pro-app` folder to your Mac Desktop.

---

## STEP 3 — OPEN TERMINAL AND GO TO THE FOLDER

```bash
cd ~/Desktop/ironworker-pro-app
```

---

## STEP 4 — ADD ANDROID PLATFORM

```bash
npx cap add android
npx cap sync
```

---

## STEP 5 — TEST ON YOUR ANDROID PHONE

```bash
npx cap open android
```

- Android Studio opens
- Plug in your phone via USB
- Enable USB Debugging on your phone
- Hit the Play button in Android Studio

---

## STEP 6 — ADD iOS PLATFORM (Mac + Xcode required)

```bash
npx cap add ios
npx cap sync
npx cap open ios
```

- Xcode opens
- Select your iPhone
- Hit Play

---

## STEP 7 — BUILD RELEASE (Android)

In Android Studio:
- Build → Generate Signed Bundle / APK
- Select Android App Bundle
- Create new keystore — SAVE IT FOREVER
- Select Release → Finish
- File saved at: android/app/release/app-release.aab

---

## STEP 8 — SUBMIT TO GOOGLE PLAY

- Go to play.google.com/console
- Create app → IronWorker Pro
- Upload app-release.aab
- Fill in store listing (see App_Store_Description.md)
- Submit for review

---

## APP DETAILS

- App Name: IronWorker Pro
- App ID: com.antoniopebworth.ironworkerpro
- Version: 1.5.0
- Author: Antonio Pebworth
- © 2026 All Rights Reserved

