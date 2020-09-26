# Martian Gothic: Unification SRT

A SRT (Speedrun Tool) for Martian Gothic: Unification PC release.

## Installation

1. Download and install the [Prerequisites](#Prerequisites) below.
2. Download and extract the latest version of [SRT Host 32-bit](#Required).
3. Download the latest [MGU SRT Provider](#Required) and [MGU SRT UI WPF](#Required) plugins.
4. Extract plugin contents to the SRT Host **plugins** folder.

## Downloads

### Prerequisites:
* [.NET Core v3.1 x86](https://dotnet.microsoft.com/download/dotnet-core/current/runtime) or newer.
* [7-Zip](https://www.7-zip.org/) or any file extraction software.

### Required

* [SRT Host 32-bit](https://www.neonblu.com/SRT/).
* [MGU SRT Provider](https://github.com/kapdap/mgu-srt-provider/releases/download/0.9.0.0/mgu-srt-provider_v0.9.0.0.zip) **v0.9.0.0**.
* [MGU SRT UI WPF](https://github.com/kapdap/mgu-srt-ui-wpf/releases/download/0.9.0.0/mgu-srt-ui-wpf_v0.9.0.0.zip) **v0.9.0.0**.

### Optional

* [SRTPluginUIJSON](https://github.com/Squirrelies/SRTPluginUIJSON/).

## Features

### Implemented

* Player health.
* Poison status.
* Caution/danger status.
* Enemy health.
* In-game timer.
* JSON HTTP Server via [SRTPluginUIJSON](#Optional).

### Planned

* Inventory display.
* Equipped item.
* DirectX overlay.

## Components

* [MGU SRT Provider](https://github.com/kapdap/mgu-srt-provider/) - A provider plugin for SRT Host to provide memory values from Martian Gothic: Unification to other plugins.
* [MGU SRT UI WPF](https://github.com/kapdap/mgu-srt-ui-wpf/) - A WPF-based User Interface for displaying game memory values from the MGU SRT Provider plugin.

## Special Thanks

* [Squirrelies](https://github.com/Squirrelies) for [SRT Host](https://github.com/Squirrelies/SRTHost/), [ProcessMemory](https://github.com/Squirrelies/ProcessMemory), various other SRTs and assistance.