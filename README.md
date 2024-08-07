# GNOME Tools Installation Script
This script installs GNOME Tweaks, GNOME Shell Extensions, and GNOME Shell Extension Manager. 
It automatically detects your package manager (apt, dnf, or pacman) and installs the necessary packages.

## Usage
### Clone the Repository
```bash
git clone https://github.com/querzion/bash.gnome-startup.git
cd bash.gnome-startup
```

### Make the Script Executable
```bash
chmod +x bash.gnome-startup.sh
```

### Run the Script
```bash
./bash.gnome-startup.sh
```

## What the Script Does
- Detects the package manager (apt, dnf, or pacman).
- Updates the package list.
### Installs:
  - GNOME Tweaks
  - GNOME Shell Extensions
  - GNOME Shell Extension Manager
  - Visual Studio Code
  - Latest .NET SDK
  - Latest .NET Runtime
  - UPower-Battery Extension
  - Discord
  - KeePassXC
  - Brave Browser

## Compatibility
### The script is compatible with:

- Debian-based systems (e.g., Ubuntu) using apt.
- Fedora-based systems using dnf.
- Arch-based systems using pacman.
