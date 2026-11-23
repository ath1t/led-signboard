<div align="center">

# 💡 LED Sign Board

**A real dot-matrix LED display, right in your phone's browser.**

Scroll it. Flash it. Go full screen. Install as a PWA. Single-file `index.html`, no build step, no dependencies.

[![Live Demo](https://img.shields.io/badge/LIVE%20DEMO-Open%20the%20sign-ff3b30?style=for-the-badge&logo=githubpages&logoColor=white)](https://ath1t.github.io/led-signboard/)

![Single file](https://img.shields.io/badge/single_file-index.html-1f2328?style=flat-square)
![PWA](https://img.shields.io/badge/PWA-installable-111827?style=flat-square)
![Dependencies](https://img.shields.io/badge/dependencies-none-2ea44f?style=flat-square)
![Hosting](https://img.shields.io/badge/hosted_on-GitHub_Pages-0969da?style=flat-square)
![Mobile](https://img.shields.io/badge/built_for-mobile-8957e5?style=flat-square)

</div>

---

## ✨ Overview

LED Sign Board turns your phone or desktop browser into a glowing dot-matrix sign. Type a message (including Myanmar Unicode), pick an effect, brightness, and colour, then show it full screen. Everything lives inside a single `index.html` file with inline PWA manifest/icon/service-worker support, no build step, and local browser storage.

## 🎛️ Features

| | Feature | Details |
|---|---|---|
| 🔴 | **Dot-matrix display** | LED-style dots with a toggleable soft glow |
| 🎞️ | **Six effects** | Scroll left, scroll right, scroll up, scroll down, still, and blink |
| 🎚️ | **Fine control** | Adjust animation speed, text size, LED dot size, and brightness |
| 🎨 | **Colour** | Six presets plus a custom colour picker |
| 🌐 | **Bilingual UI & Myanmar text** | Switch interface language between Myanmar (`မြန်မာ`) and English |
| 📲 | **Single-file PWA** | Inline manifest, SVG icon, and service worker for standalone launch |
| 📱 | **Mobile-friendly controls** | Touch-sized buttons, scrollable settings panel, and safe-area spacing for notched screens |
| 📺 | **Full screen** | Top bar fades after 3.5 seconds of inactivity; tap the sign to bring it back |
| 🔄 | **Rotate 90°** | Rotate the display 90° while holding your phone upright |
| 🪞 | **Mirror text** | Flip the message horizontally for reflections and windows |
| 🔆 | **Stays awake** | Requests a screen wake lock where supported by the browser |
| 💾 | **Remembers you** | Settings are saved locally in `localStorage` on your device |

## 🚀 Quick Start

1. Open **[ath1t.github.io/led-signboard](https://ath1t.github.io/led-signboard/)** in your phone's browser.
2. Tap **Edit** (or **ပြင်ရန်**) and enter your message.
3. Choose an animation effect, speed, text size, dot size, brightness, and colour.
4. Tap **Show sign** (or **ပြသရန်**).
5. Tap **Full screen** if supported, or **Install app** when prompted by your browser. Tap the sign anytime to bring controls back.

> [!TIP]
> **iPhone:** Full-screen support varies by browser and iOS version. Use **Share → Add to Home Screen**, then launch from the Home Screen icon for a standalone app view.

> [!TIP]
> **Mobile layout:** The settings panel scrolls when it exceeds screen height. Use **Rotate display 90°** to display a wider sign while holding your phone upright.

## 🌐 Host Your Own

<details>
<summary><b>Deploy to GitHub Pages in four steps</b></summary>
<br>

1. Create a new **public** repository on GitHub.
2. Upload `index.html` and this `README.md`, then commit the files.
3. Go to **Settings → Pages**. Under *Build and deployment*, set the source to **Deploy from a branch**, choose `main` and `/ (root)`, then click **Save**.
4. Wait for deployment to finish (it may take a few minutes). Your site will be available at:

```text
https://<username>.github.io/<repo-name>/
