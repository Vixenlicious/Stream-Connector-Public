## 📁 File Structure

**Stream Connector Beta/**
- **saved/** – Root storage folder for all files  
  - **changelogs/** – Storage location for changelogs  
    - `version.json` – Changelog file for program to read on button click  
  - **config/** – Configuration storage location  
    - **devices/** – PiShock device information storage  
    - **filters/** – Logging-window filter suppressor  
      - `noisy_parameters.json` – Modifiable by user to reduce spam in log window  
    - **userdata/** – Storage location for license data  
      - `license.json` – Created on first launch  
  - **controls/** – Control files  
    - **backup/** – Automatic backups  
  - **radials/** – Future feature  
  - `giftMapping.json` – Required for chains to load images/values  
- `Stream Connector.exe` – Compiled executable  

### 📌 Notes

- `saved/` acts as the central repository for application data, configuration, logs, and backups.
- `config/` holds all device, license, and filter configuration.
- `giftMapping.json` is required for dynamic visual or data-based chain operations.
- `radials/` is reserved for future features and may be empty currently.



# Stream Connector

### 🔗 The Ultimate Python Client for TikFinity, TikTok, VRChat, and Streaming Interactivity

Welcome to **Stream Connector**, a premium, closed-source application built for creators, VTubers, and streamers who want to bring **real-time reactivity** into their VRChat avatars and streaming setup.

From TikTok Live gifts to PiShock triggers, Stream Connector links everything with visual flair, powerful logic chains, and a beautiful glass-dark UI.

---

## 🌟 Key Features

- **TikTok Integration**
  - React to follows, likes, comments, gifts, shares, and more.
  - Use TikTok Live events to power real-time avatar responses.

- **TikFinity Event Engine**
  - Full API endpoint support for TikFinity actions and categories.
  - Bind TikFinity gift or subscriber events to complex reaction chains.

- **VRChat OSC Toolkit**
  - Real-time avatar parameter control via OSC.
  - Auto-detect and manage avatars, controls, and address states.

- **Chain Reactions**
  - Link multiple actions into logic sequences with delay, reset, and looping.
  - Powerful GUI to create, edit, and debug multi-step reactions.

- **PiShock API Support**
  - WebSocket v2 client for shock, vibrate, and beep effects.
  - Supports both owned and shared PiShock devices.

- **Web Interface & API**
  - Flask-powered API layer for integration with Twitch or Webhooks.
  - Includes action registry, reloading, and diagnostics endpoints.

---

## 🌐 Connect With Us

Come be part of the creative and interactive community that powers Stream Connector:

- 💬 **Discord Community**  
  [Join here →](https://discord.com/invite/6YCQG8N7fv)

- 📱 **TikTok**  
  [Follow @vixenlicious →](https://www.tiktok.com/@vixenlicious)

- 🧠 **VRChat Group**  
  [Join THEVIX Group →](https://vrc.group/THEVIX.5990)

---

## 💖 Support the Project

If you love what Stream Connector enables, support its development and future upgrades:

- 💸 **CashApp** → [https://cash.app/$Vixenlicious](https://cash.app/$Vixenlicious)
- ☕ **Ko-fi** → [https://ko-fi.com/vixenlicious](https://ko-fi.com/vixenlicious)

---

## 🛍️ Get Stream Connector

This software is exclusive and distributed only through Gumroad:

➡️ **[Download on Gumroad →](https://vixenlicious.gumroad.com/)**

Includes:
- Executable application
- UI assets
- Default chains and configurations
- Priority access to new features

---

## 🔒 License

Stream Connector is a **closed-source** premium application provided for personal use only.  
Redistribution, modification, or reverse engineering is strictly prohibited.

---

## 🧠 Built with Passion

Crafted by [@vixenlicious](https://www.tiktok.com/@vixenlicious)  
Made for immersive creators who demand power, polish, and performance.

---
