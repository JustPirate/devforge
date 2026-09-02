# DevForge — Hyprland Linux Environment

A personal Linux desktop environment built around Hyprland, with custom configuration, scripts, shortcuts, power controls, and workflow-focused tooling.

## Overview

DevForge is a reproducible collection of Linux desktop configuration designed to make a Hyprland workstation fast, focused, and practical for software development.

The repository combines window-manager configuration with shell customization, status-bar workflows, application launching, notifications, screenshots, and power/performance controls.

## Components

| Component | Role |
|---|---|
| Hyprland | Wayland window manager |
| Fish | Interactive shell |
| Kitty | Terminal |
| Waybar | Status bar |
| Fuzzel | Application launcher |
| wleave | Logout menu |
| Dunst | Notifications |
| Hypridle | Idle management |
| swww | Wallpaper management |
| Thunar | File manager |

## Features

- Full and compact Waybar modes
- Custom Fish shell prompt and startup messages
- Grayscale shader toggle
- Power/performance mode for reducing animations and blur
- Custom keyboard-driven application workflow
- Screenshot shortcuts for full-screen and region capture
- NVIDIA-oriented Hyprland configuration

## Keybindings

| Keybind | Action |
|---|---|
| `SUPER + T` | Open Kitty |
| `SUPER + Space` | Open Fuzzel |
| `SUPER + ESC` | Open logout menu |
| `SUPER + Q` | Close active window |
| `SUPER + W` | Open browser |
| `SUPER + C` | Open VS Code |
| `SUPER + E` | Open Thunar |
| `SUPER + F` | Toggle floating |
| `PrintScreen` | Full screenshot |
| `Shift + PrintScreen` | Region screenshot |

## Installation

Clone the repository:

```bash
git clone https://github.com/vijaygovindBiju/devforge.git ~/dotfiles
```

Review the configuration before linking it into `~/.config`, then create the required symlinks for the components you want to use:

```bash
ln -s ~/dotfiles/hypr ~/.config/hypr
ln -s ~/dotfiles/waybar ~/.config/waybar
ln -s ~/dotfiles/fish ~/.config/fish
```

Install the required fonts from `hypr/Fonts/` and ensure the applications listed above are installed on your system.

> Configuration paths and application names are intentionally documented here rather than using an automated installer, so the setup can be adapted safely to another machine.

## Screenshots

The repository includes screenshots showing the desktop, power menu, shell, and Waybar configuration.

## Engineering Notes

This project is primarily configuration and shell scripting rather than a traditional application. Its value is in automation, reproducible workstation setup, Linux tooling, and maintaining a coherent developer workflow.

## License

Personal configuration project. Use and adapt the configuration at your own discretion.
