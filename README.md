# // JITTER THEMES (`Jitter-Shadow`)

Matte-black, deep graphite, and crimson desktop and window themes built for Linux XFCE environments and portable cyberdecks (ClockworkPi uConsole & Hackberry Pi CM5).

> **Note:** Icons and HUD overlays are maintained separately—this repository covers desktop, GTK, window manager, and splash/wallpaper themes only.

### 🎨 Color Palette
* **Obsidian Void:** `#0D090A` (Primary dark base)
* **Deep Graphite:** `#181012` (Panels, cards & surface layers)
* **Crimson Border:** `#3A151B` (Dividers & window edges)
* **Signal Red:** `#E11D2E` (Primary active accents)
* **Alert Red:** `#FF2E43` (Highlights & active indicators)

### 🧩 Included Themes
* **`Jitter-Shadow` GTK2 / GTK3 & XFWM4:** High-contrast dark-and-crimson window borders, menus, and panel styling with targeted GTK3 CSS overrides for clean panel tasklists.
* **Plymouth Boot Splash:** Crimson waveform boot animation sequence for clean startup transitions.
* **Live Wallpaper Theme (`jitter-wall`):** Looping crimson/dark visual theme driven by `mpv` and `xwinwrap` with automatic fullscreen pause and hotkey toggle support.

### ⚙️ Installation (`install.sh` + `.py` Wrapper)
Each theme ships with a standalone `install.sh` script that handles file placement, permissions, and theme activation, wrapped inside a `.py` entrypoint for streamlined execution, argument handling, and status output.

* **Run a theme's Python wrapper:**
  ```bash
  python3 install_jitter_shadow.py
