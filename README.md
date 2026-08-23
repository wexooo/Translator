Translator

A lightweight translation add-on for **Firefox**.
Select any text, right-click, and instantly translate it into 14 languages.

## ✨ Features

- 🖱️ **Right-click translation** — select text, right-click, pick a language
- 🌐 **14 languages** supported
- 🔍 **Automatic source language detection**
- 📋 **One-click copy** button
- 🔄 **Multiple translation engines** with automatic fallback
  (Google → Lingva → MyMemory)
- 🎨 Stylish result panel
- 🕵️ **No accounts, no API keys, no tracking**

## 🚀 How to Use

1. Select any text on a webpage
2. Right-click → **🌍 Translate Selection**
3. Pick your target language
4. The translation appears in a panel at the bottom-right corner

## 📦 Installation

### From AMO (recommended)
Search for **Translator** on [addons.mozilla.org](https://addons.mozilla.org).
Works on Zen Browser, Firefox and all Firefox-based browsers.

### Developer / temporary install
1. Clone or download this repository
2. Open `about:debugging#/runtime/this-firefox`
3. Click **"Load Temporary Add-on…"**
4. Select `manifest.json`

## 📁 Project Structure

```
zen-translate/
├── manifest.json   # Add-on manifest
├── background.js   # Context menu + translation engines
├── content.js      # Result panel injection
├── panel.css       # Panel styling
└── icon.png        # Add-on icon
```

## 🛠️ Tech

- JavaScript (WebExtensions API, Manifest V2)
- Zero dependencies, no build step required
- Package with: `web-ext build`

## 📄 License

MIT 

---

*This project is not affiliated with Mozilla.*
