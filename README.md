# AccurateMacro

Windows automation tool: autoclicker, AHK‑style recorder, macro editor, window management. Single EXE, no install.

<img width="712" height="520" alt="image (1)" src="https://github.com/user-attachments/assets/c8659f1a-73ef-4ba4-bab8-883ce8544f5d" />


---

## Features

- **Autoclicker** – left/right/middle button, single/double click, adjustable speed with random offset, auto‑stop timer, click at current cursor or a picked screen position.
- **AHK Recorder** – record mouse and keyboard actions (clicks, moves, scrolls, keys). Stop with Esc or timer. Playback with loop and loop delay. Save/load recordings.
- **Macro Editor** – build sequences of actions: keys, clicks, mouse down/up, absolute/relative movement, scroll, delays, text typing, loops (repeat N times), holds (keep keys/buttons pressed for a duration). Modes: Spam (run once), Toggle (start/stop), Hold (repeat while hotkey is held). Cooldown, repeat delay, window title binding.
- **Window Control** – for the active window: remove/restore borders, fullscreen, pin (topmost). Assign hotkeys.
- **Global Hotkeys** – for autoclicker, record, play, emergency stop, window actions, and each macro. Duplicate detection.
- **Emergency Stop** – stops everything and restores all windows.
- **Import/Export** – macros (`.mmmacro`) and AHK recordings (`.mmahk`). Coordinates auto‑scale on import.
- **Other** – English/Russian interface, run on startup, update check, reset settings, delete all data.

---

## Installation

Download `AccurateMacro.exe` from the [Releases](https://github.com/SigmaPokoyo67Okak/AccurateMacro/releases) page. Run it – no extra steps. For input to work in games or elevated apps, run as administrator.

---

## Quick Start

Hotkeys are not assigned by default – set them in the **Hotkeys** tab.

- **Autoclicker** – configure settings and press Start. Stop with Stop button or hotkey.
- **AHK Recorder** – press Record, perform actions, press Esc to stop. Use Play to replay. Save recordings via the list.
- **Macros** – create/edit macros in the **Macros** tab. Double‑click to open editor. Add actions with the `+` button or right‑click menu. For `move`, use `x,y` (pixels) or `x,y,R` (screen fractions). For `move_rel`, use `dx,dy,speed`. `loop` and `hold` affect the actions that follow – place them before the block.

Settings are saved automatically in `Documents\AccurateMacro\cfg`. Logs go to `Documents\AccurateMacro\log`.

---

## File Formats

- `.mmmacro` – macro files (no manual editing needed).
- `.mmahk` – AHK recording files (coordinates auto‑adjust on import).

---

## Requirements

- Windows 10 or 11 (tested on 10).  
- Administrator rights recommended for reliable input.

---

## Support the Author

If you find this useful, you can send a donation via USDT (TRC20):  
`TT85oTC6fT3eu81jt37jEczAbqMjk9aeD7`

---

**Author:** SigmaPokoyo67Okak  
**GitHub:** [SigmaPokoyo67Okak/AccurateMacro](https://github.com/SigmaPokoyo67Okak/AccurateMacro)
