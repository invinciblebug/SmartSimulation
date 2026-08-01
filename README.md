# Smart Simulation

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

> [!NOTE]
> **Report Issues**
> If you have any issues, please report them on GitHub Issues:
> https://github.com/invinciblebug/SmartSimulation/issues/new?template=bug_report.yml

---

## Features

* **Improved Simulation Stability** - Reduces simulation slowdowns and keeps gameplay feeling responsive
* **Stall Recovery** - Automatically detects and recovers from stalled interactions
* **Smoother Gameplay** - Designed for more reliable and consistent simulation performance
* **Lightweight** - Focused on performance without unnecessary overhead
* **Automatic Updates** - Notifies you when a new version is available
* **Troubleshooting Logs** - Creates detailed logs for diagnosing issues
* **Offline-Friendly** - Works perfectly without internet connection
* **Cross-Platform** - Built for Windows, macOS, and Linux versions of The Sims 4

---

## Issues Resolved

Smart Simulation addresses common gameplay issues:

* **Sims Standing Still** - Prevents Sims from freezing and refusing to perform actions
* **Eating/Cleaning/Sleeping Problems** - Fixes Sims who refuse to complete basic needs interactions
* **Simulation Slowdowns** - Reduces lag and keeps the simulation running smoothly
* **Stalled Interactions** - Automatically recovers from interactions that get stuck
* **Head Bobbing** - Helps prevent the "head bob" freeze effect
* **Timeline Freezes** - Detects and recovers from timeline stalls

---

## Performance Benefits

* **Faster Simulation** - Improves overall simulation responsiveness
* **Reduced Lag** - Minimizes slowdowns during busy gameplay moments
* **Smoother Transitions** - Better handling of interaction transitions
* **Consistent Performance** - More reliable simulation across different save types
* **Safe Optimizations** - All improvements are designed to be safe and reversible

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

**Note:** Smart Simulation uses Core Library's Python API for tuning injection - no custom .package files are needed. All tuning is handled through Python code using Core Library's TuningInjector.

## Dependencies

Smart Simulation requires **Core Library** by Lot 51.

- **Download**: https://lot51.cc/mods/core-library
- **Required**: `lot51_core.ts4script`
- **Version**: Latest recommended

Core Library provides:
- Event system for zone load/unload hooks
- Logger for mod logging
- Config for persistent user settings
- TuningInjector for XML tuning injection (Python API)

> Script mods (.ts4script files) must be placed:
> - Directly in the Mods folder, OR
> - Only one subfolder deep inside Mods folder
>
> Do NOT place script mods two or more subfolders deep, or they will not load. This rule applies to Smart Simulation and Core Library.

The release bundle includes `lot51_core.ts4script` which must be installed alongside Smart Simulation.

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
.installed (marker file for first-time installation)
```

Log files use daily date-stamped filenames (DD-MM-YYYY format). Logs older than 30 days are automatically deleted. On-demand file I/O ensures no file handles are kept open.

---

## Compatibility

> [!CAUTION]
> Always check the tested version before installing. New game updates may require mod updates.

Smart Simulation is designed to work with the latest version of The Sims 4.

**Tested Version:** `1.126.73.1030`

If a game update changes behavior, a new release will be published as soon as possible.

---

## Reporting Issues

If you run into a problem, please:

1. **Create an issue on GitHub** at:
   **https://github.com/invinciblebug/SmartSimulation/issues**

2. Include the following information:
   * Smart Simulation version
   * The Sims 4 version
   * A clear description of the issue
   * Relevant log files if available (from `Documents/Electronic Arts/The Sims 4/[INVINCIBLEBUG]/`)

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

**Does this mod conflict with other mods?**

No, Smart Simulation is designed to be compatible with most mods. However, some mods like MCCC (MC Command Center) may have conflicts if you manually change certain settings. I've made sure it won't conflict unless there are specific updates or changes to those mods.

**Does this mod get regular updates?**

Yes! Smart Simulation receives regular updates with testing and improvements. I actively maintain and test the mod to ensure compatibility with the latest Sims 4 versions and to address any issues that arise.

**I have an issue, what should I do?**

Please report any issues on GitHub Issues. You'll need to sign in to GitHub to create an issue. I'll resolve issues as fast as possible. When reporting, please include:
- Smart Simulation version
- The Sims 4 version
- A clear description of the issue
- Relevant log files if available

**Is this mod paid?**

No, Smart Simulation is completely free to use. There are no costs or fees associated with downloading or using this mod.

**Does this mod contain malware or viruses?**

No, Smart Simulation does not contain any malware or viruses. The mod is safe to use and only contains the code necessary for simulation optimization.

**Will this mod slow down my game?**

No, Smart Simulation is designed to be lightweight and focused on performance. It should actually improve your game's performance by reducing simulation slowdowns and stalls.

**Does this mod make my game load faster?**

No, this mod does not significantly affect game loading times. It may have a very small effect depending on your PC or laptop specifications, but its primary purpose is to make gameplay smoother and prevent the simulation from getting stuck, not to make your game load faster.

**Does this mod make my game super fast?**

No, Smart Simulation does not make your game extraordinarily fast. It focuses on making gameplay smooth and preventing Sims from getting stuck or the timeline from freezing. The mod optimizes simulation responsiveness rather than increasing overall game speed.

**What platforms does this mod support?**

Smart Simulation supports all major platforms:
- **Windows** - Full support
- **macOS** - Full support
- **Linux** - Full support (including Steam/Proton, Lutris, and EA App versions)

**Does this mod work with the free version of The Sims 4? Do I need expansion packs?**

Yes, Smart Simulation works with any version of The Sims 4, including the free version. You do not need any expansion packs or DLC for this mod to function. The mod is designed to work with the base game and all expansion packs, game packs, stuff packs, and kits. It will work regardless of which version or combination of content you have installed.

**Can I use this mod with other simulation optimization mods?**

While Smart Simulation is designed to be compatible, using multiple simulation optimization mods together is generally not recommended as they may interfere with each other. It's best to test one at a time.

**How do I know if the mod is working?**

The mod creates log files in `Documents/Electronic Arts/The Sims 4/[INVINCIBLEBUG]/`. You can check these logs to see if the mod is active. You can also use the in-game cheat command `ss.status` to see the mod's current status.

**Can I disable the mod temporarily?**

Yes, you can disable the mod by removing the `.ts4script` and `.package` files from your Mods folder, or by renaming them with a `.disabled` extension.

**Does this mod work with all expansion packs?**

Yes, Smart Simulation is designed to work with all Sims 4 expansion packs, game packs, and stuff packs, including the latest releases.

**Will this mod affect my save files?**

No, Smart Simulation does not modify your save files. It only affects the simulation runtime and does not make permanent changes to your game data.

**Where is the source code?**

This project is currently proprietary, so the source code is not released publicly. The mod is provided as compiled `.ts4script` and `.package` files for use in The Sims 4.

**Is this project open source?**

No, currently this project is not open source. However, in the future I may consider releasing it as open source to allow others to use, modify, and improve the code, and to enable contributions on GitHub.

---

## Support My Work

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
