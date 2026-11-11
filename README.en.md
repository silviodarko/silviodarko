<p align="right"><a href="./README.md">Português</a> · <strong>English</strong></p>

<p align="center">
  <img src="./assets/profile-header-glass-v2.svg" width="100%" alt="Sílvio Henrique | Founder & Systems Builder | SilvOS" />
</p>

<p align="center">
  <strong>Building a Linux desktop shaped by glass, privacy and local intelligence.</strong><br/>
  <sub>Independent builder • Linux engineering • Local-first AI • Automation</sub>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/s%C3%ADlvio-henrique-faria-b23a1b165/"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-Connect-184363?style=flat-square&logo=linkedin&logoColor=white"/></a>
  <a href="https://github.com/silviodarko?tab=repositories"><img alt="Projects" src="https://img.shields.io/badge/GitHub-Projects-226080?style=flat-square&logo=github&logoColor=white"/></a>
  <a href="https://github.com/silviodarko?tab=achievements"><img alt="GitHub Achievements" src="https://img.shields.io/badge/GitHub-Achievements-307B9B?style=flat-square&logo=github&logoColor=white"/></a>
</p>

---

### Vision

I'm **Sílvio Henrique**, an independent developer and creator of **SilvOS**. My work connects Linux systems, automation, user experience, and locally executed artificial intelligence.

I aim to turn technical experiments into tools that are **well designed, reproducible, private by default, and maintainable**.

> **Build with purpose. Automate responsibly. Keep people in control.**

### Flagship project · SilvOS

**SilvOS** is an independent Linux distribution **in development**, built on an Arch Linux foundation with a customized desktop experience, productivity tools, and a local AI layer.

| Focus area | Technology and direction |
| :--- | :--- |
| **Desktop** | Arch Linux · Wayland · Niri / Lniri · Noctalia · Kitty |
| **User experience** | Liquid Glass · transparency & blur · GTK / CSS · Qt / QML interfaces |
| **Jarvis, local AI** | Qwen3 · llama.cpp · Whisper · Piper · Kokoro ONNX experiments |
| **Integration & automation** | Python · Bash · JavaScript · systemd user services · GitHub API |
| **Secure bridge** | authorized actions · input validation · SHA-256 · backups & rollback |
| **Distribution engineering** | PKGBUILD · pacman · GitHub Actions · isolated testing · lab-only GPG signing |

**What we're building**

- **A distinct Linux desktop experience**, integrating Wayland composition, visual customization, and productivity applications.
- **An actually useful local assistant** designed for conversation, speech recognition, explicitly authorized tasks, and privacy.
- **A desktop bridge** with tightly scoped operations, execution receipts, and recovery mechanisms.
- **An installable and maintainable distro**, with a private Alpha 0.3 installable ISO validated in QEMU UEFI and a signed package update system under development.

**Project status:** actively developed, *pre-release*. The desktop is used on my personal machine, but **SilvOS does not yet have a public ISO or a stable release**. The development repository is private at this stage. Some integrations and GPU acceleration are still under evaluation.

<p align="center">
  <img src="./assets/silvos-alpha03-glass.svg" width="100%" alt="SilvOS Alpha 0.3: private installable ISO verified in QEMU UEFI, Niri, Noctalia and unchanged sentinel disk" />
</p>

**Alpha 0.3 milestone (November 2026):** the **private installable ISO** completed installation on a disposable qcow2 disk, booted from its installed disk in QEMU UEFI **without the ISO**, and passed Niri/Wayland, Noctalia, network, `silvos-cli` and secondary-disk SHA-256 checks. This is **not physical-hardware certification, a stable release or a public download**. See the [public roadmap](./SILVOS_ROADMAP.md).

**Official SilvOS website:** [silviodarko.github.io](https://silviodarko.github.io/) · Liquid Glass, Jarvis and public roadmap.

**Public roadmap:** [SilvOS development milestones](./SILVOS_ROADMAP.md) · high-level plans, no private implementation details.

### From Alpha 0.3 to `silvos update`

| Milestone | Status |
| :--- | :--- |
| Installable ISO and ISO-free UEFI boot | **Verified in QEMU** (private lab) |
| Niri, Noctalia, network and `silvos-cli` | **Verified in the installed VM** |
| First `silvos-cli` package and temporary GPG signatures | **Tested in isolated CI** |
| Customized `silvos-lniri` build | **Under validation**, `libspa` linking unresolved |
| Trusted `silvos-testing` release repository and key | **Not available yet** |
| N → N+1 VM upgrade and recovery | **Next milestone** |
| Real `silvos update` on the workstation | **Blocked pending validation** |

The current `silvos update --check` prototype only checks the local Pacman database. The future updater is intended to use fully signed packages and complete upgrades through `pacman -Syu`, preserving Glass customizations. No production updater has been released.

**Official page:** [SilvOS development updates](https://silviodarko.github.io/#atualizacoes).

### Developer Program &amp; GitHub API

My **GitHub Developer Program enrollment was confirmed in November 2026**; I'm a participant, exploring integrations built on the GitHub API. SilvOS Bridge uses scoped, authenticated operations, execution receipts and recovery checks. This is an individual developer-program participation, **not a GitHub partnership, certification or endorsement**.

### Technology stack

**Systems & languages**

![Arch Linux](https://img.shields.io/badge/Arch_Linux-438CAB?style=flat-square&logo=archlinux&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-184363?style=flat-square&logo=linux&logoColor=white)
![Python](https://img.shields.io/badge/Python-226080?style=flat-square&logo=python&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-307B9B?style=flat-square&logo=gnubash&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-438CAB?style=flat-square&logo=rust&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-184363?style=flat-square&logo=javascript&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-226080?style=flat-square&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS-307B9B?style=flat-square&logo=css&logoColor=white)

**Desktop, tooling & delivery**

![Qt](https://img.shields.io/badge/Qt-438CAB?style=flat-square&logo=qt&logoColor=white)
![Git](https://img.shields.io/badge/Git-184363?style=flat-square&logo=git&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-226080?style=flat-square&logo=githubactions&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-307B9B?style=flat-square&logo=sqlite&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-438CAB?style=flat-square&logo=mysql&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-184363?style=flat-square&logo=flask&logoColor=white)

**AI & inference:** Qwen3 · llama.cpp · Whisper ASR · Piper TTS · Kokoro ONNX (experimental) · Vulkan / RADV (performance evaluation).

<sub>This stack includes technologies used, integrated, or studied across projects; maturity varies by component.</sub>

### Selected public work

| Project | Focus |
| :--- | :--- |
| [RX580 Linux Stability Fix](https://github.com/silviodarko/rx580-linux-stability-fix) | Experimental Linux AMD GPU power-management lab and documentation. |
| [Scroll Lock wlroots Fix](https://github.com/silviodarko/scrolllock-wlroots-fix) | Experimental Python/libevdev keyboard LED workaround with systemd sample. |
| [Flask API](https://github.com/silviodarko/API.Flask.COLAB) | Python/Flask HTTP API experiment with JSON data. |

**[Explore my curated engineering portfolio](./PORTFOLIO.en.md)** · Selected projects, technical context and maturity.

### GitHub activity

GitHub-issued achievements, when eligible, are shown by GitHub itself. [View achievements and profile badges](https://github.com/silviodarko?tab=achievements). Developer Program membership is mentioned here as a program participation, not as a fabricated GitHub badge.

---

<p align="center">
  <strong>Engineering independence, one commit at a time.</strong><br/>
  <sub>SilvOS • Built in Brazil 🇧🇷 • Work in progress, intentionally.</sub>
</p>
