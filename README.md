# BLEACH: Heat the Soul 7 — PC Native Recompilation (Beta v1.0)

[![Latest Release](https://img.shields.io/github/v/release/krprojecthts/Bleach-HTS7-Releases?include_prereleases&label=Download&color=orange&style=for-the-badge)](https://github.com/krprojecthts/Bleach-HTS7-Releases/releases/latest)
[![Platform](https://img.shields.io/badge/Platform-Windows%2010%2F11%20(64--bit)-blue?style=for-the-badge)](#system-requirements)
[![Netcode](https://img.shields.io/badge/Netcode-GGPO%204--Slot%20Rollback-brightgreen?style=for-the-badge)](#key-features)

A native PC static recompilation of ***BLEACH: Heat the Soul 7*** (`NPJH50275`), rebuilt from the ground up with 60 FPS combat, GGPO-based rollback netcode, 4-player online Battle Royale, upgraded stage lighting, and full modding support.

> **[Download Latest Release (Beta v1.0 — Windows 64-bit)](https://github.com/krprojecthts/Bleach-HTS7-Releases/releases/latest)**

---

## Key Features

* **60 FPS Native Gameplay** — Locked, fluid 60 FPS gameplay doubling the original PSP framerate for responsive combos and crisp combat pacing.
* **GGPO-Based Rollback Netcode** — Custom rollback netcode supporting **1v1**, **Tag Team**, and **4-Player Online Battle Royale**.
* **Rebuilt Online Lobby & 4P Battle Royale** — Custom Fighter Cards, public/private rooms, live room chat, 2×2 quad ready-up cards, and per-player independent camera views in 4-player matches.
* **Modern Training Mode Suite** — Real-time frame data readouts, AI dummy recording & playback, and instant neutral repositioning.
* **Replay Engine & Direct MP4 Export** — Save matches, review frame-by-frame, and export clean high-definition MP4 clips straight from the game.
* **Upgraded Lighting Engine** — Dynamic stage-matched character lighting and sharper shaders.
* **Custom Jukebox & Soundtrack Manager** — Load custom battle themes and menu tracks directly in-game.
* **Full Roster, Shuren & Restored Outfits** — All 80+ characters (including *Hell Verse* Shuren) unlocked across every mode, plus all alternate color palettes restored in Battle Royale.
* **In-Game Texture Mods** — Built-in texture dumping and live reloading (`△ Texture Mods`) for custom character and stage packs.
* **Native PC Controls** — Plug-and-play XInput controller support, keyboard bindings, custom button remapping, and macros.

---

## Quickstart Installation & Setup

### 1. Download the PC Build
1. Go to the **[Latest Releases Page](https://github.com/krprojecthts/Bleach-HTS7-Releases/releases/latest)** (no GitHub account required).
2. Scroll down to **Assets** and download **`Bleach_Heat_the_Soul_7_Beta_Version_1.0.zip`**.
3. Extract the entire ZIP into its own clean folder (for example, `C:\Games\Bleach_HTS7_PC\`). **Do not launch from inside the ZIP archive.**

### 2. Supply Your Game Files (`NPJH50275` — Japanese v1.01)
Copyrighted PSP game assets are not distributed in this repository. You must provide your own clean, unmodified dump of ***BLEACH: Heat the Soul 7* (`NPJH50275` — Japan v1.01)**, including the **decrypted `EBOOT.BIN`** and `.iso`:

**How to dump your decrypted `EBOOT.BIN` using PPSSPP:**
1. Open **PPSSPP** and go to **Settings → Tools → Developer tools**.
2. Check **"Dump decrypted EBOOT.BIN on game boot"**.
3. Boot your clean *Bleach: Heat the Soul 7* (`NPJH50275`) `.iso` for a few seconds, then close PPSSPP.
4. Open PPSSPP's `memstick\PSP\SYSTEM\DUMP\` folder, copy **`NPJH50275.BIN`**, and rename it to **`EBOOT.BIN`**.
*(Use a clean Japanese `NPJH50275` dump—do not use an `EBOOT.BIN` from a pre-patched English translation ISO, as modified executable offsets will not match.)*

**File Placement:**
* Place your clean **`.iso`** and decrypted **`EBOOT.BIN`** into your extracted `Bleach_HTS7_PC` folder alongside `BleachNative.exe`.

### 3. Launch & Play
1. Run **`BleachNative.exe`** (if Windows SmartScreen prompts you, click **More info → Run anyway**).
2. Press **`Alt + Enter`** or **`F11`** anytime to toggle Borderless Fullscreen.
3. Open **Online** to create your Fighter Card and join or host **1v1**, **Tag Team**, or **4P Battle Royale** rooms.

---

## System Requirements

* **OS:** Windows 10 / Windows 11 (64-bit)
* **GPU:** Vulkan-compatible graphics card (NVIDIA GTX 900+ / AMD RX 400+ / modern Intel integrated)
* **Controller:** Xbox / PlayStation / XInput controller or Keyboard

---

## Beta v1.0 Verification & Known Notes

* **SHA-256 (`Bleach_Heat_the_Soul_7_Beta_Version_1.0.zip`):** `EFC70CBCA98588C620A4B6EFD11E34988B1E36F96A2AB0EF9D8C4E9FB8D6A7A1`
* **4P Battle Royale HUD:** Remote human players currently display the original PSP `"CPU"` label next to their top health bar—refer to the custom online nameplates underneath for real player names.

---

## Disclaimer
This project is a fan-made native PC recompilation built on `psp-recomp` and contains **no copyrighted Sony or Bandai Namco game assets, ROMs, ISOs, or decrypted binaries**. Users must supply their own legally obtained copy of *BLEACH: Heat the Soul 7* (`NPJH50275`).
