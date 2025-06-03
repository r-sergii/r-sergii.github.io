# multiClockNext
multiClock for Linux (Flutter)

- [Description](#description)
- [Requirements](#requirements)
- [Download](#download)
- [Install](#install)
- [Run](#run)
- [Remove](#remove)

## Description
## Current time in the world's largest financial centers

multiClock allows you to track the current time in major financial centers around the world

### Features:
 - It takes into account the transition to summer / winter time in selected cities.
 - Indispensable for Forex traders away from the trading monitor. It helps to navigate the start and end time of trading sessions on local financial exchanges.

### List of clocks with current time in the largest financial centers of the world (circle dial)
![mclocknext_circle.png](/screenshots/mclocknext_circle.png)

### List of clocks with current time in the largest financial centers of the world (square dial)
![mclocknext_quad.png](/screenshots/mclocknext_quad.png)

 - A customizable list of financial centers for display.
 - A customizable online multilingual translation of the application interface.
 - It has a simple and clear interface.

### Screen of the basic settings
![mclocknext_settings.png](/screenshots/mclocknext_settings.png)

## Requirements

Install flatpak

On ubuntu:

```bash
sudo apt install flatpak
```

Add the FlatHub repo:

```bash
flatpak remote-add --if-not-exists flathub https://flathub.org/repo/flathub.flatpakrepo
```

Install flatpak build dependencies:

```bash
flatpak install -y org.freedesktop.Sdk/x86_64/22.08
flatpak install -y org.freedesktop.Platform/x86_64/22.08
flatpak install -y flathub org.freedesktop.appstream-glib
```
To display webview on Linux, WebKit2GTK development libraries are used, if you don't have it already installed:

#### Ubuntu:

```bash
apt install libwebkit2gtk-4.0-dev
```
#### Fedora:

```bash
dnf install webkit2gtk3-devel
```

## Download

Download [flatpak file x86-64](https://github.com/r-sergii/r-sergii.github.io/releases/download/0.0.1/io.github.r_sergii.multiClockNext.flatpak)

<p align="center">
<a href="https://github.com/r-sergii/r-sergii.github.io/releases/download/0.0.1/io.github.r_sergii.multiClockNext.flatpak">
    <img width="200" src="https://flathub.org/assets/badges/flathub-badge-en.png" alt="Download on Flathub ">
</a>
</p>

## Install

```bash
flatpak install --user io.github.r_sergii.multiClockNext.flatpak
```

Check the success of the installation, the appearance in the menu [Utilities, Standard, ... ] (depending on the Linux distribution) 

or from the Terminal ...

```bash
flatpak list --app | grep io.github.r_sergii.multiClockNext
```

## Run

Call from the menu [Utilities, Standard, ... ] (depending on the Linux distribution) 

or from the Terminal ...

```bash
flatpak run io.github.r_sergii.multiClockNext
```

## Remove

```bash
flatpak remove io.github.r_sergii.multiClockNext
```
