# 🌙 Luna — How to Install & Share

## 📱 Install on Your Phone

### Option 1: Direct file (easiest)
1. Copy the file `luna.html` to your phone (AirDrop, email, USB, cloud drive)
2. Open it in **Chrome** (Android) or **Safari** (iOS) — NOT in the Files app
3. Tap the menu → **"Add to Home Screen"**
4. Name it "Luna" → it now works like a real app ✨

### Option 2: Web Server (if network allows)
```
http://YOUR_IP:8080
```
Open in browser → Add to Home Screen

> 💡 **File works offline** — once opened in browser, everything is cached. No internet needed after first load.

---

## 👯 Share with Friends for Feedback

### Quickest: Send the file
- Just send `luna.html` (43 KB) — it's a single file, zero setup
- They open it in mobile Chrome/Safari → Add to Home Screen → done

### Via GitHub Pages (free, permanent)
```
1. Create a GitHub repo
2. Upload index.html, manifest.json, icon-*.png, service-worker.js
3. Go to Settings → Pages → Deploy from main branch
4. Share the URL → friends open it AND can install it on their home screen
```

### Via Netlify (free, drag & drop)
```
1. Go to https://app.netlify.com/drop
2. Drag in the `period-tracker` folder
3. Get a shareable URL instantly (e.g., luna-tracker.netlify.app)
```

---

## ⚠️ Important Privacy Note
ALL data is stored **locally on each person's phone** in browser storage. 
Nobody else can see your data. Perfect for sharing the app without sharing your personal info.
