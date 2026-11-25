# Karaoke Gia Đình — Family Karaoke TV

A karaoke room for Android TV / Google TV: a curated song library, a queue with each singer's name, and Party Mode — guests pick songs from their phones. No YouTube Data API, no account.

Made by **Toan Nguyen IT Oz** — free educational apps and content for the Vietnamese community in Australia.

![Karaoke Gia Đình](https://img.shields.io/badge/platform-Android%20TV%20%7C%20Google%20TV-green)
![Languages](https://img.shields.io/badge/languages-English%20%7C%20Ti%E1%BA%BFng%20Vi%E1%BB%87t-blue)
![License](https://img.shields.io/badge/license-MIT-lightgrey)

## What is it?

Open the app and pick a song from the built-in library — bolero, nhạc vàng, quê hương, tân cổ, nhạc trẻ, nhạc đỏ, thiếu nhi and more. Songs play in the official YouTube player, and the queue shows who is singing next. In Party Mode the TV shows a QR code: guests scan it with their phone, enter the 4-digit room code and their name, then search and add songs to the TV queue — no app install, no account.

## Features

- **Curated library:** 628 songs picked by hand, no YouTube Data API anywhere
- **Search:** on-screen Telex keyboard + accent-insensitive matching — type `da co hoai lang` and *Dạ Cổ Hoài Lang* is found
- **Queue:** every entry carries the singer's name (default "Cả nhà"); reorder with ◀ ▶, OK = sing next; queue persists across restarts
- **Player:** official YouTube IFrame player. Videos the channel blocks on TV get a short bilingual notice and the queue auto-skips to the next song
- **After each song:** a fun score (85–100, clearly labelled "just for fun") with a compliment, then a 10-second countdown to the next song
- **Party Mode (the headline feature):** the TV shows a QR + 4-digit room code and runs a small LAN server (port 8080, fallback 18080) only while Party Mode is on. Guests browse the same library on their phone, add songs, watch the live queue and send song requests
- **Party extras:** keys **1/2/3** play applause / cheer / whistle (all sounds synthesized in code — no audio files, zero licensing questions)
- **Favorites per person** (Bài tủ của Ba / của Mẹ…), **History** with one-key re-queue, **Request-a-song** list
- **Bilingual VI/EN everywhere** — one persisted footer toggle
- **"Buy me a coffee" QR** in the footer, lobby music with **MUTE on keycode 91**

## Install on your TV

The app is a standard Android TV APK. Pick the easiest method:

### Option A — Downloader (AFTVnews)
1. Install **Downloader** from the Play Store (Android TV / Google TV) or Amazon Appstore (Fire TV).
2. Open Downloader and enter code **1373226** (or the APK link from the latest release below).
3. Tap **Go** to download, then **Install** (allow "Install unknown apps" for Downloader if asked).

### Option B — Send Files to TV
1. Install **Send Files to TV** on your TV and on your phone.
2. Send the APK file from your phone to the TV, then open it with a file manager and tap **Install**.

### Option C — USB
1. Copy the APK onto a USB drive (FAT32).
2. Plug it into the TV, open a file manager, tap the APK and install.

Requires Android 5.0+ (Android TV / Google TV). The app appears as **Karaoke Gia Đình** in your apps.

## Download

Get the APK from the latest release on the [Releases](../../releases) page.

**Latest: v1.0.8** — `KaraokeGiaDinh-ToanNguyen-v1.0.8.apk`, 1,557,721 bytes, SHA-256 `52854f1397256aaba47f5f597e82c96f0e9a5e5c5c979cb70733c6a26a82a5e6`, versionCode 9. Installed and verified on a real TV.

## Changelog

### v1.0.8
- Support dialog now shows a website QR + link (toannguyeninoz.pp.ua) next to Buy Me a Coffee
- Fixed the website QR drawing on the TV screen (it rendered as a blank box in v1.0.7 — QR modules were drawn in unscaled coordinates)

### v1.0.7
- Support dialog: second QR + website link (toannguyeninoz.pp.ua) — website QR did not render on TV (fixed in v1.0.8)
