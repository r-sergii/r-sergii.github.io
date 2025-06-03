# multiCalendarNext
multiCalendar for Linux (Flutter)

- [Description](#description)
- [Requirements](#requirements)
- [Download](#download)
- [Install](#install)
- [Run](#run)
- [Remove](#remove)

## Description
## Calendars of different nations, religions and cultures on your device

## multiCalendar combines in a single application acting and "not very acting" calendars of various nations, religions and cultures on your device.

Find out when the next New Year comes the Orthodox, Islams, Persians, Jews, Buddhists, or when will the next New year on the eastern calendar.
Or move into the past to clarify what day of the week passed landmark historic date
(For example the French revolutionary calendar) and a date match in the calendar of other nations or religions.
And just ask what day of the week of your family members were born.
And a lot of other opportunities open to you this application.

### In one application:

  - Gregorian calendar - adopted today in the world as a major.
  - Julian calendar - used and currently Orthodox hrestiyanami. According to it, and now celebrate the Old New Year in Eastern Europe.
  - Chronological Calendar - Gregorian through years taken into account by Pope Gregory after 15/10/1583 and 04/10/1583 to the Julian calendar.
  - Moon Hidzhira - calendar adopted in Islamic countries.
  And the list goes on ....
  - Persian calendar.
  - The Jewish calendar.
  - EastAsian lunar calendar.
  - Coptic calendar.
  - The Ethiopian calendar.
  - French revolutionary calendar.
  - Bahai calendar.
  - Japan lunar calendar.
  - The Human Calculator calendar.

### Features:

Instant full encyclopedic information about each of the calendar view.
The indispensable app for all curious users.
It features a simple and intuitive interface.
Directory names days of the week or decades taken in different calendars.
Directory names of the months in different parts of the calendars.
Switching to a different date display formats.

### List calendars with current dates
![mcalendarnext_ticker.png](/screenshots/mcalendarnext_main.png)

### Example calendar
![mcalendarnext_candle.png](/screenshots/mcalendarnext_china.png)

### Detail info
![mcalendarnext_detail.png](/screenshots/mcalendarnext_detail.png)

### French revolutionary calendar
![mcalendarnext_france.png](/screenshots/mcalendarnext_france.png)

### Change current date
![mcalendarnext_date.png](/screenshots/mcalendarnext_date.png)

### Screen of the basic settings
![mcalendarnext_settings.png](/screenshots/mcalendarnext_settings.png)

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

Download [flatpak file x86-64](https://github.com/r-sergii/r-sergii.github.io/releases/download/0.0.1/io.github.r_sergii.multiCalendarNext.flatpak)

<p align="center">
<a href="https://github.com/r-sergii/r-sergii.github.io/releases/download/0.0.1/io.github.r_sergii.multiCalendarNext.flatpak">
    <img width="200" src="https://flathub.org/assets/badges/flathub-badge-en.png" alt="Download on Flathub ">
</a>
</p>

## Install

```bash
flatpak install --user io.github.r_sergii.multiCalendarNext.flatpak
```

Check the success of the installation, the appearance in the menu [Utilities, Standard, ... ] (depending on the Linux distribution) 

or from the Terminal ...

```bash
flatpak list --app | grep io.github.r_sergii.multiCalendarNext
```

## Run

Call from the menu [Utilities, Standard, ... ] (depending on the Linux distribution) 

or from the Terminal ...

```bash
flatpak run io.github.r_sergii.multiCalendarNext
```

## Remove

```bash
flatpak remove io.github.r_sergii.multiCalendarNext
```
