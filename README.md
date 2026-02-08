# LappManager

Minimal and modern application manager for Debian-based systems built with PyQt6 and Python.  
The application provides a simple graphical interface for installing applications, managing local packages, and handling updates from multiple sources.

## Features

- Built with Python and PyQt6
- Clean tab-based interface
- Integration with APT and Flathub
- Local package installation assistant
- Update management with changelogs

---

## Overview

The application consists of three main tabs:

### 1. Installation

Application discovery and installation from official repositories.

Features:

- Popular applications list
- Application search
- Application previews and descriptions
- Application ID display
- One-click installation
- Supported repositories:
  - APT
  - Flathub

---

### 2. Local Files

Helper tool for installing local packages and archives using drag and drop.

Supported formats:

- `.deb`
- `.AppImage`
- `.tar.gz`
- `.tar.xz`
- `.tar.zip`

Features:

- Drag and drop interface
- Automatic package detection
- Guided installation workflow

---

### 3. Updates

Centralized update management from multiple sources.

Features:

- Available updates list
- Changelog viewing
- Batch update installation
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
- Flatpak (for Flathub support)
- APT package manager

---

## Installation

Clone the repository:

```bash
git clone https://github.com/your-username/your-repo.git
cd your-repo
