# Liri Media Player – User Guide

*[Deutsche Version](ANLEITUNG.html)*

For Fire TV, Android TV and Android (phone/tablet). The app contains **no channels and no content** – you use the login details of your own provider.

**Contents:** [Install](#1-install) · [Set up](#2-set-up) · [Overview](#3-overview) · [Live TV](#4-live-tv) · [Movies & Series](#5-movies--series) · [My List & Search](#6-my-list--search) · [Phone & Tablet](#7-phone--tablet) · [Settings](#8-settings) · [Parental control](#9-parental-control) · [Updates & problems](#10-updates--problems)

---

## 1. Install

**Fire TV – Amazon Appstore (recommended)**
1. Open **Search** (magnifier) on your Fire TV.
2. Type **"liri"**.
3. Select **Liri Media Player** → **Download**.
4. Done – Downloader and "Install unknown apps" are no longer needed.

> **Previously installed the APK version?** First *Settings → Backup → Save backup*.
> If the store version won't install: uninstall the old version, install the store version, *Load backup*.

**Android TV / phone:** Open the link `https://github.com/LiriPlayer/liri-releases/releases/latest/download/Liri.apk` in the browser, open the file → **Install** (the first time, allow installing from this source).

---

## 2. Set up

On first start, **Add playlist** appears:

- **Xtream login:** server URL (e.g. `http://server.tld:8080`), username and password from your provider. This gives you live TV, TV guide, **movies and series**.
- **M3U link:** a link starting with `http`. Movies and series appear as groups in the channel list.

→ **Load**. The first time, loading movies and series takes a moment.

Multiple playlists: *Settings → Playlists* (OK = switch, long OK = remove).

---

## 3. Overview

In the top bar:

| | |
|---|---|
| **Home** | Recently watched, recently added, rows by genre (adjustable) |
| **Live TV** | Channels by category |
| **Movies** / **Series** | by category and genre |
| **Search** | channels, movies and series |
| **My List** | watchlist and favourite channels |
| **Settings** | ⚙ |

**Remote control basics**
- **OK** = open / play · **long OK** = menu for the item (My List, move, hide …)
- **Left** at the start of a row = category list
- **Back** = always back to where you came from · on the home screen **Back twice** = exit the app
- **Hold ↑** = jump to the top of the list

---

## 4. Live TV

**Full screen (default keys)**

| Key | Function |
|---|---|
| **OK** / **Left** | channel list |
| **Up / Down** | change channel (zapping) |
| **Long Up** | info about the current programme |
| **Right** | last watched channel |
| **⏯** | pause / resume (live pause) |
| **⏩** | TV guide |
| **⏪** | last watched channel |
| **☰ Menu** | playback menu: audio track, subtitles, aspect ratio, sleep timer |
| **Back** | channel list · **long Back** = live TV overview |

All keys can be changed: *Settings → Live TV → Key mapping*.

**In the channel list – long OK on a channel:**
Add to "My List" · Set as **start channel** (starts when the app opens) · Move · Hide.
Separator entries from the provider (e.g. "✦•✦• SPORT ✦•✦•") show the Liri logo instead of advertising.
If the same channel exists several times (e.g. HD/FHD), the app shows the other versions under "Also in:".

**Categories – long OK:** add to "My List", set as start category, move, hide, lock (PIN).
Arrange all groups at once: *Settings → Live TV → Manage groups* (OK = visible → hidden → locked, long OK = move).

---

## 5. Movies & Series

- **OK** on a cover = detail page: **Play**, **From the start**, **Watchlist**, **Languages / versions**, for series seasons and episodes.
- **Long OK** on a cover = watchlist, remove from history, other language/version.
- **Long OK** on the row title or category = **filter** (genres, rating from ★, languages).
- *Manage categories*: show/hide and sort the provider's categories.

**During playback**

| Key | Function |
|---|---|
| **Left / Right** | seek (step size in settings) |
| **⏪ / ⏩** | seek step back / forward |
| **⏯** / **OK** | pause / show the bar |
| **Up** | bar, Up again = info about the movie/episode |
| **Down** (2×) | recommendations and similar titles |
| **☰ Menu** | audio track, subtitles (also size), aspect ratio, sleep timer |

- **Skip intro** (series): "OK = Skip intro" appears at the bottom right. Optionally automatic per series.
- **Next episode** starts automatically (adjustable).
- If a title doesn't play: try **another version** (language/quality) or **Open in another app**.
- Progress is saved → row **Recently watched** on the home screen.

---

## 6. My List & Search

- **My List:** watchlist (movies & series) and favourite channels. Add with **long OK** → "☆ Add to “My List”" or "+ Watchlist".
- **Search:** finds channels, movies and series at the same time; results can be filtered by language.

---

## 7. Phone & Tablet

**Live TV**
- Swipe **up / down** = change channel · **left** = last channel · **right** = channel list
- Tap = info bar · long press on the right = programme info · long press on the left = live TV overview
- In portrait mode the picture is at the top with the list below; tap the picture = full screen.

**Movies & Series**
- Tap = bar on/off · double-tap left/right = seek step back/forward · double-tap centre = pause
- Swipe horizontally = seek · swipe vertically on the left = **brightness**, on the right = **volume**

**Everywhere**
- Double-tap on an empty area = Back · swipe from the left edge = category list
- Close a window: tap next to it or Back.

---

## 8. Settings

| Section | What you can set |
|---|---|
| **General** | app language (11 languages), start screen (home / live TV), start channel, **autostart** when the device turns on, **key sounds** (follow the system sounds), screensaver |
| **History** | delete recently watched channels, movies and series |
| **Playlists** | switch, add, refresh (also automatically) |
| **Appearance** | design & themes (own colours, font and cover size, focus style, transparency) |
| **Clock & time zone** | time zone, show clock, size, position |
| **Live TV** | zapping delay, manage groups, **key mapping**, TV guide (reload, shift, own address) |
| **Playback** | auto frame rate (against stutter), audio decoder, aspect ratio, preferred audio track, subtitles, technical info |
| **Movies & Series** | next episode automatically, seek steps, "watched" from, skip intro, language of descriptions, subtitle style, cover overlays (rating, rank, progress, **release year**), home screen rows |
| **Parental control** | PIN, locked categories |
| **Backup** | save / load (favourites, orders, watchlist, settings, playlists) |
| **About / Legal** | version, **Check for update**, **Report a problem**, privacy, licences |

**Tip for stutter:** turn on *auto frame rate*; for audio problems set the *audio decoder* to "Automatic" or "Always software" (takes effect after restarting the app).

**Screensaver:** only appears when nothing is playing (menus, pause) – shows covers from your movies and series.

---

## 9. Parental control

1. *Settings → Parental control → **Set PIN*** (4 digits).
2. Lock categories: there under "Manage locked categories", or in live TV **long OK** on the category → **Lock**.
3. Locked categories only appear after entering the PIN (valid until the app is closed).

Without a PIN nothing can be locked.

---

## 10. Updates & problems

- **Updates:** Installed from the Amazon Appstore: updates come automatically through the store.
  APK version (Android TV / phone): the app reports new versions itself ("Update available" → **Install**). On the first update the device asks whether Liri Media Player may install apps → allow. Manually: *Settings → About / Legal → Check for update*.
- **Report a problem:** *Settings → About / Legal → Report a problem* – briefly describe what isn't working → **Send**. App version, device model and a technical log are included – **no login details**.
- **After a crash** the app asks on the next start whether it may send the report. Optionally "Send automatically in future".
- **Backup:** before changing devices, *Save backup* – on the new device *Load backup*.

**Frequently asked questions**
- *No movies/series?* These are only available with an Xtream login.
- *No TV guide?* *Settings → Live TV → Reload TV guide*; if the time is wrong: *Shift TV guide*.
- *A channel doesn't play?* Choose another version of the channel ("Also in:") – often it's the provider.

---

Contact: **mediaplayerliri@proton.me** · © Liri Media Player
