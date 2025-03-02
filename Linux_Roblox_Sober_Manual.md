# User Manual for Sober on Roblox

## Introduction
Welcome to the user manual for **Sober on Roblox**. This guide will help you install, run, update, reset, and uninstall Sober on a Linux system using Flatpak.

## How to Install Sober

To install Sober, use the following command:

```sh
flatpak install --user https://sober.vinegarhq.org/sober.flatpakref
```

## How to Run Sober on Linux

To run Sober, use the following command:

```sh
flatpak run org.vinegarhq.Sober
```

## How to Update Flatpak

To update Flatpak and all installed applications, use the following command:

```sh
flatpak update
```

## Sober FFlag config location
```sh
~/.var/app/org.vinegarhq.Sober/config/sober # location
xdg-open ~/.var/app/org.vinegarhq.Sober/config/sober/config.json # open using terminal
```

## How to Reset FFlags in Sober

To reset the FFlags in Sober, you need to remove the configuration files and run Sober again. Use the following commands:

```sh
rm ~/.var/app/org.vinegarhq.Sober/data/sober/exe/ClientSettings/ClientAppSettings.json
rm ~/.var/app/org.vinegarhq.Sober/config/sober/config.json
flatpak run org.vinegarhq.Sober
```

## How to Uninstall Sober

To uninstall Sober and remove any unused dependencies, use the following commands:

```sh
flatpak uninstall --force-remove org.vinegarhq.Sober
flatpak uninstall --unused
```

## Contact Support
If you need further assistance, please contact our support team:
- Email: muradafan11@gmail.com
- VinegarHQ Serer: [Join VinegarHQ Official Discord](https://discord.gg/vinegarhq-1069506340973707304)
- Discord Server: [Join our Discord](https://discord.gg/BahzvqnD)
- My Friends Discord Server: [Join My friends Discord](https://discord.gg/mtkebwB7Ab)
