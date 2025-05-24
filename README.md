# multiCurrencyNext
multiCurrency for Linux (Flutter)

- [Description](#description)
- [Requirements](#requirements)
- [Download](#download)
- [Install](#install)
- [Run](#run)
- [Remove](#remove)

## Description
## Cross-rates of major world currencies

multiCurrency Next allows monitoring of both direct and reverse quotes cross-rates of major world currencies.

### Screen of cross-rate quotes for the selected currency
![mcurrencynext_ticker.png](/screenshots/mcurrencynext_ticker.png)

### Screen of the candlestick chart of the selected cross-rate for the selected currency
![mcurrencynext_candle.png](/screenshots/mcurrencynext_candle.png)

### Screen of the OHLC chart of the selected cross-rate for the selected currency
![mcurrencynext_ohlc.png](/screenshots/mcurrencynext_ohlc.png)

### Screen of the bar chart of the selected cross-rate for the selected currency
![mcurrencynext_bar.png](/screenshots/mcurrencynext_bar.png)

### Screen of the line chart of the selected cross-rate for the selected currency
![mcurrencynext_line.png](/screenshots/mcurrencynext_line.png)

### Screen of the basic settings
![mcurrencynext_settings.png](/screenshots/mcurrencynext_settings.png)

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

Download [flatpak file](https://github.com/r-sergii/r-sergii.github.io/releases/download/0.0.1/io.github.r_sergii.multiCurrencyNext.flatpak)

<p align="center">
<a href="https://github.com/r-sergii/r-sergii.github.io/releases/download/0.0.1/io.github.r_sergii.multiCurrencyNext.flatpak">
    <img width="200" src="https://flathub.org/assets/badges/flathub-badge-en.png" alt="Download on Flathub ">
</a>
</p>

## Install

```bash
flatpak install --user io.github.r_sergii.multiCurrencyNext.flatpak
```

Check the success of the installation, the appearance in the menu [Utilities, Standard, ... ] (depending on the Linux distribution) 

or from the Terminal ...

```bash
flatpak list --app | grep io.github.r_sergii.multiCurrencyNext
```

## Run

Call from the menu [Utilities, Standard, ... ] (depending on the Linux distribution) 

or from the Terminal ...

```bash
flatpak run io.github.r_sergii.multiCurrencyNext
```

## Remove

```bash
flatpak remove io.github.r_sergii.multiCurrencyNext
```
