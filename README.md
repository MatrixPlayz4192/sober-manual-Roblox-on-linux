# Roblox Studio with VinegarHQ on Linux

## Introduction
This guide will help you set up Roblox Studio using Vinegar Client on a Linux system. Follow the steps below to install necessary tools, configuring FFlags, and get started.

## Prerequisites
1. Ensure you have Flatpak installed on your system. You can find installation instructions for your Linux distribution [here](https://flatpak.org/setup/).
2. Visit [VinegarHQ installation guides](https://vinegarhq.org/Installation/guides/package.html) to check your system distro commands (if u dont want to install using flatpak).

## Installation

### Step 1: Install Flatpak
Follow the instructions for your Linux distribution on the [Flatpak setup page](https://flatpak.org/setup/).

### Step 2: Install Vinegar
Once Flatpak is set up, install Vinegar using the following command:
```sh
flatpak install flathub org.vinegarhq.Vinegar
```

### Step 3: Run Vinegar
To manually run Vinegar, use the command:
```sh
flatpak run org.vinegarhq.Vinegar
```

## Performance FFlags for Studio Vinegar

Add the followings to optimize Roblox Studio (Vinegar) performance:

```ini
[env]
WINEFSYNC = "1"
WINEESYNC = "1"

[studio]
dxvk = false
renderer = "Vulkan"
gamemode = true

[studio.env]
DXVK_HUD = "0"
MANGOHUD = "1"

[studio.fflags]
DFIntTaskSchedulerTargetFps = 99999  
FFlagTaskSchedulerLimitTargetFpsTo2402 = false   
FFlagGameBasicSettingsFramerateCap5 = false  
```

### Renderer Options
You can change the renderer to one of the following options:
- Vulkan
- D3D11
- D3D10
- OpenGL
- Metal (only for macOS)

## Support
For further assistance, join the VinegarHQ support server on Discord: [VinegarHQ Discord](https://discord.com/invite/dzdzZ6Pps2)
