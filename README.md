# LAppManager

Minimal and modern application manager for Debian-based systems built with PyQt6 and Python.  
The application provides a simple graphical interface for installing applications, managing local packages, and handling updates from multiple sources.
I bring .py to the whole releases to make it open for modifying for everyone

> [!NOTE]
>
> ### Beta testing
>
> LAppManager is currently in development and view of app now is not final look of it and soon it is going to be updated

## Features

- Built with Python and PyQt6
- Clean tab-based interface
- Integration with APT and Flathub
- Local package installation

---

## Overview

The application consists of 3 main tabs:

### 1. Installation

Application discovery and installation from official repositories.

Features:

- Popular applications list
- Search
- Application previews, IDs and descriptions
- Supported repositories:
  - APT
  - Flathub

---

### 2. Local Files

Tool for installing local packages and archives using drag and drop.

Supported formats:

- `.deb`
- `.AppImage`
- `.tar.gz`
- `.tar.xz`
- `.tar.zip`

Features:

- Drag and drop
- Guided installation workflow

---

### 3. Updates

Centralized update management.

Features:

- Available updates list
- No automatic updates
- Simple Changelog
- Supported repositories:
  - APT
  - Flathub

---

## Tech Stack

- Python
- PyQt6

---

## Requirements

- Debian or Debian-based distribution
- Python 3.10+
- PyQt6
- Flatpak

> [!IMPORTANT]
> If you dont have flathub installed app will crash or will not work correctly with flatpak, you can install it with
> ```bash
> sudo apt install flatpak
> flatpak remote-add --if-not-exists flathub https://dl.flathub.org/repo/flathub.flatpakrepo

---

## Installation

Download .bin or .deb from GitHub releases and install it

OR

Clone the repository:

```bash
git clone https://github.com/pechenkactrld/LAppManager.git
cd LAppManager
```
and install it
