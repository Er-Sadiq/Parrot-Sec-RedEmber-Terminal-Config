# Parrot Security RedEmber Bash Configuration

## Overview
This repository contains a custom Bash configuration aimed at providing a more interactive and colorful terminal experience, with a focus on security tasks. It includes aliases and functions designed to improve your terminal workflow, making it more efficient and fun.

---

## Dependencies

Before using this configuration, ensure that you have the following installed:

- `bash` (usually pre-installed on most systems)
- `nmap` (for port scanning)
- `macchanger` (for changing MAC addresses)
- `tar`, `unzip`, `7z`, `bunzip2` (for extracting compressed files)
- `git` (for version control)
- `starship` (for a modern, customizable prompt; optional)
- `emacs` (for text editing; optional)
- `rust` (for yazi a filemanager for your terminal)
- `emacs` (an advance file manager for your terminal)
- `FireCode Nerd` (for the terminal)
---

## Aliases and Functions

Here’s a list of the key aliases and functions included in the configuration:

### File and Directory Listing Aliases
- `ls` – List files with a colorful prompt.
- `dir` – Display directories in a visually distinctive way.
- `vdir` – View directory content with color.

### File Operations Aliases
- `ll` – Detailed file listing with human-readable file sizes.
- `la` – List all files, including hidden ones.
- `l` – Compact directory view.
- `rmf` – Force delete files or directories recursively (`rm -rf`).

### System Information Aliases
- `sys_upgrade` – Update and upgrade the system with a humorous message.
- `please` – Trigger `sudo` with a custom message, adding a playful touch.
- `..` – Move up one directory.
- `...` – Move up two directories.
- `....` – Move up three directories.

### Git Aliases
- `gs` – Check the status of the git repository.
- `ga` – Add files to the staging area.
- `gc` – Commit changes with a message.
- `gp` – Push changes to the remote repository.
- `gpull` – Pull the latest changes.
- `gco` – Checkout a specific branch.

### Networking Aliases
- `macchanger <interface>` – Change the MAC address of the specified interface.
- `check_ports <IP>` – Scan open ports on a specified IP address or domain using `nmap`.

### System Tools and Fun
- `extract` – Extract a variety of compressed file formats (e.g., tar, zip, rar).
- `test` – Test by listing files.
- `cls` – Clear the terminal with a custom message.
- `hack_quotes` – Display a random hacking quote with a typing effect.

### Command Not Found Handler
If a command isn't found, a colorful, humorous message will be displayed with a typing effect.

---

## Setup Instructions

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/parrot-security-mode-bash-config.git
   cd parrot-security-mode-bash-config
   ```

2. Copy the `.bashrc` and `.bash_aliases` files to your home directory:
   ```bash
   cp .bashrc ~/.bashrc
   cp .bash_aliases ~/.bash_aliases
   ```

3. Move the `StarShip.tmol` file into the `./configuration` directory.

4. Reload the `.bashrc` to apply the changes:
   ```bash
   source ~/.bashrc
   ```

---
## Demo
 ![p2](https://github.com/user-attachments/assets/3b4f007a-d123-4572-9645-97a6a3b738a4)
 ![p3](https://github.com/user-attachments/assets/c8ad42e9-aefa-4149-a2a6-f2fa9db578f9)
 ![p1](https://github.com/user-attachments/assets/f51a7f32-5ee3-4ff8-943d-59c46e7d12d8)
 ![p5](https://github.com/user-attachments/assets/6ef4a755-2f39-4f4c-9b01-b0f37efb9e03)


---
## Author & License 

This project is not licensed under the MIT License.
Copyright (c) [2024] [Sadiq Ahmed Killedar / @Er-Sadiq](https://github.com/Er-Sadiq). All rights reserved.

This software is proprietary and cannot be modified, redistributed, or used without express permission from the author.

---

☕ **Buy Me a Coffee**

If you enjoy this project and want to support my work, feel free to buy me a coffee – it'll help fuel my late-night coding sessions! ☕ Your support is much appreciated and keeps the terminal magic flowing. Thank you! 🙏

