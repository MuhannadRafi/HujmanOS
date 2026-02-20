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

### 🛠️ Quick Start: Build HujmanOS

Follow these steps to compile the ISO directly on your machine using **Docker**:

**1. Clone the environment**

```bash
git clone https://github.com/MuhannadRafi/HujmanOS.git
cd HujmanOS

```

**2. Launch the Build Container**

```bash
docker run --privileged -it -v $(pwd):/HujmanOS archlinux:base-devel /bin/bash

```

**3. Prepare & Compile (Inside Docker)**

```bash
# Initialize keys and install Archiso tool
pacman-key --init && pacman-key --populate archlinux
pacman -Sy archiso --noconfirm

# Start the "Cooking" process
mkarchiso -v -w /tmp/archiso-tmp -o /HujmanOS/out /HujmanOS/

```

---

### 💡 Why this works for HujmanOS?

* **Isolation:** Using Docker ensures that your Mac stays clean while building a Linux kernel.
* **Transparency:** Every step is visible, which is crucial for a security-focused OS dedicated to **XSS** and **SQL Injection** research.
* **Output:** Your final ISO will appear instantly in your `~/Desktop/HujmanOS/out` folder.

---


## 🤝 Contributing

Contributions are what make the open-source community an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. **Fork** the Project.
2. Create your **Feature Branch** (`git checkout -b feature/AmazingFeature`).
3. **Commit** your Changes (`git commit -m 'Add some AmazingFeature'`).
4. **Push** to the Branch (`git push origin feature/AmazingFeature`).
5. Open a **Pull Request**.

Developed by **Muhannad (MuhannadRafi)**. Let's build the future of security together.

## 📜 License
**This project is licensed under the MIT License.**
