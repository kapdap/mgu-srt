---
layout: page
title: Home
interface_version: 0.9.0.0
provider_version: 0.9.0.0
---

MGU SRT is a speedrun tool for the *popular* PC game Martian Gothic: Unification.

## Installation

1. Download and install the any missing **[prerequisite](/mgu-srt/downloads.html#Prerequisite)** software.
2. Download and extract the latest version of **[SRT Host 32-bit](https://www.neonblu.com/SRT/){:target="_blank" rel="noopener"}**.
3. Download the latest **[MGU SRT Provider](https://github.com/kapdap/mgu-srt-provider/releases/download/{{ page.provider_version }}/mgu-srt-provider_v{{ page.provider_version }}.zip)** and **[MGU SRT UI WPF](https://github.com/kapdap/mgu-srt-ui-wpf/releases/download/{{ page.interface_version }}/mgu-srt-ui-wpf_v{{ page.interface_version }}.zip)** plugins.
4. Extract plugin contents to the SRT Host **plugins** folder.
5. Run **SRTHost.exe** and start Martian Gothic.

## Features

### Implemented

* Player health.
* Poison status.
* Caution/danger status.
* Enemy health.
* In-game timer.
* JSON HTTP Server via **[SRTPluginUIJSON](https://github.com/Squirrelies/SRTPluginUIJSON/){:target="_blank" rel="noopener"}**.

### Planned

* Inventory display.
* Equipped item.
* DirectX overlay.

## Repositories

* [MGU SRT Provider](https://github.com/kapdap/mgu-srt-provider/){:target="_blank" rel="noopener"}
* [MGU SRT UI WPF](https://github.com/kapdap/mgu-srt-ui-wpf/){:target="_blank" rel="noopener"}
* [SRTPluginUIJSON](https://github.com/Squirrelies/SRTPluginUIJSON/){:target="_blank" rel="noopener"}
* [SRT Host](https://github.com/Squirrelies/SRTHost/){:target="_blank" rel="noopener"}

## Special Thanks

* [Squirrelies](https://github.com/Squirrelies){:target="_blank" rel="noopener"} for [SRT Host](https://github.com/Squirrelies/SRTHost/){:target="_blank" rel="noopener"}, [ProcessMemory](https://github.com/Squirrelies/ProcessMemory){:target="_blank" rel="noopener"}, various other SRTs and assistance.
