# 📁 File Structure

**Stream Connector/**
- **saved/** – Central storage for all app data  
  - **changelogs/** – Markdown and JSON logs for UI release notes
    - `version.json` – Read at runtime for version change UI
  - **config/** – Main configuration directory
    - **devices/** – PiShock registered devices
    - **filters/** – Log filter profiles
      - `noisy_parameters.json` – User-tunable log filter
      - `nuclear.json` – User-tunable log filter
    - **userdata/** – License validation and tier info
      - `license.json` – Created/updated on launch
  - **controls/** – Stored control profiles
    - **backup/** – Auto-saved control backups
    - **chains/** - The core files that run it all
       - **backup/** - Backup chain files that create automatically
    - **export/** - Exported chain files that can be imported to different avatars
    - **owo/** - owo control files created by users with the [Sensations Creator](https://owo-game.gitbook.io/owo-api/tools/sensations-creator)
  - `giftMapping.json` – Required for chain preview icons and values
- `Stream Connector.exe` – Compiled application binary

---

### 📌 Notes

- All persistent user data lives under `saved/` — including licenses, logs, and controls.
- `license.json` now includes both primary DRM and supporter key fields.
- `giftMapping.json` must be valid for chain UI previews to work properly.
- `radials/` is a placeholder for upcoming radial dial/slider support.

---

# Stream Connector

### 🔗 The Ultimate Interactive Control Engine for TikFinity, TikTok, VRChat, and Shock Feedback

**Stream Connector** is a purpose-built, GUI-powered platform for streamers and avatar creators who demand full control over event responses, PiShock devices, and real-time avatar logic.

Designed with creators in mind, it fuses modern Python capabilities, VRChat OSC, TikTok Live events, PiShock integration, and a powerful reactive chain engine.

---

## 🌟 Features Summary

### 🎁 TikTok Live
- Respond to likes, gifts, follows, subs, and comments.
- Includes event chaining, intensity scaling, and manual triggers.

### 🧩 Chain Logic Engine
- Build visual chain sequences with delay, timers, and mode mixing.
- Chains support OSC, PiShock, custom events, and advanced fallback logic.

### 🧠 VRChat OSC
- Automatically discovers avatar parameters from JSON + live cache.
- Supports override patterns, forced resets, and untouchable address protection.

### ⚡ PiShock Support
- Realtime WebSocket v2 support
- Custom pattern modes (licensed only: Bronze+ required)
- Owned/shared device logic

### 🖥️ Flask API & Web Layer
- Integrate with Twitch, Webhooks, or OBS via REST
- Supports live reload, diagnostics, and OSC injection

---

## 🛡️ Licensing & Tiers

- **DRM-Protected** (Gumroad licensing)
- **Tiered Access**:
  - Bronze+ → Advanced PiShock modes
  - Silver+ → Pattern Editor
  - Gold+ → Full feature unlock, early features, diagnostics

License is verified and cached on launch. Fallbacks and UI behaviors depend on tier.

---

## 🤝 Join the Community

- 💬 [Discord Server](https://discord.gg/AzjwzMJU6K)
- 🎥 [My Socials](https://vixenlicious.carrd.co/)
- 🌐 [VRChat Group](https://vrc.group/THEVIX.5990)

---

## 💖 Support the Project
- ☕ [Ko-fi](https://ko-fi.com/vixenlicious)

Your support powers continuous updates and new integrations.

---

## 🛍️ Get It Now

🔗 [Download on Gumroad →](https://vixenlicious.gumroad.com/)

Includes:
- Executable binary
- TikFinity ready UI
- Sample chains
- Supporter tier activation

---

## 🧠 Crafted by Vixenlicious

Built from the ground up to support streamers, VTubers, and immersive creators.  
Always evolving. Always yours.
