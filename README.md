# 🎮 Nyushu Switch Emulator

**Nyushu** is a high-performance Nintendo Switch emulator for Android devices, built to run commercial titles smoothly on ARM-powered phones and tablets.

---

## 📌 Features

- ⚙️ Emulates Nintendo Switch games on Android
- 🚀 Performance-optimized builds (standard / overclock / booster)
- 🎮 Support for `.nsp`, `.xci`, and folder-based game formats
- 📊 Vulkan GPU rendering with shader cache
- 🧠 Overclocking & speed limiter (up to 1000%)
- 📦 No root required
- 🔄 Frequent updates and patches

---

## 📦 Download

🔗 Visit [Release](https://github.com/nyushu-emulator/nyushu/releases) for the latest APKs:
- ✅ Standard Build
- 🔥 Overclock Build
- 🧊 Booster (cooler performance mode)

📌 Latest Version: **v40** (Released: July 20, 2025)

⚠️ **Note:** System firmware and title.keys are **not included** for legal reasons.

---

## 📥 Installation

1. Download the APK from the [official website]
2. Enable **Unknown Sources** in Android settings
3. Install the APK
4. Place the required `prod.keys` and `firmware` in `/sdcard/Nyushu/`
5. Launch the emulator and configure settings (GPU, audio, controller)

---

## ▶️ Usage

```bash
# Basic launch (via APK)
nyushu.apk

# With options (advanced)
nyushu.apk --gpu=turnip --speed-limit=1000
