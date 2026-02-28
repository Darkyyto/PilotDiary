<div align="center">
  <img src="https://cdn.discordapp.com/attachments/1447257632908771440/1477093325789200466/copertina.png?ex=69a381db&is=69a2305b&hm=1d446e9de2151860ea71bbccb0161703e31fdb35518084cfdb6211d35275bbd0&" alt="Pilot Diary Cover" width="100%">
  
  <br>
  <strong>A premium, glassmorphism Digital Kneeboard overlay for modern flight simulators.</strong>
  <br>
  
  [![Release](https://img.shields.io/github/v/release/Darkyyto/PilotDiary?style=for-the-badge&color=white&labelColor=black)](https://github.com/Darkyyto/PilotDiary/releases)
  [![Platform](https://img.shields.io/badge/Platform-Windows-blue?style=for-the-badge&color=white&labelColor=black)]()
  [![Built with Electron](https://img.shields.io/badge/Electron-40.6-000000?style=for-the-badge&logo=electron&logoColor=white)]()
</div>

<hr>

## Overview
**Pilot Diary** is a sophisticated, frameless utility designed specifically for virtual aviators across MSFS, X-Plane, and Prepar3D. It brings an essential toolkit—ATC logging, dynamic METAR weather data, and customizable settings—directly into your cockpit without breaking immersion.

Built with a stunning, translucent **"Silver Glassmorphism"** aesthetic, Pilot Diary floats over your simulator window. It is built to be clean, distraction-free, and hyper-efficient during critical phases of flight on VATSIM or IVAO.

---

## ✨ Features
* **Advanced ATC Scratchpad** 📝
  * Ditch the pen and paper. Specific, separated grids for **IFR Clearance (C.R.A.F.T.)**, **Pushback & Startup**, **Taxi**, **Enroute Control**, and **Approach**.
  * Instant "Copy C.R.A.F.T" to clipboard button.
* **Live Aviation Weather Data** 🌤️
  * Query 4-letter ICAO codes instantly.
  * Receive fully parsed METAR strings visualized clearly, including Flight Rules (VFR/IFR), Wind Direction, Visibility, and Temperatures.
* **Premium Glassmorphism Design** 💎
  * Blurred, translucent backgrounds (`backdrop-blur`) that don't block out your flight deck instruments.
  * Silver, neon-white highlights for maximum readability in night-flying scenarios.
* **Always-On-Top & Frameless** 📌
  * Native Windows dragging mechanism integrated directly into the UI.
  * Pin button to force the kneeboard above all other windows, meaning it stays active even when clicking inside MSFS.
* **Silent Auto-Updates** 🔄
  * Integrated background updater pulling directly from GitHub Releases. You'll never have to manually check for a new version.
* **Global Localization** 🌍
  * Native translation support for over 15+ languages to suit pilots worldwide.

---

## 📥 Installation

1. Navigate to the [**Releases**](https://github.com/Darkyyto/PilotDiary/releases) tab.
2. Download the latest `Pilot Diary Setup X.X.X.exe`.
3. Run the installer (it does not require Administrator privileges).
4. Launch Pilot Diary alongside your simulator. That's it!

---

## 🛠️ Development

If you'd like to build the project from source or contribute to Pilot Diary:

### Prerequisites
* [Node.js](https://nodejs.org/) (v18 or higher)
* [npm](https://www.npmjs.com/)

### Running Locally
```bash
# Clone the repository
git clone https://github.com/Darkyyto/PilotDiary.git

# Enter the directory
cd PilotDiary

# Install dependencies
npm install

# Run the live Vite + Electron development server
npm run dev
```

### Building for Production
```bash
# Compile and build the NSIS installer
npm run build
```
Once the build is complete, the standalone executable will be placed in the `/release` directory.

---

<div align="center">
  <em>Developed by Darko Studio. Fly safe.</em>
</div>
