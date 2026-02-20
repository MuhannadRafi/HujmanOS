# 🛡️ HujmanOS (V1.0) 

**HujmanOS** is a professional, Arch-based Linux distribution custom-built for Cybersecurity Specialists, Penetration Testers, and Linux Enthusiasts. Developed by **Muhannad (Munx64)**, it focuses on modern workflows, security analysis, and web vulnerability research.

---

## 🚀 Core Philosophy
Designed in Jeddah, Saudi Arabia, HujmanOS bridges the gap between high-performance daily driving and hardcore security auditing. It features a highly customized **Hyprland (Wayland)** environment for maximum productivity.

### 🛠️ Specialized Focus:
- **Web Security:** Pre-configured tools for **XSS** and **SQL Injection** analysis.
- **Pentesting Suite:** Includes Metasploit, Burp Suite, Nmap, and Ghidra.
- **Modern UI:** Powered by Wayland, Waybar, and Kitty terminal.
- **Compatibility:** Built-in support for Windows applications via Wine and Winetricks.

---

## 📸 Screenshots
> *[Add your screenshot here: `assets/desktop_preview.png`]*
> *Experience the fluid motion of Hyprland with HujmanOS custom dotfiles.*

---

## 🧰 The Pentester's Toolbox
HujmanOS comes out of the box with:
* **Information Gathering:** Recon-ng, Sublist3r, Maltego.
* **Vulnerability Analysis:** Nikto, Skipfish, Nuclei.
* **Exploitation:** Metasploit Framework, ExploitDB.
* **Forensics & Reversing:** Autopsy, Ghidra, OllyDbg.
* **Password Cracking:** John the Ripper, Hashcat.

---

## 🏗️ Build & Installation

### Build from Source (macOS/Linux)
HujmanOS is built using `archiso` within a Docker container to ensure environment consistency.

```bash

# Clone the repository
git clone [https://github.com/MuhannadRafi/HujmanOS.git](https://github.com/MuhannadRafi/HujmanOS.git)
cd HujmanOS

# Build the ISO (Requires Docker)
docker run --privileged -it -v $(pwd):/HujmanOS archlinux:base-devel /bin/bash
# Inside container:
mkarchiso -v -w /tmp/archiso-tmp -o /HujmanOS/out /HujmanOS/

```
