# 🧊 GlassHub - Premium Firefox New Tab

![GlassHub Banner](https://img.shields.io/badge/UI-Glassmorphism-blue?style=for-the-badge) ![Firefox](https://img.shields.io/badge/Firefox-Extension-FF7139?style=for-the-badge&logo=Firefox-Browser) ![Privacy](https://img.shields.io/badge/Privacy-100%25_Local-success?style=for-the-badge)

**GlassHub** is a beautiful, highly customizable, and privacy-focused "New Tab" extension for Firefox. It replaces your default new tab with a stunning **Glassmorphism** interface, bringing all your favorite tools, shortcuts, and widgets into one elegant dashboard.

---

## ✨ Features

- **🎨 Premium Glassmorphism UI:** A sleek, frosted-glass design that adapts to any background you choose.
- **🔗 Customizable Shortcuts:** 
  - Add your most visited websites to the Main and Small shortcut grids.
  - **Auto-Favicon:** Just paste a URL, and GlassHub automatically fetches the correct, high-res icon.
- **🖐️ Drag & Drop Reordering:** Rearrange your shortcuts and greetings seamlessly with native drag-and-drop.
- **🌤️ Live Local Weather:** Powered by Open-Meteo API. Just type your city name to get real-time temperature and conditions.
- **🕒 Dynamic Clock & Greetings:** Real-time clock with date, and customizable greeting messages to start your day right.
- **🖼️ Custom Backgrounds:** 
  - Upload a local image, paste an image URL, or use the built-in Slideshow feature to rotate wallpapers automatically!
- **💾 Import / Export Config:** Change computers? Simply export your setup to a `.json` file and restore your entire personalized dashboard in one click.
- **🔒 100% Private:** No tracking, no analytics, no remote databases. Everything is stored locally in your browser's `localStorage`.

---

## 🚀 Installation

### Option 1: Load as a Temporary Add-on (For Developers)
1. Download or clone this repository to your computer.
2. Open Firefox and navigate to `about:debugging`.
3. Click on **"This Firefox"** in the left sidebar.
4. Click the **"Load Temporary Add-on..."** button.
5. Select any file inside the `GlassHub` folder (e.g., `manifest.json`).
6. Open a new tab and enjoy!

### Option 2: Permanent Installation (Self-Signed)
If you want to keep GlassHub permanently without reloading it every time you restart Firefox:
1. Zip the **contents** of the folder (not the folder itself).
2. Go to the [Mozilla Add-ons Developer Hub](https://addons.mozilla.org/developers/).
3. Submit a new Add-on and choose the **"On your own"** (Unlisted) option.
4. Upload your `.zip` file. Mozilla will automatically scan and sign it in minutes.
5. Download the `.xpi` file they provide, go to `about:addons` in Firefox, click the ⚙️ gear icon, and select **"Install Add-on From File..."**.

---

## ⚙️ Configuration

1. Open a new tab to see GlassHub.
2. Click the **Settings (⚙️)** icon in the bottom right corner.
3. Add your shortcuts, set your city for the weather, write custom greeting messages, or upload a background image.
4. Use the **☰** handles to drag and reorder items.
5. Click **Save Changes** and watch your new tab instantly update!

---

## 🛠️ Built With
- **Vanilla HTML5, CSS3, JavaScript** (No heavy frameworks, ultra-fast load times!)
- **Open-Meteo API** (Free, no-key weather data)
- **Google Favicon API** (For automatic icon fetching)

## 📄 License
This project is open-source and free to use. Feel free to fork, customize, and make it your own!
