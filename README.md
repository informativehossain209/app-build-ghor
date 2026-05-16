# 🏠 Ghor Khoroch — Android APK

> **ঘরের খরচ হিসাব করুন সহজে** — বিজ্ঞাপনমুক্ত, সম্পূর্ণ বিনামূল্যে Android APK।

**Developed by: SAKIB HOSSAIN**
**Web App:** [https://g-happk.vercel.app/](https://g-happk.vercel.app/)

---

## ⚡ সবচেয়ে সহজ পদ্ধতি — GitHub দিয়ে Auto Build

### ধাপ ১ — GitHub Repository তৈরি করুন

1. **github.com** → New Repository → নাম দিন: `ghor-khoroch-android`
2. **Public** রাখুন (Private হলে Actions কাজ নাও করতে পারে)

### ধাপ ২ — Code Upload করুন

```bash
cd ghor-khoroch-android
git init
git add .
git commit -m "Initial commit - Ghor Khoroch APK"
git branch -M main
git remote add origin https://github.com/আপনার-username/ghor-khoroch-android.git
git push -u origin main
```

### ধাপ ৩ — APK Download করুন

GitHub push করার **৫-৭ মিনিট** পর:

```
আপনার Repository → Actions tab → সবচেয়ে নতুন workflow
→ "GhorKhoroch-APK" artifact → Download
```

---

## 📲 APK Install করুন

1. ZIP extract করুন → `app-release.apk` পাবেন
2. Phone এ পাঠান (WhatsApp / USB / Google Drive)
3. Phone Settings → **"Unknown sources"** বা **"Install unknown apps"** চালু করুন
4. APK তে tap করুন → Install

---

## 🎨 Features

- ✅ **Splash Screen** — অ্যাপ খুলতেই সুন্দর Splash Screen দেখাবে
- ✅ **Developer Credit** — SAKIB HOSSAIN নাম প্রতিবার দেখা যাবে
- ✅ **Ghor Khoroch Logo** — Custom app icon
- ✅ কোনো বিজ্ঞাপন নেই
- ✅ Back button কাজ করে
- ✅ Full screen (action bar নেই)
- ✅ File upload support
- ✅ Image save & WhatsApp share

---

## 🔄 App Update করতে

শুধু code change করে GitHub এ push করুন:
```bash
git add .
git commit -m "update"
git push
```
**৫-৭ মিনিটে নতুন APK তৈরি হবে।**

---

## 📁 Project Structure

```
ghor-khoroch-android/
├── .github/workflows/build.yml        ← Auto APK builder
├── app/src/main/
│   ├── java/com/sakib/ghorkhoroch/
│   │   ├── SplashActivity.java        ← Splash screen (launcher)
│   │   └── MainActivity.java          ← WebView (loads web app)
│   ├── res/
│   │   ├── drawable/splash_background.xml  ← Green gradient background
│   │   ├── layout/activity_splash.xml      ← Splash UI layout
│   │   ├── mipmap-*/                  ← App icons (all densities)
│   │   └── values/strings.xml         ← App name
│   └── AndroidManifest.xml
├── build.gradle
├── settings.gradle
└── gradlew
```

---

## 👨‍💻 Developer

**SAKIB HOSSAIN**
Web App: [https://g-happk.vercel.app/](https://g-happk.vercel.app/)
