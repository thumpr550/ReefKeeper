# Reef Keeper (Android)

A starter Android app for Josh's 120-gallon aquarium. Data is stored locally on the device using Android DataStore.

## Build an APK using GitHub (no laptop required)

1. On your Pixel, open https://github.com and create/sign into an account.
2. Create a new repository named `ReefKeeper` (choose **Public** for the simplest setup; do not add README/license/gitignore).
3. Upload the contents of this ZIP to the repository. Make sure `.github/workflows/build-apk.yml` is included. GitHub mobile may hide dot-folders; if so use GitHub in Chrome with **Desktop site** enabled.
4. Open the repository → **Actions** → **Build Reef Keeper APK** → **Run workflow**. If prompted, enable Actions.
5. Wait for the workflow to finish green. Open that run, scroll to **Artifacts**, and download `reef-keeper-apk`.
6. Extract the ZIP on your Pixel. Tap `app-debug.apk` and allow Chrome/Files to install unknown apps if Android prompts. Install.

The workflow also builds automatically on commits to `main`.

## Included features
- Dashboard for 120g tank and 30g sump
- Water parameter values saved locally
- Maintenance checklist saved locally
- Water-change percentage calculator
- Journal entries saved locally
- Dark aquarium theme

## Notes
This is an early v1. It does not connect to aquarium sensors and does not yet provide timed notifications, graph history, livestock management, or cloud sync. Parameters are manually entered. Current ranges are general guidance and should be adjusted to your livestock and goals.
