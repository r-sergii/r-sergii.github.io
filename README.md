# multiElementNext
multiElement for Linux (Flutter)

- [Description](#description)
- [Requirements](#requirements)
- [Download](#download)
- [Install](#install)
- [Run](#run)
- [Remove](#remove)

## Description
## Alternative versions of the periodic table of chemical elements

Instant, complete encyclopedic information about each chemical element is available.
	    An indispensable application for students studying chemical disciplines

### Features:
 - It has a simple and clear interface.
 - A customizable online multilingual translation of the application interface

### Extended periodic table
![melementnext_extended.png](/screenshots/melementnext_extended.png)

### Short periodic table
![melementnext_short.png](/screenshots/melementnext_short.png)

### Circle periodic table
![melementnext_circle.png](/screenshots/melementnext_circle.png)

### Piramid periodic table
![melementnext_piramid.png](/screenshots/melementnext_piramid.png)

### Spiral periodic table
![melementnext_spiral.png](/screenshots/melementnext_spiral.png)

### ADOMAH periodic table
![melementnext_adomah.png](/screenshots/melementnext_adomah.png)

### Settings
![melementnext_settings.png](/screenshots/melementnext_settings.png)

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

Download [flatpak file x86-64](https://github.com/r-sergii/r-sergii.github.io/releases/download/0.0.1/io.github.r_sergii.multiElementNext.flatpak)

<p align="center">
<a href="https://github.com/r-sergii/r-sergii.github.io/releases/download/0.0.1/io.github.r_sergii.multiElementNext.flatpak">
    <img width="200" src="https://flathub.org/assets/badges/flathub-badge-en.png" alt="Download on Flathub ">
</a>
</p>

## Install

```bash
flatpak install --user io.github.r_sergii.multiElementNext.flatpak
```

Check the success of the installation, the appearance in the menu [Utilities, Standard, ... ] (depending on the Linux distribution) 

or from the Terminal ...

```bash
flatpak list --app | grep io.github.r_sergii.multiElementNext
```

## Run

Call from the menu [Utilities, Standard, ... ] (depending on the Linux distribution) 

or from the Terminal ...

```bash
flatpak run io.github.r_sergii.multiElementNext
```

## Remove

```bash
flatpak remove io.github.r_sergii.multiElementNext
```
