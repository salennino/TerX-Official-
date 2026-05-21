<p align="center">
  <img src="https://raw.githubusercontent.com/salennino/TerX-Official-/main/Img.png" alt="Frieren AI Banner" width="600">
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Frieren%20AI-v8.0-blue?style=for-the-badge" alt="Version">
  <a href="https://t.me/terxofficial"><img src="https://img.shields.io/badge/Telegram-Join%20Channel-2CA5E0?style=for-the-badge&logo=telegram" alt="Telegram"></a>
  <a href="[https://youtube.com/@yourchannel](https://youtube.com/@terx0-c4f?si=et6fUAn_HxnWcb7O)"><img src="https://img.shields.io/badge/YouTube-Tutorial-red?style=for-the-badge&logo=youtube" alt="YouTube Tutorial"></a>
</p>

<h1 align="center">✨ Frieren AI v8.0 — Official Changelog ✨</h1>
<p align="center"><b>Integrated System & Engine Update</b></p>

---

> ⚠️ **Important:**  
> 📥 **Download the module exclusively from our official Telegram channel:** [@terxofficial](https://t.me/terxofficial)  
> 📹 **Step-by-step bypass tutorial now available on YouTube:** [Watch Here](https://youtube.com/shorts/j8NwzROQTuI?si=lgID-q6cr3Y2t2xG) <!-- Replace with your actual link -->

---

## 🔐 Account & Security
- **Forced Sign‑In** – All tools now require authentication; new users are immediately greeted with a login screen.
- **Owner Alerts** – On every new sign‑up, the owner receives a detailed Telegram notification containing full device and user information.

## ⚙️ Automation & Control
- **Spells System** – Toggles now execute root shell scripts and persist their state locally.
- **Game List Manager** – Packages written to `gamelist.txt` and `render.txt` are instantly applied by the engine—no restart required.

## 📢 User Interface
- **Local Broadcast Banner** – Reads data directly from storage, no server fetch needed.
- **Appeal Page** – Feedback and images are sent directly to Telegram.
- **Persistent Settings** – FPS, refresh rate, graphics, spells, and game list all survive app restarts.

## 🧹 Offline & Clean
- **Fully Offline** – All external API calls have been removed; the app works completely offline—no AI server required.

---

## 🚀 Engine Core – Performance & Stability

### ◻️ Render Pipeline
- **Native Render Binaries** – Replaced shell scripts with `Frieren_Vulkan`, `Frieren_SkiaGL`, and `Frieren_Hybrid`, launched via `nohup` for true background execution.
- **Conflict‑Free Activation** – Only the chosen renderer is applied; conflicting scripts are automatically killed.

### 📦 Processor & Thermal
- **Frieren_Chipset** – Recognizes the chipset via `ro.hardware`, applies processor‑specific properties, and supports `activate` / `restore` with full backup.
- **Frieren_Thermal** – Safely disables/restores all thermal services with complete zone backup; battery bypass keeps charging enabled.

### 💌 Notifications
- **Simplified Alerts** – Exactly two notifications: “Frieren AI: Performance Mode” and “Frieren AI: Restored”, each accompanied by a toast.
- **Branded** – Frieren icon used in all persistent notifications.

### 🗃️ Backup & Safety
- **Zero Permanent Changes** – Every sysfs value and system property is backed up before modification and automatically restored on game exit.
- **Crash Recovery** – Leftover backup files are reverted on engine start to prevent stale states.

### 💽 Compatibility
- **Universal Support** – Fully compatible with root, Shizuku, and non‑root devices, with graceful fallback.
- **Expanded Limits** – Game list and render map capacity extended to **65,535 entries**.

---

## 🎮 Gaming Experience
- **Extended Performance Properties** – Conflict‑free tuning of HWUI, SurfaceFlinger, Dalvik, Power HAL, and Adreno/Mali.
- **GPU Forced to Performance** – Automatic governor detection and frequency lock for maximum graphics throughput.
- **CPU Lock** – All cores pinned online with maximum priority (`-20`).
- **Network Low‑Latency** – Optimized tweaks for a smoother online gaming experience.

---

<p align="center">
  <b>Frieren AI v8.0 – Uncompromising performance, total control, and complete peace of mind</b> 🔥
</p>

<p align="center">
  <a href="https://t.me/terxofficial">📢 Join @terxofficial for downloads & updates</a>
</p>
