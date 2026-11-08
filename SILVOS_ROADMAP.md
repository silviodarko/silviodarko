# SilvOS | Public Roadmap

> **Project phase:** active development / pre-release  
> **Public availability:** not yet released  
> **Last reviewed:** November 2026

SilvOS is an independently developed Linux desktop distribution project, built around **control, visual consistency, local-first AI, and maintainable delivery**.

This is a **public, high-level roadmap**. The implementation repository remains private during the engineering phase. The Alpha 0.1 milestone is an isolated VM validation, not an installation guide, a public release announcement, or a promise of availability on any particular date.

## Product pillars

| Pillar | Direction |
| --- | --- |
| **Distinct desktop** | Arch Linux foundation, Wayland, Niri/Lniri, Noctalia, customized Glass experience |
| **Local-first AI** | Conversational assistant with local inference, speech recognition, speech synthesis and explicit consent |
| **Safe automation** | Narrowly scoped commands, authenticated transport, minimal telemetry, backup and rollback |
| **Distribution quality** | Versioned packages, build checks, package signing, repeatable testing and recovery |
| **User ownership** | Transparent behavior, reversible changes and user-controlled services |

## Milestones

### Phase 0. Workstation prototype

**Status: in use as a personal development environment.**

- [x] Build a customized Arch-based desktop experience.
- [x] Integrate Niri/Lniri with Noctalia and selected applications.
- [x] Prototype local assistant components and remote bridge operations.
- [ ] Complete long-term stability, usability and documentation review.

### Phase C. Reproducible packages and updates

**Status: lab prototyping and validation. Not a production update channel.**

- [x] Create initial package descriptions and an experimental command-line interface.
- [x] Exercise an isolated package build and temporary signing workflow in CI.
- [ ] Compile and validate the customized compositor package in a clean build environment.
- [ ] Finish independent package licensing and redistributability checks.
- [ ] Establish real release signing keys and a trusted package repository.
- [ ] Validate backups, migrations and rollback on a clean test installation.
- [ ] Release a supported, user-facing update channel.

### Phase D. Installable distribution

**Status: private Alpha 0.1 Live ISO validated in QEMU UEFI (November 2026); installer and public release still planned.**

- [x] Build a private experimental Live ISO and verify its SHA-256.
- [x] Test graphical UEFI boot in QEMU with Niri/Wayland, Noctalia, Kitty, Thunar, network and PipeWire (`SILVOS_ALPHA_PASS`).
- [ ] Validate alternative UEFI configurations and physical hardware, including AMD RX 580.
- [ ] Investigate bit-for-bit ISO reproducibility; matching package inventories do not imply identical ISO hashes.
- [ ] Provide a documented installer, upgrade process and recovery procedure, tested first on disposable virtual disks.
- [ ] Publish release notes, checksums, verification instructions and applicable source licenses.

## Engineering rules

1. **No "it works on my machine" releases.** Isolated tests are useful, but they are not substitutes for real hardware validation.
2. **No silent system changes.** System modifications need clear authorization, scoped operations and rollback.
3. **No secrets in public issues, commits or logs.** No private messages, tokens or personal workspace material.
4. **No unverified compatibility claims.** Experimental components remain clearly marked.
5. **No premature release labels.** A public ISO appears only after licensing, packaging and recovery are verified.

## Following the project

You can follow [Sílvio Henrique's GitHub profile](https://github.com/silviodarko) for updates and public project announcements.

The project is not currently accepting installation requests or promising a download date.

---

*SilvOS is a work in progress, built in Brazil with a focus on privacy, craftsmanship and system ownership.*
