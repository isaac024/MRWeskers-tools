# Torrentéka changelog

Newest first. Each version links to its release with the installer.

## [0.2.0](https://github.com/isaac024/MRWeskers-tools/releases/tag/torrenteka-v0.2.0) (2026-11-21)

**New**
- Ratio column: how much you've uploaded compared to what you downloaded, over the torrent's whole life. Hover it to see both totals. Also in the Sort menu.
- Tells you at startup when a newer version is out; click the message to get it. Can be switched off in Settings.

**Changed**
- Every column in the list is centred.
- Settings: the colour pickers fold away under the preset line (arrow on the right), closed by default.
- Close to tray lives only in the toolbar now.
- "Too big for the Recycle Bin" now lists just the torrents and their sizes, measured from what's really on disk.

**Fixed**
- No empty box in the status bar when there's no message.
- A warning that keeps repeating (like an unreadable drive) now clears on time instead of staying forever.

## [0.1.0](https://github.com/isaac024/MRWeskers-tools/releases/tag/torrenteka-v0.1.0) (2026-11-21)

First release.

**Downloading**
- Add from `.torrent` files, magnet links, bare hashes, the clipboard or by
  dropping onto the window; several at once, one step each.
- Folders: Series, Games, Movies and Programs under your download folder,
  guessed from the name and pre-selected, never moved without you.
- Spots duplicates (offers to add their trackers instead) and torrents that
  look like one you already have.
- Pause, resume, move to another folder, force re-check, add trackers.
- Speed limits for everything or per torrent; a lock in the status bar shows
  when one is on.
- Holds torrents when a drive is running out of room and resumes them when
  there's space again.
- Keeps working after a restart without checking every file again.

**Staying tidy**
- Remove and delete files: to the Recycle Bin, always confirmed; asks before
  deleting for good when the bin is too small.
- Checkup: finds downloads deleted from disk and clears them in one click.
- Red rows for torrents that need you (no file list after 5 minutes, all
  trackers failing, disk full, file errors), each with Retry now.

**Window**
- BitTorrent-style toolbar: select box with "select by state", icon buttons
  while rows are selected, Sort dropdown (Most recent by default).
- Resizable columns, remembered window size and sort.
- Close to tray, tray icon with a red dot when something needs you, finish
  popups that wait during full-screen games.
- Busy signs: a status-bar spinner saying what's being worked on, and a
  moving light on rows being checked, moved or removed.
- Settings: colours with live preview and presets, download folder, limits,
  listen port, popups; asks before throwing away unsaved changes.
- One copy at a time: opening a torrent file while it runs adds it to the
  open window.

**Light on your PC**
- About 50 MB of memory with 50 torrents, no GPU use, nothing animating while
  minimised.
