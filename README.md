<div align="center">

# Smart Simulation

**Intelligent Sims 4 mod for faster, smoother, and more stable gameplay**

[![GitHub Issues](https://img.shields.io/github/issues/invinciblebug/SmartSimulation?style=flat-square&color=red)](https://github.com/invinciblebug/SmartSimulation/issues)
[![GitHub Pull Requests](https://img.shields.io/github/issues-pr/invinciblebug/SmartSimulation?style=flat-square&color=blue)](https://github.com/invinciblebug/SmartSimulation/pulls)
[![License](https://img.shields.io/badge/License-Proprietary-red?style=flat-square)](https://github.com/invinciblebug/SmartSimulation/blob/main/LICENSE)
[![GitHub Last Commit](https://img.shields.io/github/last-commit/invinciblebug/SmartSimulation?style=flat-square&color=orange)](https://github.com/invinciblebug/SmartSimulation/commits/main)
[![GitHub Release](https://img.shields.io/github/v/release/invinciblebug/SmartSimulation?style=flat-square&color=purple)](https://github.com/invinciblebug/SmartSimulation/releases)
[![Sims 4 Version](https://img.shields.io/badge/Sims%204-v1.126.73.1030-blue?style=flat-square)](https://www.ea.com/games/the-sims/the-sims-4)
[![Core Library](https://img.shields.io/badge/Core%20Library-v1.43-orange?style=flat-square)](https://lot51.cc/mods/core-library)
[![Platform](https://img.shields.io/badge/Platform-Windows%20%7C%20macOS%20%7C%20Linux-lightgrey?style=flat-square)](#installation)
[![Donate](https://img.shields.io/badge/Donate-Cryptocurrency-yellow?style=flat-square)](#support-my-work)

</div>

---

**Smart Simulation** is an intelligent Sims 4 mod designed for faster, smoother, and more stable gameplay with safe simulation optimizations.

It helps improve simulation responsiveness, reduce stalls, and keep gameplay feeling smooth without changing the core experience.

---

> [!IMPORTANT]
> **Official Sources Only**
> Always download Smart Simulation from official sources to ensure you get the latest, safe version:
> - **GitHub Releases**: https://github.com/invinciblebug/SmartSimulation/releases
> - **CurseForge**: https://www.curseforge.com/sims4/mods/smart-simulation
> - **Official Website**: https://invinciblebug.github.io
>
> Avoid downloading from third-party sites unless you trust the source.

> [!NOTE]
> This mod is proprietary software. See the [License](#license) section for usage terms.

---

> [!TIP]
> **Star this Repository**
> If you love this mod and want to help keep it active, all you have to do is sign in to GitHub and star this repository project. It shows your appreciation and helps others discover the mod. Thank you for your support!
>
> **Support Development**
> You can also support development by donating cryptocurrency. Every contribution helps maintain and improve the mod. See the [Support My Work](#support-my-work) section for details.

> [!NOTE]
> **Report Issues**
> If you have any issues, please report them on GitHub Issues:
> https://github.com/invinciblebug/SmartSimulation/issues/new?template=bug_report.yml

---

## Features

* **Stall Recovery** - Automatically detects and recovers from Sims freezing or getting stuck
* **Timeline Freeze Detection** - Detects when the game's internal timeline gets stuck and recovers gracefully
* **Head Bobbing Prevention** - Fixes the annoying "head bob" freeze effect where Sims stare into space
* **Fast Loading Screen** - Speeds up the loading screen with an adjustable multiplier
* **Routing Stall Detection** - Detects and recovers from Sims stuck pathfinding
* **Detailed Error Logs** - Includes sim info, lot details, and queued actions when errors occur
* **Automatic Updates** - Notifies you when a new version is available
* **In-Game Debug Commands** - View status, change settings, and run diagnostics without leaving the game
* **Cross-Platform** - Works on Windows, macOS, and Linux (including Steam/Proton)
* **Offline-Friendly** - Works perfectly without internet connection
* **Lightweight** - No performance overhead, only optimizations
* **Mod Compatible** - Works alongside MCCC, Basemental, Meaningful Stories, and other mods

---

## Issues Resolved

Smart Simulation fixes these common gameplay problems:

* **Sims Standing Still** - Sims freeze and refuse to perform any actions
* **Timeline Freezes** - The game simulation gets stuck and Sims stop progressing
* **Head Bobbing** - Sims stare into space with a frozen "head bob" effect
* **Stalled Interactions** - Interactions get stuck and never complete
* **Eating/Cleaning/Sleeping Problems** - Sims refuse to complete basic needs actions
* **Slow Loading Screens** - Loading screens take too long
* **Routing Failures** - Sims get stuck trying to walk somewhere
* **Simulation Slowdowns** - General lag during busy gameplay moments

---

## Performance Benefits

* **Smoother Simulation** - Game runs at consistent speed without stuttering
* **Reduced Lag** - Minimizes slowdowns during busy gameplay moments
* **Faster Loading** - Adjustable loading screen speed multiplier
* **No Compatibility Issues** - Designed to work with other mods including MCCC
* **Safe & Reversible** - All optimizations can be disabled individually
* **Zero Overhead** - The mod itself uses negligible resources

---

## What This Mod Does

Smart Simulation is designed to be non-invasive. It only does these things:

* **Detects stuck Sims** - When a Sim freezes or stops responding, the mod notices
* **Recovers stuck Sims** - Automatically gets stuck Sims moving again
* **Optimizes loading screens** - Makes loading screens faster with an adjustable multiplier
* **Tunes game performance** - Adjusts time slice and clock speed for smoother simulation
* **Logs errors with context** - When something goes wrong, it saves detailed info to help fix it

## What This Mod Does NOT Do

* **Does NOT change autonomy** - Your Sim's decision-making stays exactly the same
* **Does NOT affect other mods** - Works alongside MCCC, Basemental, Meaningful Stories, etc.
* **Does NOT change game speed** - Simulation runs at normal speed (except during loading)
* **Does NOT alter NPC behavior** - Background Sims act normally

The mod only detects when something gets stuck and recovers it. That's it.

---

## Detailed Error Logging

When an error or crash occurs, Smart Simulation logs detailed information to help diagnose the issue:

* **Sim Info** - Which sim caused the error (name, age, NPC status)
* **Lot Details** - Current lot name and how many sims are on it
* **Queued Actions** - What the sim was trying to do when the error occurred
* **Full Traceback** - Complete error stack trace for debugging

This information is included in the `ss-DD-MM-YYYY.log` file and helps identify exactly what caused the issue.

---

## Installation

> [!TIP]
> Enable script mods in Game Options > Other > Enable Custom Content and Mods before installing.

1. Download the latest release from the **Releases** page.
2. Extract the files.
3. Copy the included files into:

```text
Documents/Electronic Arts/The Sims 4/Mods/
```

4. Enable:

   * **Custom Content and Mods**
   * **Script Mods Allowed**

5. Restart The Sims 4.

The mod file is named: `[INVINCIBLEBUG] SmartSimulation v{version}.ts4script`

---

## In-Game Commands

Use these commands in the cheat console (Ctrl+Shift+C) while in Live mode:

| Command | Description |
|---------|-------------|
| `ss.status` | Show mod status and statistics |
| `ss.config` | Show all current settings |
| `ss.set_config <key> <value>` | Change a setting and save it |
| `ss.dump_timeline` | Dump timeline heap to log file |
| `ss.reset_state` | Reset watchdog state manually |
| `ss.diagnostics` | Dump full diagnostic report to log |
| `ss.help` | Show all available commands |

Example: `ss.set_config loading_speed_multiplier 5` to speed up loading screens.

### Configuration File (.dat)

You can also configure settings by editing the `smart_simulation.dat` file directly:

**Location:** `Documents/Electronic Arts/The Sims 4/[INVINCIBLEBUG]/smart_simulation.dat`

**Priority Chain:**
```
1. Runtime cheat commands (ss.set_config)  ← Highest priority
2. .dat file overrides (game start)
3. Mod defaults (hardcoded)                ← Lowest priority
```

Edit the `.dat` file before starting the game to apply your preferred settings automatically on startup.

## Dependencies

Smart Simulation requires **Core Library** by Lot 51 to function.

- **Download**: https://lot51.cc/mods/core-library
- **Required**: `lot51_core.ts4script`
- **Included**: The release bundle includes Core Library - no separate download needed

> [!IMPORTANT]
> Both files must be in your Mods folder for the mod to work.

---

## Update Checks

Smart Simulation can check for newer releases and notify the player when an update is available.

If the game is offline or the internet is unavailable, update checks are skipped safely and the mod continues normally.

---

## Logs

The mod creates its logs inside:

```text
Documents/Electronic Arts/The Sims 4/[INVINCIBLEBUG]/
```

Example log files:

```text
ss-01-08-2026.log
act-01-08-2026.log
config-01-08-2026.log
smart_simulation.dat
LICENSE
README.md
```

Log files use daily date-stamped filenames (DD-MM-YYYY format). Logs older than 30 days are automatically deleted. On-demand file I/O ensures no file handles are kept open.

> [!TIP]
> On first load, the mod creates a `README.md` file in the `[INVINCIBLEBUG]` folder with complete documentation of all configuration options and cheat commands. Check it for detailed settings reference.

> [!IMPORTANT]
> When reporting issues, always include ALL log files from the date the issue occurred:
> - `ss-DD-MM-YYYY.log` (main log)
> - `act-DD-MM-YYYY.log` (sim activity log)
> - `config-DD-MM-YYYY.log` (config state log)

---

## Compatibility

> [!CAUTION]
> Always check the tested version before installing. New game updates may require mod updates.

Smart Simulation is designed to work with the latest version of The Sims 4.

**Tested Version:** `1.126.73.1030`

If a game update changes behavior, a new release will be published as soon as possible.

---

## Troubleshooting

### Mod Not Working

If the mod doesn't seem to be working, check these common issues:

**1. Script Mods Not Enabled**
- Go to Game Options → Other → Enable Custom Content and Mods
- Make sure both "Custom Content" and "Script Mods" are enabled
- Restart The Sims 4 after enabling

**2. Files Not in Correct Location**
- Both files must be in: `Documents/Electronic Arts/The Sims 4/Mods/`
- Files can only be ONE subfolder deep (e.g., `Mods/[INVINCIBLEBUG]/mod.ts4script`)
- Do NOT place files two or more folders deep

**3. Internet Connectivity**
- **The mod works completely offline** - no internet required for normal gameplay
- Internet is ONLY used for: checking for updates (optional)
- If update check fails, the mod continues working normally
- You can disable update checks in the config if desired

**4. Windows Security / Antivirus**
- Some antivirus software may block script mods
- Add the Mods folder to your antivirus exceptions/exclusions list
- Windows Defender: Settings → Update & Security → Windows Security → Virus & threat protection → Manage settings → Exclusions → Add an exclusion → Folder → Select Mods folder
- Make sure the mod files are not quarantined or deleted

**5. Outdated Mod Version**
- Check if you have the latest version from [GitHub Releases](https://github.com/invinciblebug/SmartSimulation/releases)
- Compare your version with the latest release version

**6. Conflicts with Other Mods**
- Try removing other script mods one by one to identify conflicts
- Common conflicting mods: MCCC, Basemental, other performance mods
- Test with only Smart Simulation installed first

**7. Check Log Files**
- Look for error messages in `Documents/Electronic Arts/The Sims 4/[INVINCIBLEBUG]/`
- The `ss-DD-MM-YYYY.log` file shows mod activity and errors
- The `config-DD-MM-YYYY.log` file shows your current configuration

### Sims Still Getting Stuck

If Sims are still getting stuck after installing Smart Simulation:

1. **Increase stall threshold**: `ss.set_config stall_count_threshold 300`
2. **Increase progress timeout**: `ss.set_config progress_timeout_seconds 60`
3. **Enable verbose logging**: `ss.set_config verbose true`
4. **Check logs** for error messages

### Loading Screens Still Slow

If loading screens are still slow:

1. **Verify loading speed is enabled**: `ss.set_config enable_loading_speed true`
2. **Increase multiplier**: `ss.set_config loading_speed_multiplier 5`
3. **Check timeout**: `ss.set_config loading_speed_timeout 180`

---

## Reporting Issues

If you run into a problem, please:

1. **Create an issue on GitHub** at:
   **https://github.com/invinciblebug/SmartSimulation/issues**

2. Include the following information:
   * Smart Simulation version
   * The Sims 4 version
   * A clear description of the issue
   * **ALL log files from the date the issue occurred** (from `Documents/Electronic Arts/The Sims 4/[INVINCIBLEBUG]/`):
     - `ss-DD-MM-YYYY.log` (main log)
     - `act-DD-MM-YYYY.log` (sim activity log)
     - `config-DD-MM-YYYY.log` (config state log)

3. **For discussions, questions, or help**, start a discussion at:
   **https://github.com/invinciblebug/SmartSimulation/discussions**

---

## Releases

Download the latest version here:

**https://github.com/invinciblebug/SmartSimulation/releases**

---

## Credits

Developed by **Invincible Bug**.

**Official Sources:**
- **Website**: https://invinciblebug.github.io
- **GitHub**: https://github.com/invinciblebug?tab=repositories
- **CurseForge Profile**: https://www.curseforge.com/members/invinciblebug
- **CurseForge Projects**: https://www.curseforge.com/members/invinciblebug/projects

Thanks to the Sims 4 modding community for tools, documentation, and shared knowledge.

---

## About

Thanks for trying Smart Simulation! I created this mod to help improve your gameplay experience.

I made this mod for myself because my Sims 4 setup has become quite extensive:
- Over 20,000 animations
- 10,000+ mods (including both package and .ts4script files)

With this many mods, my Sims 4 game became very slow, the timeline would frequently get stuck, and sometimes Sims would stop working entirely. I needed a solution to keep my game playable and enjoyable.

Smart Simulation is the result of my efforts to optimize simulation performance and recover from stalls. I hope it helps your gameplay experience as much as it has helped mine.

---

## FAQ

<details open>
<summary><strong>Does this mod conflict with other mods?</strong></summary>

No, Smart Simulation is designed to be compatible with most mods. However, some mods like MCCC (MC Command Center) may have conflicts if you manually change certain settings. I've made sure it won't conflict unless there are specific updates or changes to those mods.

</details>

<details>
<summary><strong>Does this mod get regular updates?</strong></summary>

Yes! Smart Simulation receives regular updates with testing and improvements. I actively maintain and test the mod to ensure compatibility with the latest Sims 4 versions and to address any issues that arise.

</details>

<details>
<summary><strong>I have an issue, what should I do?</strong></summary>

Please report any issues on GitHub Issues. You'll need to sign in to GitHub to create an issue. I'll resolve issues as fast as possible. When reporting, please include:
- Smart Simulation version
- The Sims 4 version
- A clear description of the issue
- **ALL log files from the date the issue occurred** (ss-*.log, act-*.log, config-*.log)

</details>

<details>
<summary><strong>Is this mod paid?</strong></summary>

No, Smart Simulation is completely free to use. There are no costs or fees associated with downloading or using this mod.

</details>

<details>
<summary><strong>Does this mod contain malware or viruses?</strong></summary>

No, Smart Simulation does not contain any malware or viruses. The mod is safe to use and only contains the code necessary for simulation optimization.

</details>

<details>
<summary><strong>Will this mod slow down my game?</strong></summary>

No, Smart Simulation is designed to be lightweight and focused on performance. It should actually improve your game's performance by reducing simulation slowdowns and stalls.

</details>

<details>
<summary><strong>Does this mod make my game load faster?</strong></summary>

No, this mod does not significantly affect game loading times. It may have a very small effect depending on your PC or laptop specifications, but its primary purpose is to make gameplay smoother and prevent the simulation from getting stuck, not to make your game load faster.

</details>

<details>
<summary><strong>Does this mod make my game super fast?</strong></summary>

No, Smart Simulation does not make your game extraordinarily fast. It focuses on making gameplay smooth and preventing Sims from getting stuck or the timeline from freezing. The mod optimizes simulation responsiveness rather than increasing overall game speed.

</details>

<details>
<summary><strong>What platforms does this mod support?</strong></summary>

Smart Simulation supports all major platforms:
- **Windows** - Full support
- **macOS** - Full support
- **Linux** - Full support (including Steam/Proton, Lutris, and EA App versions)

</details>

<details>
<summary><strong>Does this mod work with the free version of The Sims 4? Do I need expansion packs?</strong></summary>

Yes, Smart Simulation works with any version of The Sims 4, including the free version. You do not need any expansion packs or DLC for this mod to function. The mod is designed to work with the base game and all expansion packs, game packs, stuff packs, and kits. It will work regardless of which version or combination of content you have installed.

</details>

<details>
<summary><strong>Can I use this mod with other simulation optimization mods?</strong></summary>

While Smart Simulation is designed to be compatible, using multiple simulation optimization mods together is generally not recommended as they may interfere with each other. It's best to test one at a time.

</details>

<details>
<summary><strong>How do I know if the mod is working?</strong></summary>

The mod creates log files in `Documents/Electronic Arts/The Sims 4/[INVINCIBLEBUG]/`. You can check these logs to see if the mod is active. The `config-DD-MM-YYYY.log` file shows your current configuration. You can also use the in-game cheat command `ss.status` to see the mod's current status.

</details>

<details>
<summary><strong>Can I disable the mod temporarily?</strong></summary>

Yes, you can disable the mod by removing the `.ts4script` and `.package` files from your Mods folder, or by renaming them with a `.disabled` extension.

</details>

<details>
<summary><strong>Does this mod work with all expansion packs?</strong></summary>

Yes, Smart Simulation is designed to work with all Sims 4 expansion packs, game packs, and stuff packs, including the latest releases.

</details>

<details>
<summary><strong>Will this mod affect my save files?</strong></summary>

No, Smart Simulation does not modify your save files. It only affects the simulation runtime and does not make permanent changes to your game data.

</details>

<details>
<summary><strong>My game is still slow, what should I do?</strong></summary>

If your game is still experiencing slowdowns after installing Smart Simulation, please report the issue by creating a bug report on GitHub:

**https://github.com/invinciblebug/SmartSimulation/issues/new?template=bug_report.yml**

When reporting, please include:
- Your Smart Simulation version
- Your Sims 4 version
- Your operating system (Windows/macOS/Linux)
- A description of the slowdown (when it happens, how often)
- **ALL log files** from the `[INVINCIBLEBUG]` folder (`ss-*.log`, `act-*.log`, `config-*.log`)
- List of other mods you have installed

This helps me investigate the issue and provide a fix or workaround. Common causes of slowdowns include:
- Too many mods installed (especially script mods)
- Conflicts with other performance mods
- Outdated game or mod versions
- Large households with many Sims

</details>

<details>
<summary><strong>Where is the source code?</strong></summary>

This project is currently proprietary, so the source code is not released publicly. The mod is provided as compiled `.ts4script` and `.package` files for use in The Sims 4.

</details>

<details>
<summary><strong>How can I support you?</strong></summary>

Thank you for asking! You can support the development of Smart Simulation in the following ways:

1. **Star the repository** - Sign in to GitHub and star this project. It helps others discover the mod.

2. **Donate cryptocurrency** - Any amount is fine, no matter how small. Your support helps cover development time, maintenance, bug fixes, compatibility updates, and documentation. See the [Support My Work](#support-my-work) section for wallet addresses.

3. **Share the mod** - Tell your friends or share it on social media.

4. **Report issues** - Help improve the mod by reporting bugs on [GitHub Issues](https://github.com/invinciblebug/SmartSimulation/issues/new?template=bug_report.yml).

Every contribution, no matter the size, is greatly appreciated and helps keep this project active!

</details>

<details>
<summary><strong>Is this project open source?</strong></summary>

No, currently this project is not open source. However, in the future I may consider releasing it as open source to allow others to use, modify, and improve the code, and to enable contributions on GitHub.

</details>

---

<details>
<summary><strong>Support My Work</strong></summary>

If you'd like to support the development of my open-source projects and mods, you can donate using any of the following cryptocurrencies.

**Donations are completely optional but greatly appreciated.** All of my projects are provided free of charge, and your support helps cover development time, maintenance, bug fixes, compatibility updates, documentation, and future improvements.

### Bitcoin (BTC) – Taproot

**Address:**
```
bc1pww6tzrykn5swfqf3nd8aeyw3gcsr9lvw6ylw4jfj5k2h9chctsssuq2yw8
```

### Ethereum (ETH)

**Address:**
```
0xb2B549f6cBC6BaCc5A55FfB90Cb71Ce843A413EE
```

### BNB Smart Chain (BNB)

**Address:**
```
0xb2B549f6cBC6BaCc5A55FfB90Cb71Ce843A413EE
```

### USDT (BNB Smart Chain / BEP-20)

**Address:**
```
0xb2B549f6cBC6BaCc5A55FfB90Cb71Ce843A413EE
```

### Solana (SOL)

**Address:**
```
FKoAM9v4snn5QgW6cRhH89itGQiw2juPAYgs7ByJdP1
```

### USDC (Solana)

**Address:**
```
FKoAM9v4snn5QgW6cRhH89itGQiw2juPAYgs7ByJdP1
```

### TRON (TRX)

**Address:**
```
TSG8TNzPPQk5sVXvRgUV31NKhGZwggyQ6r
```

### Dogecoin (DOGE)

**Address:**
```
DBxmkbfwV7GYsGxY7rcWMkiXhQwqAZB3rn
```

---

**Important:** Please ensure you send each cryptocurrency using the correct blockchain network. Transactions sent using an unsupported network may be unrecoverable.

Thank you for your support! Every contribution helps me continue developing, maintaining, and improving free software, open-source projects, and mods for the community.

</details>

---

## License

Smart Simulation is proprietary software and the exclusive property of Invincible Bug.

**Permissions:**
- You may install and use this software for personal, non-commercial use with The Sims™ 4.
- You may modify this software for personal use only.
- Modified versions may be used solely for your personal use and may not be redistributed or shared.

**Restrictions:**
- You may NOT redistribute, re-upload, mirror, sell, sublicense, rent, or otherwise make this software available to others in any form. You may, however, share links only to the official download page, official website, or official GitHub repository.
- You may NOT distribute modified versions of this software.
- You may NOT use this software or any part of it for commercial purposes.
- You may NOT claim this software or any part of it as your own work.
- You may NOT remove, alter, or obscure any copyright notices, license information, or author attribution.
- You may NOT include this software in any mod pack, collection, installer, or archive without prior written permission from the author.
- You may NOT attempt to circumvent, remove, or bypass any licensing mechanism, copyright notices, or author attribution contained within this software, except where permitted by applicable law.
- You may NOT remove or modify this license agreement.

For the full license agreement, see the [LICENSE](LICENSE) file.

---

## Disclaimer

Smart Simulation is an independent community mod and is not affiliated with or endorsed by Electronic Arts or Maxis.

The Sims™ is a trademark of Electronic Arts Inc.
