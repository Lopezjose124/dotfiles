# Arch Dotfiles

My personal Arch Linux dotfiles, built for a clean, keyboard-driven workflow with Wayland (Hyprland), a custom Neovim setup, and a slick Waybar config.

---

## 🖥️ Features

* **Hyprland**: Dynamic tiling WM with multi-monitor setup

  * Ultrawide monitor (`DP-2`) + 7" touchscreen (`HDMI-A-2`)
  * Firefox kiosk music hub on secondary screen
  * Workspace-specific app placement

* **Waybar**: Clean status bar themed with Catppuccin-like colors

  * Custom modules: Bluetooth, Notifications, Power Menu
  * Single-bar layout pinned to `DP-2`

* **Neovim**: Minimal and modern

  * LSP, treesitter, completion, and custom keymaps

* **Wofi**: App launcher and power menu

* **Swaync**: Notification daemon

* **Ghostty**: Terminal emulator

* **Unclutter**, **Hypridle**, and other polish utilities

---

## 📁 Folder Structure

```
~/.dotfiles/
├── hypr/             # Hyprland config
├── waybar/           # Waybar config + modules + CSS
├── nvim/             # Neovim Lua config
├── wofi/             # Launcher + powermenu
├── scripts/          # Custom scripts
└── README.md         # You're here
```

---

## 🚀 Setup Instructions

```bash
git clone https://github.com/lopez.jose124/dotfiles ~/.dotfiles
cd ~/.dotfiles

```

Or manually symlink:

```bash
ln -s ~/.dotfiles/hypr ~/.config/hypr
ln -s ~/.dotfiles/waybar ~/.config/waybar
ln -s ~/.dotfiles/nvim ~/.config/nvim
```

---

## 🔧 Dependencies

* [Hyprland](https://github.com/hyprwm/Hyprland)
* [Waybar](https://github.com/Alexays/Waybar)
* [Neovim](https://neovim.io)
* [Ghostty](https://github.com/mitchellh/ghostty)
* [Wofi](https://hg.sr.ht/~scoopta/wofi)
* [Swaync](https://github.com/ErikReider/SwayNotificationCenter)
* [playerctl](https://github.com/altdesktop/playerctl)
* [wl-clipboard](https://github.com/bugaevc/wl-clipboard)
* [brightnessctl](https://github.com/Hummer12007/brightnessctl)

---

## 🧼 Credits

* [Catppuccin](https://github.com/catppuccin) for color inspiration
* [Arch Wiki](https://wiki.archlinux.org/) for literally everything

---

## License

MIT
