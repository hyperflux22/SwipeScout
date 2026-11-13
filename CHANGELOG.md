# Changelog

<p align="right"><b>English</b> · <a href="CHANGELOG.de.md">Deutsch</a></p>

All versions of Swipe Scout. The numbers follow this rule:

- **First number** (e.g. 2.0 → 3.0): big change – many new features or a new look.
- **Second number** (e.g. 2.0 → 2.1): small change – improvements and bug fixes.

Every version can be downloaded as an APK under [Releases](https://github.com/hyperflux22/SwipeScout/releases).

## 5.0 – Data Scout: 2 in 1

- **New: Data Scout.** One tap switches Swipe Scout (photos & videos) to Data Scout – the same app for **all files**:
  documents, PDFs, spreadsheets, presentations, archives, installers, disk images, music, voice messages, e-books …
  Files are recognized by their content (a PDF or ZIP without extension is found too).
- **What is the file for?** The sort view shows **path, name, last change, age and purpose** of every file
  (e.g. “Installer – usually not needed after installing”, “Cache – recreated automatically”) with a hint:
  usually safe to delete, check first or personal file.
- **Storage as blocks:** folders and files drawn as blocks as big as the space they take; open folders by tapping,
  or show blocks by file type.
- New filters: file type and **only safe to delete**; duplicate search works for all files.
- Path, age and purpose are now also shown for photos and videos.
- On Android, Windows and Mac. Downloads: `.apk`, `.msi`, `.exe`, `.dmg`.

## 4.1 – More download formats

- Windows: besides the **`SwipeScout.msi`** installer there is now also **`SwipeScout.exe`** (setup program).
- Mac: **`SwipeScout.dmg`** (Apple Silicon) is now part of every release.
- Every release contains `.apk` (Android), `.msi` and `.exe` (Windows) and `.dmg` (Mac).
- Smaller Windows installer (about 90 MB instead of 160 MB).

## 4.0 – Windows & Mac, updates

- **New: Swipe Scout for Windows and Mac** with all features of the phone app.
  - Sort with the **arrow keys** (← keep, → sort out, ↑ later, ↓ / Ctrl+Z undo).
  - **Fit to window** – small images are reliably enlarged to the window size (can be switched off); zoom with the
    mouse wheel or + / −, drag to move, double-click for 100 %.
  - Full path, source, dimensions and date always visible; **Show in folder**, **Copy path**, **Open with default app**.
  - Search the user folder, **all drives** or chosen folders; hidden files incl. the Windows “hidden” attribute.
  - Videos and HEIC/AVIF via a built-in player.
- **Update check** on Android, Windows and Mac: asks on first start; “New version available” → **Update now**.
  Windows/Mac install and restart automatically; Android opens the installer (one tap).
- Shared core for phone and computer (same detection, filters, duplicate search and trash).
- New sources: Desktop, Documents, Cloud (OneDrive, iCloud …).

## 3.2 – Maintenance

- Internal clean-up, no visible changes. Updates over 3.1 as usual.

## 3.1 – New icon, “About”, tidier labels

- **New app icon:** a photo card being swiped, on a blue gradient.
- **About Swipe Scout** in the menu ⋮: version, link to the website and downloads, report a bug or idea.
- The labels on a card (format, size, source, hidden …) now wrap onto a second line instead of being cut off.

## 3.0 – Trash, smart search, statistics, light/dark

- **Trash:** deleting moves files to the trash first; they can be restored.
  Time limit: 5/10/20/30 days, 1/2/3 months or custom (hours, days, weeks, months).
- **Smart search:** duplicate files, similar photos, blurry photos – with “Pick automatically”.
- **Sort order:** standard (newest first), largest, smallest, oldest first.
- **Storage statistics:** size by type and source, space freed up so far.
- **Appearance:** like the system (default), light or dark.
- **Menu ⋮:** scan again, trash, statistics, appearance, language.
- Small phones and large text: nothing wraps or gets cut off any more.

## 2.1 – Fixes

- Supports Android 16.
- “3 sorted out” no longer wraps onto several lines.
- The “Sort” tab shows the full number instead of “999+”.

## 2.0 – Swipe Scout

- **New name:** “Bilder” becomes “Swipe Scout”.
- **10 languages:** English, German, Spanish, French, Italian, Portuguese, Dutch, Polish, Turkish, Russian –
  follows the phone, changeable in the app.
- **New actions:** copy to a folder (also SD card/USB), save as ZIP, share, keep after all.
- Clearer wording: Keep / Later / Sort out.
- New README with screenshots in German and English.

## 1.2 – Clearer interface

- Speaker switch (off by default, remembered).
- Before scanning: Everything / Photos only / Videos only, each with “Also search hidden”.
- Filter in its own panel, active filters as chips.
- Progress bar, three big decision buttons, consistent dark design.

## 1.1 – Videos

- Finds videos (MP4, MOV, 3GP, MKV, WebM, AVI) and plays them automatically, also while swiping.
- Filter after scanning: hidden / not hidden, photos / videos, source (camera, WhatsApp …).
- “Scan again” button.

## 1.0 – First version

- Scans the whole storage, including hidden folders.
- Recognizes images by their content instead of their extension (also `.bng` or no extension).
- Swipe: left keep, right select, up later.
- Grid with check boxes; delete or move selected images.
