# Chimera DevBoard V1.0: Silicon Verification & Rapid Prototyping

## 📋 Overview
The functional verification environment for the Chimera V1.0 project. This setup was utilized to perform initial silicon handshakes, calibrate the 20MHz clock, and resolve toolchain compatibility issues.

## 🧪 Verification Milestones
- **ICSP Handshake:** Successfully established a communication link between the PIC16F887 and a PICkit 3 clone.
- **Toolchain Migration:** Identified and resolved driver regressions in MPLAB X v6.xx by migrating to a stable v5.35 environment.
- **Device ID Validation:** Verified silicon integrity via real-time Device ID reporting (0x2080).
- **Signal Logic:** Calibrated the bare-metal "Heartbeat" (LED Blink) logic to the 20MHz external oscillator.

## 🛠️ Toolchain Details
- **IDE:** MPLAB X v5.35
- **Compiler:** XC8 v3.10
- **Programmer:** PICkit 3 (Firmware Sync: 01.56.07)

## 📸 Media
![photo_1_2026-03-04_20-57-46](https://github.com/user-attachments/assets/127655c7-f4e4-481f-be08-247504b73c8e)

## Schematics

<img width="803" height="545" alt="Screenshot 2026-03-04 205843" src="https://github.com/user-attachments/assets/1c017961-6e35-426b-b580-c8631c6b620f" />
