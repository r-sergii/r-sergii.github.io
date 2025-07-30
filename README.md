# WordInPictureNextUs
WordInPictureNext for Linux (Flutter)

- [Description](#description)
- [Requirements](#requirements)
- [Download](#download)
- [Install](#install)
- [Run](#run)
- [Remove](#remove)

## Description
## Test your knowledge of American English

Test your knowledge of American English

### Light theme
![wordinpicturenext_en01.png](/screenshots/wordinpicturenext_en01.png)

### Dark theme
![wordinpicturenext_en02.png](/screenshots/wordinpicturenext_en02.png)

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
flatpak install -y org.gnome.Sdk/x86_64/44
flatpak install -y org.gnome.Platform/x86_64/44
flatpak install -y flathub org.freedesktop.appstream-glib
```

To display webview on Linux, WebKit2GTK development libraries are used, if you don't have it already installed:

#### Ubuntu:

```bash
apt install libwebkit2gtk-4.1-dev
```
#### Fedora:

```bash
dnf install webkit2gtk3-devel
```

## Download

Download [flatpak file x86-64](https://github.com/r-sergii/r-sergii.github.io/releases/download/0.0.1/io.github.r_sergii.WordInPictureNextUs.flatpak)

<p align="center">
<a href="https://github.com/r-sergii/r-sergii.github.io/releases/download/0.0.1/io.github.r_sergii.WordInPictureNextUs.flatpak">
    <img width="200" src="https://flathub.org/assets/badges/flathub-badge-en.png" alt="Download on Flathub ">
</a>
</p>

## Install

```bash
flatpak install --user io.github.r_sergii.WordInPictureNextUs.flatpak
```

Check the success of the installation, the appearance in the menu [Utilities, Standard, ... ] (depending on the Linux distribution) 

or from the Terminal ...

```bash
flatpak list --app | grep io.github.r_sergii.WordInPictureNextUs
```

## Run

Call from the menu [Utilities, Standard, ... ] (depending on the Linux distribution) 

or from the Terminal ...

```bash
flatpak run io.github.r_sergii.WordInPictureNextUs
```

## Remove

```bash
flatpak remove io.github.r_sergii.WordInPictureNextUs
```
