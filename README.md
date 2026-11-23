# Privacy HQ — GitHub to Android APK Project

Offline-ready Capacitor Android app wrapper for **Privacy HQ — Data Protection & Cybersecurity Simulation** (with custom Shield launcher icons).

## Build the `.apk` on GitHub (No Android Studio Needed)
1. Extract this ZIP archive on your computer.
2. Create a new repository on [github.com](https://github.com).
3. Click **uploading an existing file**, drag `README.md`, `package.json`, `capacitor.config.json`, the `assets` folder, and the `www` folder into the upload area, and click **Commit changes**.
4. Click **Add file → Create new file**, type `.github/workflows/build-apk.yml` as the file name, paste the contents of `build-apk.yml` from this ZIP, and click **Commit changes**. *(GitHub's browser drag-and-drop skips hidden `.github` folders, so creating that file directly ensures the workflow triggers.)*
5. Open the **Actions** tab at the top of your repository, wait for **Build Android APK** to turn green (~2 minutes), click the completed run, and download **`privacy-hq-apk`** from **Artifacts**.
6. Unzip `privacy-hq-apk.zip` to get **`app-debug.apk`**, transfer it to your Android phone, and tap to install.
