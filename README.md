# LappManager

Minimal and modern application manager for Debian-based systems built with PyQt6 and Python.  
The application provides a simple graphical interface for installing applications, managing local packages, and handling updates from multiple sources.

> [!IMPORTANT]
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

The application consists of three main tabs:

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
- Automatic package detection
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
- APT package manager

> [!NOTE]
> If you dont have flathub installed app will crash or will not work correctly with flatpak, you can install it with
> ```bash
> sudo apt install flatpak

---

## Installation

Clone the repository:

```bash
git clone https://github.com/your-username/your-repo.git
cd your-repo
