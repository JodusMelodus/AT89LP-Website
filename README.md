# AT89LP-IDE

A simple, integrated development environment for AT89LP microcontrollers, built directly into VS Code. This extension brings the tools you need for AT89LP development into VS Code, providing a simple and clean interface.

## Features

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

## Getting Started

### 1. Install the dependencies

**AT89LP IDE requires the following software to be installed separately**.

Please install both dependencies using their **default installation options**.

- [SDCC](https://sdcc.sourceforge.net/index.php#Download)
- [Atmel FLIP](https://www.microchip.com/en-us/development-tool/flip)

### 2. Install AT89LP IDE

Install **AT89LP IDE** from the VS Code Marketplace.

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

# Features

## Build Menu
![Build Menu](assets/build_menu.png)

## Program Menu
![Program Menu](assets/program_menu.png)

## Serial Monitor
![Serial Monitor Menu](assets/serial_monitor_menu.png)

## License

See [License](LICENSE.md)
