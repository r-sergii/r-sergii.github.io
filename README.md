# multiEAdditivesNext
multiEAdditives for Linux (Flutter)

- [Description](#description)
- [Requirements](#requirements)
- [Download](#download)
- [Install](#install)
- [Run](#run)
- [Remove](#remove)

## Description
## Food Additives Handbook. Find out the “what” you eat by buying goods in markets.

Food Additives - is the common name of natural or synthetic chemicals that are added to foods to make them certain properties (improvement of taste and smell, increase the nutritional value, and prevent contamination, etc., etc.), which It is not used as stand-alone food.

Handbook of food additives. Just pay attention to what is written in the composition of the ingredients on the packaging of the products you buy. And look in the application *that* it is you"ll have ... And then you decide.

### In one application:

Instant information about each of the additive.

### Features:

The indispensable app for all curious users. It features a simple and intuitive interface.

### Screen of searching for additives by categories dangerous
![meadditives_danger.png](/screenshots/meadditives_danger.png)

### Screen of searching for additives by number
![meadditives_find.png](/screenshots/meadditives_find.png)

### Screen of searching for additives by categories groups
![meadditives_groups.png](/screenshots/meadditives_groups.png)

### Screen of searching for additives by categories origin
![meadditives_origin.png](/screenshots/meadditives_origin.png)

### Screen of searching for additives by categories vegan
![meadditives_vegans.png](/screenshots/meadditives_vegans.png)

### Screen of searching for additives by categories classifications
![meadditives_classification.png](/screenshots/meadditives_classification.png)

### Information screen for the selected additive
![meadditives_info.png](/screenshots/meadditives_info.png)

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

## Download

Download [flatpak file](https://github.com/r-sergii/r-sergii.github.io/releases/download/0.0.1/io.github.r_sergii.multiEAdditivesNext.flatpak)

<p align="center">
<a href="https://github.com/r-sergii/r-sergii.github.io/releases/download/0.0.1/io.github.r_sergii.multiEAdditivesNext.flatpak">
    <img width="200" src="https://flathub.org/assets/badges/flathub-badge-en.png" alt="Download on Flathub ">
</a>
</p>

## Install

```bash
flatpak install --user io.github.r_sergii.multiEAdditivesNext.flatpak
```

Check the success of the installation, the appearance in the menu [Utilities, Standard, ... ] (depending on the Linux distribution) 

or from the Terminal ...

```bash
flatpak list --app | grep io.github.r_sergii.multiEAdditivesNext
```

## Run

Call from the menu [Utilities, Standard, ... ] (depending on the Linux distribution) 

or from the Terminal ...

```bash
flatpak run io.github.r_sergii.multiEAdditivesNext
```

## Remove

```bash
flatpak remove io.github.r_sergii.multiEAdditivesNext
```
