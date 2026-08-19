# AT89LP IDE

A simple, integrated development environment for AT89LP microcontrollers, built directly into VS Code.

AT89LP IDE brings project management, building, programming, calculations, and serial debugging together in one clean interface.

## Table of Contents

- [AT89LP IDE](#at89lp-ide)
  - [Table of Contents](#table-of-contents)
  - [Overview](#overview)
  - [Free VS Premium](#free-vs-premium)
  - [Premium](#premium)
  - [Quick Start Guide](#quick-start-guide)
    - [1. Install the dependencies](#1-install-the-dependencies)
    - [2. Install AT89LP IDE](#2-install-at89lp-ide)
    - [3. Create a project](#3-create-a-project)
  - [Why AT89LP IDE?](#why-at89lp-ide)
  - [Requirements](#requirements)
  - [Interface](#interface)
    - [Build Menu](#build-menu)
    - [Program Menu](#program-menu)
    - [Serial Monitor](#serial-monitor)
  - [License](#license)

## Overview

- **Simple Interface** - Only the tools you actually need, without unnecessary complexity.
- **Integrated Build System** - Build your projects directly from VS Code using SDCC.
- **Project Templates** - Quickly create new projects with a single button press.
- **Integrated Programmer** - Program/Flash your microcontroller directly from VS Code using Atmel FLIP.
- **Programmer's calculator** - Useful calculations for microcontroller development, right inside the IDE.
- **Serial Monitor** - Integrated serial monitor, for easy serial debugging.

## Free VS Premium

| Feature                               | Free | Premium |
| ------------------------------------- | ---- | ------- |
| Built-in build button                 | ✓    | ✓       |
| Project templates                     | ✓    | ✓       |
| Integrated microcontroller programmer | ✗    | ✓       |
| Programmer's calculator               | ✗    | ✓       |
| Serial monitor                        | ✗    | ✓       |

## Premium

AT89LP IDE is available as a free extension with additional premium
functionality for developers who need integrated programming, calculations,
and serial debugging.

Premium functionality includes:

- Integrated microcontroller programmer
- Programmer's calculator
- Integrated serial monitor

The core build system and project templates remain available in the free version.

## Quick Start Guide

### 1. Install the dependencies

**AT89LP IDE requires the following software to be installed separately**.

Please install both dependencies using their **default installation options**.

- [SDCC](https://sdcc.sourceforge.net/index.php#Download)
- [Atmel FLIP](https://www.microchip.com/en-us/development-tool/flip)

### 2. Install AT89LP IDE

Install [AT89LP IDE](https://marketplace.visualstudio.com/items?itemName=jodusmelodus-dev.at89lp-ide) from the VS Code Marketplace.

### 3. Create a project

- Use the `AT89LP: Create Project` command provided by the extension to create a new AT89LP project.
- Once your project is set up, you can build and program your microcontroller directly from VS Code.

## Why AT89LP IDE?

AT89LP development usually requires several separate tools for writing code, compiling it, and programming the microcontroller. AT89LP IDE simplifies and brings these steps into **one single interface**, so you can spend less time configuring and more time doing the fun stuff!

## Requirements

- Visual Studio Code
- SDCC
- Atmel FLIP
- AT89LP-compatible microcontroller

## Interface

### Build Menu
![Build Menu](assets/build_menu.png)

Compile your 8051 projects using this simple integrated build menu. Designed specifically so that you do not have to struggle to change any of your project settings. Beginner friendly but gives you all the power you need. 

### Program Menu
![Program Menu](assets/program_menu.png)

Program/Flash your AT89LP devices with a powerful built-in programmer. Easily change your targeted device, serial port and Baud rate with the dropdown menus.

### Serial Monitor
![Serial Monitor Menu](assets/serial_monitor_menu.png)

Debug your serial communications directly inside VS Code using the built-in serial monitor. Choose your serial port and baud rate with ease. Send and receive serial data using the integrated serial monitor, without installing any external dependencies.

---

## License

AT89LP IDE is proprietary software.

The free version of AT89LP IDE is available through the Visual Studio Code Marketplace.
Premium functionality is available separately.

See the [License](LICENSE.md) for the full license terms.

---

[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/JodusMelodus)
[![YouTube](https://img.shields.io/badge/YouTube-FF0000?style=flat-square&logo=youtube&logoColor=white)](https://www.youtube.com/@JodusMelodus)
[![Instagram](https://img.shields.io/badge/Instagram-E4405F?style=flat-square&logo=instagram&logoColor=white)](https://www.instagram.com/jodusmelodus_dev/)
[![VS Code Marketplace](https://img.shields.io/badge/VS%20Code%20Marketplace-007ACC?style=flat-square&logo=visualstudiocode&logoColor=white)](https://marketplace.visualstudio.com/publishers/jodusmelodus-dev)

---

**© 2026 Philip. All rights reserved.**

AT89LP is proprietary software. The free version is available through the
Visual Studio Code Marketplace. Premium features are available separately.

AT89LP is an independent project and is not affiliated with or endorsed by
Microsoft Corporation or Microchip Technology Inc.