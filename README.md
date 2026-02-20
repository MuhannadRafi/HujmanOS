# <img src="airootfs/etc/calamares/branding/hujmanos/logo.png" width="50" align="center"> HujmanOS (V1.0)

**HujmanOS** is a high-performance, Arch-based Linux distribution tailored for **Cybersecurity Professionals** and **Penetration Testers**. It features a pre-configured **Hyprland** environment designed for efficiency and speed.

🌐 **Official Website:** [https://HujmanOS.com](https://HujmanOS.com)

---

## 🚀 Core Philosophy
Designed in Jeddah, Saudi Arabia, HujmanOS is the intersection of Global Political Economy and Advanced Cybersecurity. It provides a seamless experience for auditing digital infrastructures.

### 🛠️ Key Features
- **UI/UX:** Custom **Hyprland** (Wayland) compositor with professional dotfiles.
- **Security Focus:** Advanced tools for **XSS** and **SQL Injection** vulnerability research.
- **Versatility:** Integrated **Wine** and **Winetricks** for Windows tool compatibility.
- **Ready for Daily Use:** Pre-installed with **LibreOffice**, **GIMP**, and **VLC**.

---

## 🧰 The Pentester's Toolbox
Armed with official Arch and **BlackArch** repositories:

| Category | Tools |
| :--- | :--- |
| **Web Analysis** | **Burp Suite**, SQLMap, Nikto, Wfuzz |
| **Reconnaissance** | Nmap, Recon-Ng, Sublist3r, Gobuster |
| **Exploitation** | Metasploit-Framework, Exploit-DB |
| **Reverse Eng.** | **Ghidra**, OllyDbg, Autopsy |
| **Cryptography** | Hashcat, John the Ripper, Hydra |

---

## 💿 Build from Source
Build HujmanOS using Docker on macOS/Linux:

```bash
# Clone the repository
git clone [https://github.com/MuhannadRafi/HujmanOS.git](https://github.com/MuhannadRafi/HujmanOS.git)
cd HujmanOS

# Build using Docker
docker run --privileged -it -v $(pwd):/HujmanOS archlinux:base-devel /bin/bash

# Inside the container:
# Update keys and install archiso
pacman-key --init && pacman-key --populate archlinux
pacman -Sy archiso --noconfirm

# Run the build
mkarchiso -v -w /tmp/archiso-tmp -o /HujmanOS/out /HujmanOS/



## 🤝 Contributing

Contributions are what make the open-source community an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. **Fork** the Project.
2. Create your **Feature Branch** (`git checkout -b feature/AmazingFeature`).
3. **Commit** your Changes (`git commit -m 'Add some AmazingFeature'`).
4. **Push** to the Branch (`git push origin feature/AmazingFeature`).
5. Open a **Pull Request**.

Developed by **Muhannad (Munx64)**. Let's build the future of security together.
