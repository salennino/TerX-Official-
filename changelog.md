<p align="center">
  <img src="https://img.shields.io/badge/Frieren%20AI-v7.5-blue?style=for-the-badge" alt="Version">
  <a href="https://t.me/terxofficial"><img src="https://img.shields.io/badge/Telegram-Join%20Channel-2CA5E0?style=for-the-badge&logo=telegram" alt="Telegram"></a>
</p>

<h1 align="center">🚀 Frieren AI v7.5 — Official Changelog</h1>
<p align="center"><b>Stability · Security · Performance · Reliability</b></p>

---

## 📢 Bug Fix & Stability Update

We are proud to release **Frieren AI v7.5**, a major maintenance and optimization update focused on improving system stability, reliability, performance consistency, and user experience across both root and non‑root environments.

This update brings smarter server synchronization, safer kernel handling, improved boot protection, enhanced AI integration, and expanded performance controls for gaming optimization.

---

## 📋 Detailed Changelog

### 🌐 System & Synchronization
- **🟢 Dynamic Online Status Indicator**  
  The module description now displays a live online/offline indicator using a 🟢/🔴 status system powered by a GitHub‑hosted `status.json` file.
- **🔄 GitHub Actions Auto‑Sync**  
  Automated GitHub Actions synchronization checks the AI health endpoint every 5 minutes to ensure accurate server status updates.

### 🛡️ Stability & Boot Protection
- **🛡️ Safe Anti‑Kernel Panic**  
  Improved kernel panic protection logic by disabling triggers only when the target files exist and are not already set to safe values, preventing potential boot instability.
- **⏱️ Bootloop Prevention**  
  Optimized boot delays and background execution handling to eliminate early‑boot network hangs and reduce bootloop risks.
- **📝 Robust File Handling**  
  Fixed an issue where the `statusUrl` entry could disappear from `module.prop` due to improper newline handling during description updates.
- **📄 Diagnostic Logging**  
  All server checks, sync updates, and status events are now logged to `/data/local/tmp/frieren_status.log` for easier debugging.

### 🔐 Security & Authentication
- **🔑 Forced Login System**  
  All interactive systems — Spells, AI Analysis, Performance Tweaks, Optimization Controls — now require successful authentication before use.
- **🚫 Server‑Driven Ban System**  
  Ban and unban status is now fully controlled by the server without local persistence, allowing instant unban synchronization.
- **📱 Advanced Device Recognition**  
  Real hardware specifications are automatically detected before login and securely sent to the server to prevent spoofed login data.
- **🚪 Logout & Privacy Improvements**  
  Logging out now automatically opens the sign‑in interface, clears cached device information, and prevents cross‑user data leakage.

### 💬 AI & Chat Improvements
- **🤖 Offline AI Fallback**  
  Integrated offline fallback responses to maintain usability even when the AI server becomes unreachable.
- **💬 Persistent Chat System**  
  Chat button functionality restored; chat history now persists across sessions and can be restored locally after a restart.
- **⚙️ Live AI Engine Control**  
  Disabling `ai.txt` now gracefully shuts down the AI engine without instability.

### ⚡ Performance Engine Enhancements
- **🚀 Instant Performance Mode**  
  Removed tier‑based optimization scaling — all available performance enhancements now activate immediately once a game launches.
- **🧩 Dedicated Render Binaries**  
  Replaced Vulkan, SkiaGL, and Hybrid scripts with optimized standalone `Frieren_*` binaries executed through `nohup`.
- **🧹 Clean Shutdown System**  
  All helper binaries and background processes are automatically terminated using `pkill -9 -f` after game exit.
- **🎚️ Persistent Sliders**  
  FPS and refresh‑rate sliders now restore previously saved values automatically after reload.
- **🛠️ Extended System Properties**  
  Added support for VSYNC, Cache Size, Touch Latency, Frame Pacing, and vendor‑specific rendering properties.
- **🚀 GPU / CPU Lock**  
  GPU forced into maximum performance mode; CPU locked between 95–100% maximum frequency.
- **🔥 Thermal Override**  
  `thermal.txt` or `extreme.flag` can now fully disable thermal throttling for maximum sustained performance.
- **🔋 Battery Safety Protection**  
  Default system values are automatically restored when battery level drops below 20%.

### 🔔 System Features
- **🔔 Dual Notification System**  
  Added persistent icon‑based notifications and instant pop‑up toast alerts for real‑time engine feedback.
- **💾 Full Backup & Restore**  
  All sysfs values, system properties, and performance configurations are backed up before tweaks and automatically restored after gameplay ends.
- **📦 Expanded Limits**  
  Now supports up to **65,535 entries** in both `gamelist.txt` and `render.txt`.
- **🛠️ Root & Non‑Root Compatibility**  
  Fully compatible with Root Access, Shizuku, and limited Non‑Root Mode.

---

## 🌐 Official Channel

Stay updated and join the community:  
[**@terxofficial on Telegram**](https://t.me/terxofficial)

---

<p align="center"><i>Thank you for supporting Frieren AI.</i></p>
