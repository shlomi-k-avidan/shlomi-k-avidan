# Shlomi Avidan

**Embedded & Firmware Engineer | Cyber Security | M.Sc. ECE, VLSI/RFIC @ Ben-Gurion University**

Currently: independent security research on a D-Link DSL-224 xDSL gateway — UART root shell, bit-exact 8 MB SPI flash dump, SquashFS carving, MIPS httpd analysis in Ghidra.

---

### Selected work

- **[D-Link DSL-224 hardware security research](https://github.com/shlomi-k-avidan/dsl-224-research)** — Firmware extraction and vulnerability research on a Realtek-based DSL router. UART root shell (baud measured on an oscilloscope, console via a bit-banged ESP8266 bridge), md5-verified 8 MB SPI flash dump over `nc`, SquashFS rootfs carving, static analysis of the MIPS web stack in Ghidra, on-target debugging with a cross-compiled big-endian MIPS gdbserver. *In progress.*
- **[Blind HID Injector — ADB enablement on a dead-display Android](https://github.com/shlomi-k-avidan/Pixel-6_Recovery_HID_Injector)** — Raspberry Pi Pico (CircuitPython) presenting as a composite USB HID device that blindly drives the Android UI to enable USB Debugging on a Pixel 6 with a dead screen. Relative-to-absolute pointer calibration by corner-slamming, deterministic keyboard focus traversal, and an honest write-up of where the technique hits its observability limit.
- **[Check Point Security Academy CTF writeup](https://github.com/shlomi-k-avidan/ctf-writeups)** — Reverse-engineered a custom network protocol from packet captures, recovered the XOR key of a challenge-response scheme, and built a working exploit past a CRC-32 integrity check. Also MITM via ARP spoofing with RC4 key recovery, plus cryptography, forensics, and steganography.
- **[CEE-Masters](https://github.com/shlomi-k-avidan/CEE-Masters)** — Graduate technical work in semiconductor devices and nanophotonics, including an independent reproduction and critique of a *Science* paper on dielectric metasurfaces (with my own MATLAB simulations) and first-principles reviews of solar-cell physics.
- **[BGU remittance automator](https://github.com/shlomi-k-avidan/bgu-remittance-automator)** — Multi-stage Python pipeline written by hand in 2022 that replaced a full-time manual data-processing role: cleaning and validating messy monthly financial spreadsheets, resolving donor IDs, driving records into a Salesforce CRM. Backed by a formal recommendation letter from the division CFO.
- **[Arduino Nano SDI-12 → USB bridge](https://github.com/shlomi-k-avidan/Arduino-Nano-SDI-12-to-USB-Bridge-for-HydraProbe)** — Interface between an Arduino Nano (ATmega328P) and a Stevens HydraProbe soil sensor over the SDI-12 protocol, with a clean parser and full documentation.

**Achievements:** 1st place (solo, out of 69 teams) — Iron Codes CTF, Tel Aviv University CyberWeek 2024 · HackTheBox rank #1,026 globally (July 2026) [`s4ma3l`](https://profile.hackthebox.com/profile/019e3cb8-674c-7298-be1f-58a22dfe8035)

**Contact:** [LinkedIn](https://www.linkedin.com/in/shlomi-k-avidan/) · shlomika99@gmail.com

**Legacy Projects:** [BGU scanned-exam downloader](https://github.com/shlomi-k-avidan/BGU-Exam-Downloader) — student-era 
tool that retrieved your own scanned exams before official publication by reconstructing the 
download token (release gate existed only in the UI; since fixed by the university).
