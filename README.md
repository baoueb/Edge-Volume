<img align="left" width="80" height="80" src="https://i.postimg.cc/xCnnC8LZ/icon-modified.png" alt="Edge Volume Icon">

# Edge Volume

**Edge Volume** is a sleek, lightweight macOS utility that brings an iOS-style volume slider to your desktop. Hover near the right edge of your screen to reveal a translucent, animated volume control that blends beautifully with macOS aesthetics.

---

> ⚠️ **Bluetooth limitation:**  
> Most Bluetooth speakers and headphones (e.g. AirPods, Beats, etc.) implement their own hardware volume control. While Edge Volume will still appear, these devices often pin your Mac’s system volume at 100%, so turning the slider in-app won’t actually change their output level. For full control, use your device’s onboard volume buttons or crown. A future MacOS update could fix this.

---

## ✨ Features

- 🎛️ **iOS-Inspired Volume Slider** — minimal and elegant.  
- 🖱️ **Edge-Triggered Reveal** — hover near the right screen edge.  
- 🔄 **Live Sync** with system volume for supported devices.  
- 💬 **Animated Transitions** — smooth UX.  
- 🌒 **Dark & Light Mode Support**  
- 🌟 **Always On Top** — stays above fullscreen apps.  
- ⚙️ **Menu Bar Integration** — settings, launch-at-login, update checks.  
- 📦 **Auto Updates** via [Sparkle](https://sparkle-project.org/).  
- 💥 **Haptic Feedback** on max/min volume (if supported).  
- 📃 **Welcome Screen** on first launch.

---

## 🖼️ Preview

![screenshot](https://i.postimg.cc/ZRTV0znH/Product-Preview.png)

---

## 📥 Installation

Download the latest `.dmg` from the [Releases](https://github.com/baoueb/Edge-Volume/releases) page and drag it into your `/Applications` folder.

> ⚠️ **Note**: Edge Volume is currently unsigned. You may need to right-click the app and select **Open** on first launch.

---

## 🧑‍💻 Development

```bash
git clone https://github.com/baoueb/Edge-Volume.git
cd Edge-Volume
open EdgeVolumeSlider.xcodeproj
