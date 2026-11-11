<p align="right"><b>English</b> · <a href="README.de.md">Deutsch</a></p>

<p align="center">
  <img src="docs/icon-512.png" width="96" alt="Swipe Scout icon"><br><br>
  <picture>
    <source media="(prefers-color-scheme: light)" srcset="docs/banner-en-light.png">
    <img src="docs/banner-en-dark.png" alt="Swipe Scout – clean up photos & videos with a swipe" width="100%">
  </picture>
</p>

<p align="center">
  <b>Find every photo and video on your Android phone – even hidden, duplicate, similar and blurry ones –<br>
  and clean them up with a swipe.</b>
</p>

<p align="center">
  <a href="https://github.com/hyperflux22/SwipeScout/releases/latest/download/SwipeScout.apk">
    <img src="https://img.shields.io/badge/Download_APK-Version_4.0-6C7CFF?style=for-the-badge&logo=android&logoColor=white" alt="Download APK">
  </a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Android-8.0%2B-3DDC84?logo=android&logoColor=white" alt="Android 8.0+">
  <img src="https://img.shields.io/badge/languages-10-6C7CFF" alt="10 languages">
  <img src="https://img.shields.io/badge/theme-light_%26_dark-6C7CFF" alt="Light & dark">
  <img src="https://img.shields.io/badge/Windows%20·%20Mac%20·%20Android-6C7CFF" alt="Windows · Mac · Android">
  <img src="https://img.shields.io/badge/ads-none-43A047" alt="No ads">
</p>

---

## Contents

- [Why Swipe Scout?](#why-swipe-scout)
- [Screenshots](#screenshots)
- [Windows & Mac](#windows--mac)
- [Install](#install)
- [How it works](#how-it-works)
- [All features](#all-features)
- [Languages & appearance](#languages--appearance)
- [Privacy & safety](#privacy--safety)
- [FAQ](#faq)
- [Versions](#versions)
- [How the app is built](#how-the-app-is-built)
- [License](#license)
- [Feedback & support](#feedback--support)

## Why Swipe Scout?

Regular gallery apps only show what Android reports to them. Photos in **hidden folders**
(`.private`, folders with `.nomedia`), **hidden files** or photos with a **wrong extension**
(`.bng`, `.dat`, no extension at all) are missing there. Swipe Scout scans the whole storage,
recognizes photos and videos **by their content** – and lets you sort them as fast as in a dating app.

| | Regular gallery | **Swipe Scout** |
|---|:---:|:---:|
| Hidden folders & files | ✗ | ✓ |
| Wrong or missing extension | ✗ | ✓ |
| Sort by swiping | ✗ | ✓ |
| Find duplicate, similar & blurry photos | partly | ✓ |
| Filter by source (camera, WhatsApp …) | partly | ✓ |
| Trash with a freely adjustable time limit | partly | ✓ |
| Save as ZIP, copy to a folder | ✗ | ✓ |

## Screenshots

> [!TIP]
> **The app follows your phone’s light/dark setting** automatically (can also be set to light or dark by hand).
> The screenshots below show the dark version; if your own device is set to light mode, you see the light version.

<table>
  <tr>
    <td align="center" width="33%"><picture><source media="(prefers-color-scheme: light)" srcset="docs/screenshots/en/light/01-scan.png"><img src="docs/screenshots/en/dark/01-scan.png" width="270"></picture><br><b>Set up the scan</b><br><sub>Everything, photos only or videos only – hidden ones on request</sub></td>
    <td align="center" width="33%"><picture><source media="(prefers-color-scheme: light)" srcset="docs/screenshots/en/light/02-sort.png"><img src="docs/screenshots/en/dark/02-sort.png" width="270"></picture><br><b>Sort</b><br><sub>One file at a time, with format, size and source</sub></td>
    <td align="center" width="33%"><picture><source media="(prefers-color-scheme: light)" srcset="docs/screenshots/en/light/03-swipe.png"><img src="docs/screenshots/en/dark/03-swipe.png" width="270"></picture><br><b>Swipe</b><br><sub>Left keep, right sort out, up later</sub></td>
  </tr>
  <tr>
    <td align="center" width="33%"><picture><source media="(prefers-color-scheme: light)" srcset="docs/screenshots/en/light/04-all.png"><img src="docs/screenshots/en/dark/04-all.png" width="270"></picture><br><b>Overview</b><br><sub>Everything in a grid, tap to sort out</sub></td>
    <td align="center" width="33%"><picture><source media="(prefers-color-scheme: light)" srcset="docs/screenshots/en/light/05-filter.png"><img src="docs/screenshots/en/dark/05-filter.png" width="270"></picture><br><b>Filter</b><br><sub>Hidden, type and source</sub></td>
    <td align="center" width="33%"><picture><source media="(prefers-color-scheme: light)" srcset="docs/screenshots/en/light/06-smart.png"><img src="docs/screenshots/en/dark/06-smart.png" width="270"></picture><br><b>Sort order & smart search</b><br><sub>Largest first, duplicates, similar, blurry</sub></td>
  </tr>
  <tr>
    <td align="center" width="33%"><picture><source media="(prefers-color-scheme: light)" srcset="docs/screenshots/en/light/07-duplicates.png"><img src="docs/screenshots/en/dark/07-duplicates.png" width="270"></picture><br><b>Find duplicates</b><br><sub>Numbered groups, “Pick automatically”</sub></td>
    <td align="center" width="33%"><picture><source media="(prefers-color-scheme: light)" srcset="docs/screenshots/en/light/09-actions.png"><img src="docs/screenshots/en/dark/09-actions.png" width="270"></picture><br><b>Clean up</b><br><sub>Trash, move, copy, ZIP, share</sub></td>
    <td align="center" width="33%"><picture><source media="(prefers-color-scheme: light)" srcset="docs/screenshots/en/light/10-trash.png"><img src="docs/screenshots/en/dark/10-trash.png" width="270"></picture><br><b>Trash</b><br><sub>Restore, time limit fully adjustable</sub></td>
  </tr>
  <tr>
    <td align="center" width="33%"><picture><source media="(prefers-color-scheme: light)" srcset="docs/screenshots/en/light/11-stats.png"><img src="docs/screenshots/en/dark/11-stats.png" width="270"></picture><br><b>Storage statistics</b><br><sub>What takes how much space</sub></td>
    <td align="center" width="33%"><picture><source media="(prefers-color-scheme: light)" srcset="docs/screenshots/en/light/08-sorted-out.png"><img src="docs/screenshots/en/dark/08-sorted-out.png" width="270"></picture><br><b>Sorted out</b><br><sub>Everything sorted out at a glance</sub></td>
  </tr>
</table>

## Windows & Mac

Swipe Scout also runs on **Windows** and **Mac** – with all features of the phone app, plus things that are especially handy on a computer.

<table>
  <tr>
    <td align="center" width="50%"><picture><source media="(prefers-color-scheme: light)" srcset="docs/screenshots/desktop/en/light/1-sort.png"><img src="docs/screenshots/desktop/en/dark/1-sort.png" width="420"></picture><br><b>Sort with the arrow keys</b><br><sub>Large view, full path, “Show in folder”</sub></td>
    <td align="center" width="50%"><picture><source media="(prefers-color-scheme: light)" srcset="docs/screenshots/desktop/en/light/2-all.png"><img src="docs/screenshots/desktop/en/dark/2-all.png" width="420"></picture><br><b>Overview</b><br><sub>Adjustable tile size, click to sort out</sub></td>
  </tr>
  <tr>
    <td align="center" width="50%"><picture><source media="(prefers-color-scheme: light)" srcset="docs/screenshots/desktop/en/light/4-stats.png"><img src="docs/screenshots/desktop/en/dark/4-stats.png" width="420"></picture><br><b>Storage statistics</b><br><sub>What takes how much space</sub></td>
    <td align="center" width="50%"><picture><source media="(prefers-color-scheme: light)" srcset="docs/screenshots/desktop/en/light/0-scan.png"><img src="docs/screenshots/desktop/en/dark/0-scan.png" width="420"></picture><br><b>Choose where to search</b><br><sub>User folder, all drives or your own folders</sub></td>
  </tr>
</table>

| Key / mouse | Action |
|---|---|
| **←** | Keep |
| **→** | Sort out |
| **↑** | Later |
| **↓** or **Ctrl+Z** | Undo |
| **Space** | Play / pause video |
| **+ / −** or **mouse wheel** | Zoom in / out |
| **0** | Fit to window |
| **1** | Original size (100 %) |
| **Drag** | Move a zoomed image |
| **Double-click** | Switch between 100 % and fit |

- **Fit to window:** small images are reliably enlarged to the window size – also after resizing the window. Can be switched off (then at most original size).
- **Always visible:** full path, source, dimensions and date, plus **Show in folder**, **Copy path** and **Open with default app**.
- **Where to search:** your user folder, **all drives** (system folders are skipped) or **folders you choose**. Hidden files are found by the dot *and* by the Windows “hidden” attribute.
- **Videos** (MP4, MOV, MKV, WebM, 3GP, AVI) play inside the app; **HEIC/AVIF** photos open too.

### Install on a computer

- **Windows:** download **`SwipeScout.msi`** from [Releases](https://github.com/hyperflux22/SwipeScout/releases/latest) and open it. Windows may show “Windows protected your PC” – click **More info → Run anyway** (the installer is not signed with a paid certificate).
- **Mac (Apple Silicon, M1 or newer):** download **`SwipeScout.dmg`**, open it and drag **Swipe Scout** into **Applications**. On first start: **right-click the app → Open → Open** (or System Settings → Privacy & Security → “Open anyway”).

### Updates

On first start, the app asks whether it may look for updates. If yes, it checks the public repository briefly at every start; nothing about you is sent.
- **Windows & Mac:** “New version available” → **Update now** – the app downloads, installs and restarts itself.
- **Android:** “New version available” → **Update now** – the app downloads the new version and opens the Android installer; tap **Install** once, then **Open**. (Android does not allow apps outside the Play Store to replace themselves without this one tap.)

## Install

1. **[Download SwipeScout.apk](https://github.com/hyperflux22/SwipeScout/releases/latest/download/SwipeScout.apk)** – ideally right on your phone.
2. Open the file. Android asks whether to allow **apps from unknown sources** → allow it for your browser or file manager.
3. Tap **Install**.
4. Open Swipe Scout → **Allow access** → turn on **“Access to all files”** → go back.

> [!NOTE]
> Access to all files is required so the app can also find hidden folders and files with a wrong extension.

## How it works

| Gesture / button | Meaning |
|---|---|
| ⬅️ **swipe left** | **Keep** – the file stays as it is |
| ➡️ **swipe right** | **Sort out** – goes to “Sorted out” |
| ⬆️ **swipe up** | **Later** – when you are not sure yet |
| ↩️ **Undo** | Reverts the last decision |
| 👆👆 **double tap** | View the file large (videos with controls) |
| 🔇 / 🔊 **speaker at the top** | Sound for auto-playing videos – remembered |
| 🎛️ **sliders at the top** | Filter, sort order and smart search |
| ⋮ **menu at the top** | Scan again, trash, storage statistics, appearance, language |

Swiping **never** deletes anything. Only under **Sorted out** do you decide what happens – and even then everything goes to the **trash** first.

## All features

<details open>
<summary><b>🔍 Scan</b></summary>

- Choose at the top: **Everything**, **Photos only** or **Videos only**.
- Below, **Also search hidden photos** and/or **Also search hidden videos** appear.
- **More options:** skip very small files (under 20 KB, usually thumbnails or icons).
- Detection by **file content**: photos (JPEG, PNG, GIF, WebP, BMP, HEIC, AVIF) and videos (MP4, MOV, 3GP, MKV, WebM, AVI).
</details>

<details open>
<summary><b>👆 Sorting & 🔊 sound</b></summary>

- Large card with name, folder, format, size, source and **hidden**, **wrong extension**, **blurry** labels.
- **Videos play automatically** in a loop and are swiped the same way.
- Speaker at the top right: **crossed out** by default (sound off). Tap → sound on, remembered.
</details>

<details open>
<summary><b>🎛️ Filter, sort order & smart search</b></summary>

Everything is always scanned – the filter only decides what is shown, in every view.

| Group | Options |
|---|---|
| Hidden | Hidden & visible · Hidden only · Not hidden only |
| Type | Photos & videos · Photos only · Videos only |
| Source | Camera · Screenshots · WhatsApp · Telegram · Instagram · Snapchat · Facebook · Downloads · Bluetooth · Pictures · Movies · App folders · Thumbnails · Other |
| Sort order | **Standard (newest first)** · Largest first · Smallest first · Oldest first |
| Smart search | **Duplicate files** · **Similar photos** · **Blurry photos** |
| Special | Only files with a wrong extension |

- **Duplicate files:** exactly the same content (checksum), even with a different name, folder or extension.
- **Similar photos:** burst shots and near-identical pictures.
- **Blurry photos:** shaky or out-of-focus pictures.
- Groups are numbered (#1, #2 …). **“Pick automatically”** keeps the best file of each group and sorts out the rest.
- The analysis runs once and is saved – next time it is instant.
</details>

<details open>
<summary><b>🗂️ Sorted out – what you can do with the files</b></summary>

| Action | What happens |
|---|---|
| 🗑️ **Trash** | Can be restored until the time limit runs out |
| 📁 **Move** | To the folder `Pictures/SwipeScout` |
| 📋 **Copy to folder…** | Any folder, SD card or USB stick – the originals stay |
| 🗜️ **Save as ZIP…** | Pack all files into one ZIP file and save it wherever you want |
| 📤 **Share…** | Send via messenger, e-mail or cloud |
| 💚 **Keep after all** | Back to “Kept” |
| ⛔ **Delete permanently** | Without the trash, with confirmation |
</details>

<details open>
<summary><b>♻️ Trash</b></summary>

- Deleted files go to a hidden folder and do not show up in any gallery.
- Every file shows how long it stays. **Restore** or **delete permanently**, one by one or all at once.
- **Delete automatically after:** 5, 10, 20 or 30 days, 1, 2 or 3 months – or **custom** in hours, days, weeks or months.
</details>

<details open>
<summary><b>📊 Storage statistics</b></summary>

- Total size, **space freed up so far**, sorted-out files and trash.
- Bars by type (photos, videos, hidden) and by source (camera, WhatsApp …).
</details>

## Languages & appearance

- **Language:** follows your phone automatically. Change it via ⋮ → Language (or, on Android 13+, in Android Settings).
  🇬🇧 English · 🇩🇪 Deutsch · 🇪🇸 Español · 🇫🇷 Français · 🇮🇹 Italiano · 🇵🇹 Português · 🇳🇱 Nederlands · 🇵🇱 Polski · 🇹🇷 Türkçe · 🇷🇺 Русский
- **Appearance:** follows your **phone’s light/dark mode** by default. Set it to **Light** or **Dark** via ⋮ → Appearance.

<p align="center">
  <img src="docs/screenshots/en/light/02-sort.png" width="260">&nbsp;&nbsp;&nbsp;
  <img src="docs/screenshots/en/dark/02-sort.png" width="260">
</p>

## Privacy & safety

- 📴 **Offline by default.** The app only goes online for the update check – and only if you allowed it on first start. Nothing about you or your files is sent.
- 🚫 **No ads, no tracking, no account.**
- 🗑️ **Nothing is deleted without you.** Swiping only marks files; deleting goes to the trash first.

## FAQ

<details>
<summary><b>Why does the app find more photos than my gallery?</b></summary>

Gallery apps only show files Android knows as images. Hidden folders, folders with `.nomedia`
and files with a wrong extension are missing there. Swipe Scout reads the first bytes of each file to detect the real format.
</details>

<details>
<summary><b>Can I break hidden images of other apps?</b></summary>

Only if you delete or move them. Swipe Scout never renames files and changes nothing while you just swipe.
Files in the trash can be put back where they were.
</details>

<details>
<summary><b>When is the trash emptied?</b></summary>

Expired files are deleted when you open the app. If you do not open it for a long time, they stay a bit longer.
</details>

<details>
<summary><b>Why is the <code>Android/data</code> folder not included?</b></summary>

Since Android 11, Android no longer allows any app to access this folder.
</details>

## Versions

| Version | What's new |
|---|---|
| **4.0** | **Windows & Mac version**, arrow keys, zoom and fit-to-window; update check with “Update now” on all platforms |
| 3.2 | Maintenance, no visible changes |
| 3.1 | New app icon, “About” with link, labels no longer cut off |
| **3.0** | Trash with adjustable time limit, duplicate/similar/blurry photos, sort order, storage statistics, light/dark |
| 2.1 | Android 16, fixed the “x sorted out” bar |
| **2.0** | New name Swipe Scout, 10 languages, ZIP/copy/share |
| 1.2 | Clearer interface, sound switch, scan choice |
| 1.1 | Videos, filter by source |
| **1.0** | First version |

Big changes raise the first number (2.0 → 3.0), small ones the second (3.0 → 3.1).
Details in the [changelog](CHANGELOG.md), every version as an APK under
[Releases](https://github.com/hyperflux22/SwipeScout/releases).

## How the app is built

```mermaid
flowchart LR
    A[Phone storage] -->|Scan: content, not extension| B[All photos & videos]
    B -->|Filter, sort order, smart search| C[View]
    C -->|left| D[Keep]
    C -->|up| E[Later]
    C -->|right| F[Sorted out]
    F --> G[(Trash)]
    F --> H[Move · Copy · ZIP · Share]
```


## License

Swipe Scout is **free to use**. You may pass the app on **unchanged and free of charge**, with a note that it comes
from Swipe Scout by hyperflux22. Changing it, selling it or using it for harmful purposes is **not allowed**.
All details: [LICENSE](LICENSE) · [German translation](LICENSE.de.md).

## Feedback & support

Found a bug or have an idea? [Open an issue](https://github.com/hyperflux22/SwipeScout/issues/new/choose) – in English or German.

<sub>Sample photos in the screenshots: <a href="https://picsum.photos">Lorem Picsum</a> / Unsplash.</sub>
