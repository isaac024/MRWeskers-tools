# Torrentéka

A small, fast BitTorrent client for Windows. No ads, your own colours, about
50 MB of memory with 50 torrents (BitTorrent Web used about 330 MB in the same
test).

**Latest: 0.2.0 (2026-11-21)**:
[Torrenteka-Setup.exe](https://github.com/isaac024/MRWeskers-tools/releases/download/torrenteka-v0.2.0/Torrenteka-Setup.exe)
(about 31 MB). Every version: [CHANGELOG.md](CHANGELOG.md).

## Install

1. Download `Torrenteka-Setup.exe` and run it.
2. If Windows says "Windows protected your PC": **More info**, then
   **Run anyway** (the installer isn't signed yet).
3. Pick the options you want: a desktop shortcut, and "Start with Windows"
   (off unless you tick it).

It installs for your user only, no admin rights needed. Uninstall from
Windows Settings > Apps. Your settings and torrent list stay in
`%APPDATA%\torrent-client`, so a reinstall picks up where you left off.

## What it does

- Add torrents from a `.torrent` file, a magnet link or hash, the clipboard,
  or by dropping them on the window. Each one asks where it goes: Series,
  Games, Movies or Programs (guessed from the name), the main folder, or any
  folder you pick.
- Pause, resume, move, re-check, speed limits per torrent or for everything.
- Remove and delete files sends them to the Recycle Bin, always after asking.
- Checkup finds downloads you deleted by hand and offers to clear them from
  the list.
- Close to tray keeps downloads going with the window closed.
- Coloured rows: green done, blue downloading, grey paused, red needs you,
  with a Retry button.
- Finish popups wait while you play a full-screen game.

## Requirements

Windows 10 or 11, 64-bit.
