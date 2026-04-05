# Dala Dala Water — TWA Android App

This is the Android wrapper for the Dala Dala Water PWA.
It turns your website into a real Android app using TWA (Trusted Web Activity).

## ✅ What's Already Done
- App name: Dala Dala Water
- URL: https://akyturiy-solutions-dala-dala-water.vercel.app
- Package: com.daladalawater.app
- Version: 3.0
- Auto-builds APK & AAB via GitHub Actions

---

## 🚀 How to Get Your APK (Step by Step)

### Step 1 — Create a New GitHub Repo
1. Go to github.com
2. Click the green "New" button
3. Name it: **DalaDalaWater-TWA**
4. Set it to **Public**
5. Click "Create repository"

### Step 2 — Upload These Files
1. Click "uploading an existing file"
2. Drag and drop ALL the files and folders from this zip
3. Click "Commit changes"

### Step 3 — Wait for the Build
1. Click the "Actions" tab in your new repo
2. You'll see a build running automatically
3. Wait 3–5 minutes for it to finish ✅

### Step 4 — Download Your APK
1. Click on the completed build
2. Scroll down to "Artifacts"
3. Download **DalaDalaWater-TWA-DEBUG** to test on your phone
4. Download **DalaDalaWater-TWA-GOOGLE-PLAY** (.aab) for Play Store

---

## ⚠️ One Important Step — assetlinks.json

For the app to work properly without showing the browser bar,
you need to add a file to your PWA repo.

Create this file in your PWA GitHub repo:
- File path: **public/.well-known/assetlinks.json** (or ask Claude to do it)
- Content: provided in assetlinks-template.json in this folder

You'll need your **app signing key SHA-256 fingerprint** to fill it in.
Claude can help you with this step when you're ready.

---

## 📱 Installing the APK on Android
1. Download the DEBUG APK to your phone
2. Open it — Android will ask to allow "Install unknown apps"
3. Enable it and install
4. Dala Dala Water appears on your home screen like a real app!

---

## 🏪 Publishing to Google Play Store
1. Create a Google Play Developer account (one-time $25 fee)
2. Upload the .aab file
3. Fill in app details, screenshots, description
4. Submit for review (usually 1–3 days)
