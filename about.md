---
title: "About"
tagline: "building things that can't afford to fail — embedded systems by day, side projects by night"
socials: ["github:https://github.com/AbhinavXT", "twitter:https://twitter.com/AbhinavXT", "linkedin:https://linkedin.com/in/abhinavpathak21"]
---

Hey — I'm Abhinav.

I'm a software engineer at **Bharat Electronics Limited**, where I work on India's indigenous train protection systems — **Kavach** and **iCBTC**. My day job lives at the intersection of bare-metal firmware, safety-critical design, and the kind of code where a single misplaced bit can have real-world consequences. Everything I ship runs under **SIL-4 certification**, the highest safety integrity level in the industry.

Before this, I interned at **Biconomy** working on blockchain infrastructure, and I hold a **B.Tech in Computer Science**.

When I'm not writing firmware, I'm usually deep in competitive programming, building side projects, or writing horror fiction rooted in the folklore I grew up hearing in the hills of North India.

---

## What I work with

- **Languages** — C, C++, Rust, TypeScript, Kotlin, Python
- **Embedded** — ARM Cortex-R/M, TI MCU+ SDK, bare-metal RTOS, QSPI flash, DTHE hardware crypto
- **Protocols** — CAN-FD, UART, I2C, SPI, Ethernet/UDP, FSI
- **Systems** — bootloader design, OTA firmware updates, hardware abstraction layers
- **Web & Mobile** — Next.js, React, Tailwind, Jetpack Compose
- **Tools** — GDB, LLDB, JTAG, Wireshark, QEMU, Nix

---

## Currently building

- **Multi-protocol OTA bootloader** — a firmware update system for the TI AM2634 that routes updates over Ethernet/UDP to a central card, then fans out over CAN-FD to target boards. Dual-bank QSPI flash, SHA-256 + CRC32 integrity checks, power-cut safe metadata, and zero `goto` statements.
- **This blog** — a retro-aesthetic developer blog built with Next.js 16, TypeScript, and Tailwind. Posts are fetched at runtime from a separate GitHub repo. 8 color themes, 4 view modes, Cmd+K search, and a custom markdown parser that handles everything from callout blocks to syntax-highlighted inline code.
- **ImpulseGuard** — an Android app (Kotlin + Jetpack Compose) that acts as a friction layer for impulse spending. Want to open Amazon? Complete a checklist and survive a cooldown timer first.

---

## What you'll find here

- **Embedded systems** — deep dives into bare-metal ARM development, communication protocols, firmware architecture, and the unique constraints of safety-critical code
- **DSA & competitive programming** — algorithm breakdowns and data structure guides, mostly in C++, written the way I wish they existed when I was learning
- **Project build logs** — honest accounts of architecture decisions, debugging rabbit holes, and lessons from things I'm actively building
- **Horror fiction** — short stories drawing from Pahadi and North Indian folklore, because sometimes the scariest bugs aren't in code

---

## Philosophy

I try to write the kind of technical content I wish existed when I was figuring things out — **detailed enough to actually be useful**, honest about the tricky parts, and structured so you can follow along even if you're seeing the topic for the first time. No hand-waving past the hard bits.

> If you can't explain the edge cases, you don't understand the system.