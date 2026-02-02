# Plant Family Guide - Offline PWA

A Progressive Web App (PWA) for plant family identification that works offline.

## 🚀 Quick Deploy to GitHub Pages

### Step 1: Create a GitHub Repository
1. Go to [github.com](https://github.com) and sign in
2. Click the **+** button → **New repository**
3. Name it `plant-guide` (or whatever you prefer)
4. Make it **Public** (required for free GitHub Pages)
5. Click **Create repository**

### Step 2: Upload Files
1. On your new repository page, click **"uploading an existing file"**
2. Drag and drop ALL these files:
   - `index.html`
   - `manifest.json`
   - `service-worker.js`
   - `icon-192.png`
   - `icon-512.png`
3. Click **Commit changes**

### Step 3: Enable GitHub Pages
1. Go to your repository's **Settings** tab
2. Click **Pages** in the left sidebar
3. Under "Source", select **Deploy from a branch**
4. Select **main** branch and **/ (root)** folder
5. Click **Save**

### Step 4: Access Your App
After 1-2 minutes, your app will be live at:
```
https://YOUR-USERNAME.github.io/plant-guide/
```

## 📱 Installing as Offline App

### On Mobile (iOS/Android):
1. Open your GitHub Pages URL in the browser
2. **iOS**: Tap Share → "Add to Home Screen"
3. **Android**: Tap the menu → "Install app" or "Add to Home Screen"

### On Desktop (Chrome/Edge):
1. Open your GitHub Pages URL
2. Look for the install icon (⊕) in the address bar
3. Click "Install"

## 🌿 Using the App

1. First time: Upload or paste your plant family CSV data
2. Click "Save to Browser" to store it locally
3. The app will now work completely offline!
4. Your data stays in your browser's local storage

## 📋 CSV Format

Your CSV should have these columns:
- Family
- Order
- Group
- Common genera
- Growth Form
- Leaf Characteristics
- Flower Characteristics
- Fruit Characteristics
- Distribution
- Reproductive Strategy
- Common Dispersal Type
- Sp. estimate
- Two extremes
- Uses/other info

## 🔧 Troubleshooting

**App not installing?**
- Make sure you're using HTTPS (GitHub Pages provides this)
- Try using Chrome or Edge browser
- Clear browser cache and refresh

**Data not saving?**
- Check if your browser allows local storage
- Some privacy browsers block this feature

**Updates not showing?**
- Clear the browser cache
- Uninstall and reinstall the app

## 📄 License

Free to use and modify for personal/educational purposes.
