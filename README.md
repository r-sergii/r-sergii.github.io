# multiCurrencyLite
multiCurrency for Linux (Flutter)

- [Description](#description)
- [Requirements](#requirements)
- [Download](#download)
- [Install](#install)
- [Run](#run)
- [Remove](#remove)

## Description
## Cross-rates of major world currencies

multiCurrency Lite allows monitoring of both direct and reverse quotes cross-rates of major world currencies.

### Screen of cross-rate quotes for the selected currency
![mcurrencylite_ticker.png](/screenshots/mcurrencylite_ticker.png)

### Screen of the candlestick chart of the selected cross-rate for the selected currency
![mcurrencylite_candle.png](/screenshots/mcurrencylite_candle.png)

### Screen of the OHLC chart of the selected cross-rate for the selected currency
![mcurrencylite_ohlc.png](/screenshots/mcurrencylite_ohlc.png)

### Screen of the bar chart of the selected cross-rate for the selected currency
![mcurrencylite_bar.png](/screenshots/mcurrencylite_bar.png)

### Screen of the line chart of the selected cross-rate for the selected currency
![mcurrencylite_line.png](/screenshots/mcurrencylite_line.png)

### Screen of the basic settings
![mcurrencylite_settings.png](/screenshots/mcurrencylite_settings.png)

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

Download [flatpak file](https://github.com/r-sergii/r-sergii.github.io/releases/download/0.0.1/io.github.r_sergii.multiCurrencyLite.flatpak)

<p align="center">
<a href="https://github.com/r-sergii/r-sergii.github.io/releases/download/0.0.1/io.github.r_sergii.multiCurrencyLite.flatpak">
    <img width="200" src="https://flathub.org/assets/badges/flathub-badge-en.png" alt="Download on Flathub ">
</a>
</p>

## Install

```bash
flatpak install --user io.github.r_sergii.multiCurrencyLite.flatpak
```

Check the success of the installation, the appearance in the menu [Utilities, Standard, ... ] (depending on the Linux distribution) 

or from the Terminal ...

```bash
flatpak list --app | grep io.github.r_sergii.multiCurrencyLite
```

## Run

Call from the menu [Utilities, Standard, ... ] (depending on the Linux distribution) 

or from the Terminal ...

```bash
flatpak run io.github.r_sergii.multiCurrencyLite
```

## Remove

```bash
flatpak remove io.github.r_sergii.multiCurrencyLite
```
