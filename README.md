<p align="center">
  <img src="https://cdn.jsdelivr.net/gh/dhisjwhd-svg/lumio-assets@main/images/branding/kon-favicon.jpg" alt="LUMIO assets project mark" width="100">
</p>

<h1 align="center">LUMIO Assets</h1>

<p align="center">
  Shared app modules, profile artwork, branding, and image resources for
  <a href="https://github.com/dhisjwhd-svg/LUMIO-OS">LUMIO-OS</a>.
  <br>
  <a href="https://github.com/dhisjwhd-svg/LUMIO-OS/blob/main/main.html"><strong>Open LUMIO-OS</strong></a>
  ·
  <a href="https://github.com/dhisjwhd-svg/lumio-assets/tree/main/assets/apps">Browse app modules</a>
  ·
  <a href="https://github.com/dhisjwhd-svg/lumio-assets/tree/main/images">Browse images</a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/content-HTML%20modules-111827?style=flat-square" alt="HTML modules">
  <img src="https://img.shields.io/badge/assets-images%20%26%20profiles-111827?style=flat-square" alt="Images and profiles">
  <img src="https://img.shields.io/badge/delivery-GitHub%20%2B%20jsDelivr-111827?style=flat-square" alt="GitHub and jsDelivr delivery">
</p>

---

## About this repository

This repository stores the separate app pages and image files used by LUMIO-OS. Keeping these resources separate from the desktop shell makes it easier to maintain app experiences, reuse artwork, and update individual modules without putting every large HTML file into the main desktop document.

It contains five main app experiences, a directory link source, app artwork, branding, and profile images. The modules are web pages, not native desktop programs.

## App gallery

<table>
  <tr>
    <td align="center" width="25%">
      <a href="https://github.com/dhisjwhd-svg/lumio-assets/blob/main/assets/apps/Netflix.html">
        <img src="https://cdn.jsdelivr.net/gh/dhisjwhd-svg/lumio-assets@main/images/apps/netflix-cover.jpg" alt="Netflix module artwork" width="150">
      </a>
      <br><strong>Netflix</strong>
      <br><sub>Video-library interface</sub>
      <br><a href="https://github.com/dhisjwhd-svg/lumio-assets/blob/main/assets/apps/Netflix.html">Open module</a>
    </td>
    <td align="center" width="25%">
      <a href="https://github.com/dhisjwhd-svg/lumio-assets/blob/main/assets/apps/Spotify.html">
        <img src="https://cdn.jsdelivr.net/gh/dhisjwhd-svg/lumio-assets@main/images/apps/spotify-icon.jpg" alt="Spotify module artwork" width="150">
      </a>
      <br><strong>Spotify</strong>
      <br><sub>Music and library interface</sub>
      <br><a href="https://github.com/dhisjwhd-svg/lumio-assets/blob/main/assets/apps/Spotify.html">Open module</a>
    </td>
    <td align="center" width="25%">
      <a href="https://github.com/dhisjwhd-svg/lumio-assets/blob/main/assets/apps/Steam.html">
        <img src="https://cdn.simpleicons.org/steam/FFFFFF" alt="Steam logo" width="150">
      </a>
      <br><strong>Steam</strong>
      <br><sub>Game catalogue</sub>
      <br><a href="https://github.com/dhisjwhd-svg/lumio-assets/blob/main/assets/apps/Steam.html">Open module</a>
    </td>
    <td align="center" width="25%">
      <a href="https://github.com/dhisjwhd-svg/lumio-assets/blob/main/assets/apps/directory/Directory.html">
        <img src="https://cdn.jsdelivr.net/gh/dhisjwhd-svg/lumio-assets@main/images/apps/directory-icon.jpeg" alt="Directory module artwork" width="150">
      </a>
      <br><strong>Directory</strong>
      <br><sub>Terminal-style link directory</sub>
      <br><a href="https://github.com/dhisjwhd-svg/lumio-assets/blob/main/assets/apps/directory/Directory.html">Open module</a>
    </td>
  </tr>
</table>

## App documentation

### Netflix

**File:** [`assets/apps/Netflix.html`](https://github.com/dhisjwhd-svg/lumio-assets/blob/main/assets/apps/Netflix.html)

A video-library experience with title discovery, series and episode views, and a collection/library workflow.

- **Who's watching? / profiles** — enter through a profile-selection screen and manage profiles through the available controls.
- **All titles** — browse the available title catalogue.
- **Title details** — open a title's information view before playing.
- **Play and playback actions** — use Play, Play next, previous/next episode navigation, retry, and alternate-source controls when offered by the selected content.
- **Episodes** — open episode lists for supported series.
- **Continue Playing** — return to titles surfaced in the continue-playing area.
- **My List** — add titles to or remove titles from the saved list.
- **Your Netflix library / My library** — access the app's library views.
- **Import Modules** — load an HTML module using the import interface, inspect the available module, or remove imported modules.
- **Source controls** — retry playback, try another source, or open a source when those actions are available.

The interface does not guarantee that every title or stream will play. Playback depends on the configured content sources, imported modules, network access, and browser restrictions.

### Spotify

**File:** [`assets/apps/Spotify.html`](https://github.com/dhisjwhd-svg/lumio-assets/blob/main/assets/apps/Spotify.html)

A music-oriented interface centered on a personal library.

- **Your Library** — view the library area.
- **Add songs** — use the add-songs control to bring supported music content into the interface.
- **Clear library** — clear the current library entries.

The module's interface does not bypass official Spotify authentication, subscriptions, licensing, or access restrictions. Playback and available content depend on what the current module supports.

### Steam

**File:** [`assets/apps/Steam.html`](https://github.com/dhisjwhd-svg/lumio-assets/blob/main/assets/apps/Steam.html)

A Steam-inspired game catalogue for browsing and launching supported web game entries.

- **Featured** — browse the featured catalogue area.
- **Play Now / Play** — open a supported game entry.
- **Favorite** — mark catalogue entries for quick reference.
- **Load more** — request additional catalogue entries when available.
- **History** — clear the app's saved browsing/play history.
- **Back** — return from a game view to the catalogue.
- **Retry / Refresh** — try loading a page or game again after a failure.

Games can fail to launch if a source is offline, a path is invalid, required assets are missing, or the browser blocks embedded content. This module is not the official Steam client and does not provide access to a user's Steam account or paid library by itself.

### Directory

**File:** [`assets/apps/directory/Directory.html`](https://github.com/dhisjwhd-svg/lumio-assets/blob/main/assets/apps/directory/Directory.html)

A terminal-styled directory for organizing and opening website links.

- **Enter Terminal / Open Directory** — enter the directory interface.
- **Load Directory** — load the directory data source.
- **Logbook** — access the logbook view.
- **Verified Entries** — filter or view entries marked as verified within the app.
- **Field Guide** — read guidance for using the directory and managing entries.
- **Register Site** — submit a site name, website address, and category.
- **Quarantine / Flagged Entries** — separate entries that have been flagged.
- **Reinstate** — return a quarantined entry to the active directory when appropriate.
- **Move to notes** — retain an entry in notes instead of the active list.
- **Export Directory** — export directory data.
- **Purge Quarantine** — clear quarantined entries.

“Verified” is an internal directory label, not a security guarantee. Check website addresses before opening them and avoid entering private information into unfamiliar sites.

### Directory link source

**File:** [`assets/apps/directory/linker.html`](https://github.com/dhisjwhd-svg/lumio-assets/blob/main/assets/apps/directory/linker.html)

A companion HTML data source containing directory link entries, separate from the main Directory interface. Keep this file available when the Directory module expects to load its shared link data.

### The Forged Flowers / moon.d.flower profile

**File:** [`assets/apps/TFF.html`](https://github.com/dhisjwhd-svg/lumio-assets/blob/main/assets/apps/TFF.html)

A standalone, Discord-inspired profile page for **moon.d.flower**. It provides a profile-focused presentation rather than a general desktop utility. The profile page and its artwork are hosted independently from the main LUMIO-OS desktop.

## Image gallery

### App artwork

<box align="center">
  <table>
    <tr>
      <td align="center">
        <img src="https://cdn.jsdelivr.net/gh/dhisjwhd-svg/lumio-assets@main/images/apps/netflix-cover.jpg" alt="Netflix cover artwork" width="180">
        <br><strong>Netflix cover</strong>
        <br><code>images/apps/netflix-cover.jpg</code>
      </td>
      <td align="center">
        <img src="https://cdn.jsdelivr.net/gh/dhisjwhd-svg/lumio-assets@main/images/apps/spotify-icon.jpg" alt="Spotify icon artwork" width="180">
        <br><strong>Spotify icon</strong>
        <br><code>images/apps/spotify-icon.jpg</code>
      </td>
    </tr>
    <tr>
      <td align="center">
        <img src="https://cdn.jsdelivr.net/gh/dhisjwhd-svg/lumio-assets@main/images/apps/directory-icon.jpeg" alt="Directory icon artwork" width="180">
        <br><strong>Directory icon</strong>
        <br><code>images/apps/directory-icon.jpeg</code>
      </td>
      <td align="center">
        <img src="https://cdn.jsdelivr.net/gh/dhisjwhd-svg/lumio-assets@main/images/apps/milkbox-icon.png" alt="MilkBox icon artwork" width="180">
        <br><strong>MilkBox icon</strong>
        <br><code>images/apps/milkbox-icon.png</code>
      </td>
    </tr>
  </table>
</box>

### Branding

<p align="left">
  <img src="https://cdn.jsdelivr.net/gh/dhisjwhd-svg/lumio-assets@main/images/branding/kon-favicon.jpg" alt="LUMIO project branding mark" width="120">
</p>

- **Project mark / favicon:** [`images/branding/kon-favicon.jpg`](https://github.com/dhisjwhd-svg/lumio-assets/blob/main/images/branding/kon-favicon.jpg)

### Profile artwork

<table>
  <tr>
    <td align="center" width="50%">
      <img src="https://cdn.jsdelivr.net/gh/dhisjwhd-svg/lumio-assets@main/images/profiles/moon-banner.png" alt="moon.d.flower profile banner" width="360">
      <br><strong>moon.d.flower banner</strong>
      <br><code>images/profiles/moon-banner.png</code>
    </td>
    <td align="center" width="50%">
      <img src="https://cdn.jsdelivr.net/gh/dhisjwhd-svg/lumio-assets@main/images/profiles/satoshiwizard-banner.jpeg" alt="Satoshi Wizard profile banner" width="360">
      <br><strong>Satoshi Wizard banner · profile 002</strong>
      <br><code>images/profiles/satoshiwizard-banner.jpeg</code>
    </td>
  </tr>
  <tr>
    <td align="center">
      <img src="https://cdn.jsdelivr.net/gh/dhisjwhd-svg/lumio-assets@main/images/profiles/kirby-dvd.jpg" alt="Kirby DVD-style profile artwork" width="180">
      <br><strong>Kirby DVD artwork</strong>
      <br><code>images/profiles/kirby-dvd.jpg</code>
    </td>
    <td align="center">
      <img src="https://cdn.jsdelivr.net/gh/dhisjwhd-svg/lumio-assets@main/images/profiles/satoshiwizard-pfp.jpeg" alt="Satoshi Wizard profile picture" width="180">
      <br><strong>Satoshi Wizard profile picture</strong>
      <br><code>images/profiles/satoshiwizard-pfp.jpeg</code>
    </td>
  </tr>
</table>

The profile artwork files are reusable assets. A page only displays an image when its HTML references the corresponding path or URL.

### Miscellaneous image

- [`images/misc/fd0048fa0231ae5e790e8671faea2157.jpg`](https://github.com/dhisjwhd-svg/lumio-assets/blob/main/images/misc/fd0048fa0231ae5e790e8671faea2157.jpg) — retained image asset; its specific role is not documented yet.

## Repository layout

```text
lumio-assets/
├── README.md
├── assets/
│   └── apps/
│       ├── Netflix.html
│       ├── Spotify.html
│       ├── Steam.html
│       ├── TFF.html
│       └── directory/
│           ├── Directory.html
│           └── linker.html
└── images/
    ├── apps/
    │   ├── directory-icon.jpeg
    │   ├── milkbox-icon.png
    │   ├── netflix-cover.jpg
    │   └── spotify-icon.jpg
    ├── branding/
    │   └── kon-favicon.jpg
    ├── misc/
    │   └── fd0048fa0231ae5e790e8671faea2157.jpg
    └── profiles/
        ├── kirby-dvd.jpg
        ├── moon-banner.png
        ├── satoshiwizard-banner.jpeg
        └── satoshiwizard-pfp.jpeg
```

## Using and hosting these assets

The modules can be opened directly from GitHub or served as raw files. LUMIO-OS uses hosted module URLs and can use GitHub Raw or jsDelivr depending on the loader configuration.

**GitHub Raw example**

```text
https://raw.githubusercontent.com/dhisjwhd-svg/lumio-assets/main/assets/apps/Netflix.html
```

**jsDelivr example**

```text
https://cdn.jsdelivr.net/gh/dhisjwhd-svg/lumio-assets@main/assets/apps/Netflix.html
```

**Image example**

```text
https://cdn.jsdelivr.net/gh/dhisjwhd-svg/lumio-assets@main/images/apps/netflix-cover.jpg
```

### Maintenance notes

- **Paths are case-sensitive.** Preserve exact names such as `Netflix.html`, `Spotify.html`, and `Steam.html`.
- **Update references when renaming files.** Search both repositories for the previous path before removing or renaming an asset.
- **Keep app dependencies together.** These HTML modules are substantial self-contained files. Avoid moving their CSS, JavaScript, or data into separate files unless their loading logic is updated at the same time.
- **Use stable URLs.** If a desktop app references a raw or jsDelivr URL, make sure the referenced path exists on the default branch.
- **External content can change.** Embedded sites, game sources, and media services may block framing or stop working independently of this repository.

## Related links

- [LUMIO-OS repository](https://github.com/dhisjwhd-svg/LUMIO-OS)
- [Launch LUMIO-OS](https://github.com/dhisjwhd-svg/LUMIO-OS/blob/main/main.html)
- [App modules](https://github.com/dhisjwhd-svg/lumio-assets/tree/main/assets/apps)
- [Image assets](https://github.com/dhisjwhd-svg/lumio-assets/tree/main/images)
- [moon.d.flower on TikTok](https://www.tiktok.com/@moon.d.flower)

---

<p align="center"><sub>LUMIO Assets · Shared modules and artwork for LUMIO-OS.</sub></p>
