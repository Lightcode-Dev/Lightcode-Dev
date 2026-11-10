<h1 align="center">Hi, I'm Nathan 👋</h1>

<p align="center">
  <em>Linux tinkerer. I like low-level things, tiling desktops, and building tools from scratch to learn how they work.</em>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Arch_Linux-1793D1?style=for-the-badge&logo=archlinux&logoColor=white" alt="Arch Linux" />
  <img src="https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white" alt="Rust" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=black" alt="C" />
  <img src="https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white" alt="Bash" />
  <img src="https://img.shields.io/badge/Lua-2C2D72?style=for-the-badge&logo=lua&logoColor=white" alt="Lua" />
  <img src="https://img.shields.io/badge/Proxmox-E57000?style=for-the-badge&logo=proxmox&logoColor=white" alt="Proxmox" />
</p>

---

## 🔭 What I'm working on

- 🦀 **[weyes](https://github.com/Lightcode-Dev/weyes)**: an xeyes clone written in Rust, with Wayland and X11 support on Linux
- 📊 **[sysmon](https://github.com/Lightcode-Dev/sysmon)**: a system monitor in strict C90 that reads straight from `/proc` and `/sys` (currently adding NVIDIA GPU support)
- 💬 **[matrix-tui](https://github.com/Lightcode-Dev/matrix-tui)**: an open-source terminal user interface client for Matrix written in Rust
- 🎨 **[kitty-theme-select](https://github.com/Lightcode-Dev/kitty-theme-select)**: an interactive terminal script for customizing Kitty
- 🖥️ A from-scratch **Hyprland** desktop, configured in Lua
- 📡 A custom **Arch Linux router**
- 📡 OpenWrt port for the [TP-Link Archer C5400X](https://www.tp-link.com/ca/home-networking/wifi-router/archer-c5400x/) (making some real progress recently!)
- 🐧 Building and tuning custom Linux kernels (e.g., compiling with `CONFIG_RUST=y` and `march=native` CPU optimizations)

## 🏠 Homelab Infra

I run my own self-hosted setup and treat it as a place to learn new skills and gain knowledge.

- **Virtualisation:** Multi-node Proxmox cluster hosting my VMs and LXC containers
- **Edge:** Caddy is the public-facing reverse proxy for my services and handles TLS. I also maintain the `caddy-crowdsec-git` package on the AUR for WAF/AppSec integration!
- **Back ends:** Apache, Anubis
- **Media:** Icecast and MPD for music streaming over the internet, Jellyfin for self-hosted movies and shows
- **Email:** Self-hosted Mailcow instance on my own domain with a score of 9.8/10 on [mail-tester.com](https://mail-tester.com/)
- **Networking:** A custom Arch Linux router is in the works, with VLANs planned



## 🧰 Tools & Infrastructure

| Category | Stack |
| :--- | :--- |
| 💻 **Languages** | C, Rust, Lua, Python, Bash, Go |
| 🛠️ **Environment** | Doom Emacs (Evil-mode), Kitty Terminal, Fish/Zsh, Starship |
| 🐧 **OS & Virt** | Arch Linux (Daily), Proxmox VE (Multi-node), Debian LXC, Alpine Linux LXC |
| 🎨 **Desktop Ricing** | Hyprland, KDE Plasma, Wallust, Eww |
| 🐳 **Self-Hosted Infra** | Caddy + CrowdSec, Mailcow, Matrix Synapse, Home Assistant |
| 📡 **Networking** | OpenWrt, NFS (systemd automounts), Icecast + MPD |

## 🌱 Currently learning

- 🪟 **Wayland Internals:** Diving deep into Wayland protocols and client-compositor IPC for my custom Hyprland environment
- 🔌 **Hardware Interfacing:** Tapping into UART serial consoles for bare-metal debugging and embedded firmware extraction
- 🔬 **Reverse Engineering:** Using Ghidra for hardware hacking and dissecting router firmware
- ❄️ **Declarative Systems:** Exploring NixOS, `nix-shell`, and the philosophy of reproducible system management
- 🤖 **Local AI Automation:** Integrating Ollama local LLMs with Home Assistant for entirely offline smart home voice control
- 📦 **Advanced Arch Packaging:** Mastering kernel configuration, `makepkg`, and building custom CPU-optimized native kernels

## 📫 Get in touch

- **GitHub:** [@Lightcode-Dev](https://github.com/Lightcode-Dev)
- **Mastodon:** [@lightcode177@mastodon.social](https://mastodon.social/@lightcode177)
- **Web:** [bigland.cc](https://bigland.cc) (Check out my subarctic landscape photography!)
- **Email:** dev@bigland.cc
- Open an issue on any of my repos, or start a discussion. Happy to chat.

---

<p align="center">
  <sub>Built with Doom Emacs and too much coffee. ☕</sub>
</p>
