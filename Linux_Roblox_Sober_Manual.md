<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
<body>
    <h1 align="center">
        <img src="https://github.com/Nightro-Fx/Performance-FastFlags/blob/main/img/Sober.png" width="40" alt="Logo"/> 
        ## Roblox (Sober) on linux.
    </h1>

## Introduction
Welcome to the user manual for **Sober on Roblox**. This guide will help you install, run, update, reset, and uninstall Sober on a Linux system using Flatpak.
[Sober Vinegar Official](https://sober.vinegarhq.org/)

## Flatpak Flathub supported distros here.
https://flathub.org/setup

## Adding the Flathub repository.
```sh
flatpak remote-add --if-not-exists flathub https://dl.flathub.org/repo/flathub.flatpakrepo
```

## Installing Sober

To install Sober, use the following command:

```sh
flatpak install --user https://sober.vinegarhq.org/sober.flatpakref
```

## Running Sober

To run Sober, use the following command:

```sh
flatpak run org.vinegarhq.Sober
```

## Updating flatpak

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

## Uninstalling Sober

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
