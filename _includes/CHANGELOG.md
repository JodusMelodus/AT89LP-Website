# Change Log

All notable changes to the "at89lp-ide" extension will be documented in this file.

## Unreleased

- **Dynamically create .vscode** - create `.vscode/c_cpp_properties.json` when not existing to support existing projects.

## 0.3.7 - 2026/08/21

- **Update UI to match new VS Code** - smooth UI to match the new VS Code look.
- **Add walkthrough** - to guide a beginner through the setup and usage.
- **Add dependency check** - check regularly if dependencies are installed.

## 0.3.6 - 2026/08/20

- **Error message when no project open** - display error message when no project is open and the user is trying to build
- **Remove accidental lock** - `programming` could fail to reset causing a lock and preventing the user from flashing.
- **Other small fixes** - User experience improvements

## 0.3.5 - 2026/08/20

- **Update icon** - change icon

## 0.3.4 - 2026/08/20

- **SDCC Diagnostics** - Diagnose c files to check for errors lazily
- **SDCC Preprocessor Keywords** - Updated pre-processor keywords
- **Prevent license sharing** - Limit license usage to single devices

## 0.3.3 - 2026/08/18

- **Fixed build bug** - Failed to clean build directory with no error message
- **Fixed license bug** - Premium activated accidentally