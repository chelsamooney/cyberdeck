# Glossary

This glossary is built throughout the project.

Definitions are intentionally concise and focus on practical understanding rather than textbook precision.

---

## BIOS

Basic Input/Output System.

Legacy firmware responsible for initializing hardware before handing control to an operating system.

Modern systems generally use UEFI instead.

---

## Cyberdeck

A custom-built portable computer designed around the builder's needs rather than commercial constraints.

Cyberdecks typically prioritize repairability, modularity, experimentation, and personalization.

---

## Embedded Controller (EC)

A dedicated microcontroller inside many laptops.

Responsible for low-level tasks such as:

- Power button events
- Battery charging
- Keyboard scanning
- Fan control
- Sleep and wake behavior

The EC remains active even when the operating system is not running.

---

## Firmware

Software stored directly on hardware devices.

Firmware starts before the operating system and provides low-level control over hardware.

Examples include:

- UEFI
- SSD firmware
- Wi-Fi firmware
- Embedded Controller firmware

---

## Motherboard

The primary circuit board that connects all major computer components.

Rather than performing computation itself, it distributes power and provides communication pathways between hardware devices.

---

## Subsystem

A group of components working together to perform a specific function.

Examples include:

- Display subsystem
- Storage subsystem
- Power subsystem
- Thermal subsystem
- Networking subsystem

Thinking in subsystems simplifies understanding complex computers.

---

## UEFI

Unified Extensible Firmware Interface.

The modern replacement for BIOS.

Responsible for hardware initialization and launching the operating system's bootloader.