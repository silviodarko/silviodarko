# SilvOS | Public roadmap / Roteiro público

> Active development · Pré-lançamento · November 2026  
> No public ISO or release date / Sem ISO pública ou data anunciada.

The engineering repository remains private. This roadmap describes milestones and their acceptance criteria, not operational internals.

## 01 · Foundation / Base

**Validated in a disposable VM / Validado em VM descartável**

- [x] Private Alpha 0.1 live boot.
- [x] Private Alpha 0.3 installed on qcow2, UEFI boot without ISO, Niri/Noctalia, network and CLI checks.
- [x] Secondary disk integrity checked.
- [ ] Physical installation matrix and reproducibility checks.

## 02 · UNITY Aurora

**Integration candidate / Candidata em integração**

- [x] Lab build, local conversation and streaming integration, settings, memory and audio regressions documented.
- [ ] Authenticated promotion, physical desktop validation and recovery.
- [ ] Confirm cancellation, resource release, everyday UX, reboot and game-mode behavior.
- [ ] Physical Android messenger validation, scoped access and device revocation.

The assistant is designed for local-first interaction and explicit authorization, not arbitrary system access.

## 03 · Vulcano

**Lab candidate / Candidata em laboratório**

- [x] Sequential execution and receipt reconciliation rehearsals with simulated dependencies.
- [x] Watchdog and rollback rehearsals in isolated environments.
- [ ] Independently authorized real workload, physical installation and two consecutive real jobs.
- [ ] Long-running resource, failure and recovery validation.

## 04 · Distribution and updates / Distribuição e atualizações

**Development and validation / Desenvolvimento e validação**

- [x] Initial package descriptions, isolated package build and temporary GPG signing.
- [ ] Customized compositor clean build and licensing review.
- [ ] Trusted release signing, package repository and complete upgrade in disposable VM.
- [ ] Backup, migration, rollback and recovery on a clean installation.
- [ ] Supported update channel; publish verified commands only after acceptance.

## 05 · Hardware adaptation / Adaptação ao hardware

**Proposed / Proposto**

- [ ] Common installer with hardware capability detection.
- [ ] Desktop-only profile, optional local AI, adaptive compute profiles.
- [ ] AMD, Intel, NVIDIA and CPU-only evaluation; no compatibility claim before results.
- [ ] Test memory tiers, firmware, boot, graphics, audio, network, suspend and recovery.
- [ ] Document tested hardware and known limitations, distinguishing workstation development use from clean installation tests.

## 06 · Public beta / Beta público

- [ ] Confirm licensing, dependencies, reproducible package sources and release signing.
- [ ] Publish installation, verification, recovery, accessibility and support documentation.
- [ ] Provide sanitized evidence and release notes.
- [ ] Release only after explicit review.

## Engineering principles / Princípios

No silent system changes, no secrets in public logs, no unverified hardware claims, no premature release labels. A laboratory test is not proof of physical operation. A public milestone requires reviewed, sanitized evidence.

Não há promessa de lançamento. O usuário permanece no controle das operações e da publicação. Os componentes têm níveis de maturidade diferentes.

[Perfil / Profile](./README.md) · [English](./README.en.md) · [Site](https://silviodarko.github.io/)
