# LUMIO Assets

Shared app modules and image assets for [LUMIO-OS](https://github.com/dhisjwhd-svg/LUMIO-OS).

## Repository layout

```text
assets/
└── apps/
    ├── Netflix.html
    ├── Spotify.html
    ├── Steam.html
    ├── TFF.html
    └── directory/
        ├── Directory.html
        └── linker.html
images/
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
    └── moon-banner.png
```

## App modules

| File | Purpose |
| --- | --- |
| `assets/apps/Netflix.html` | Netflix-style video interface |
| `assets/apps/Spotify.html` | Spotify-style music interface |
| `assets/apps/Steam.html` | Steam-style game launcher |
| `assets/apps/TFF.html` | The Forged Flowers / Moon profile |
| `assets/apps/directory/Directory.html` | Directory interface |
| `assets/apps/directory/linker.html` | Shared directory link data |

## Asset groups

- **`images/apps/`** — app icons and tile artwork.
- **`images/branding/`** — desktop branding and favicon assets.
- **`images/profiles/`** — profile avatar and banner artwork.
- **`images/misc/`** — retained image whose purpose is not yet established.

## Using the files

LUMIO-OS loads these files from GitHub's raw-content host, with jsDelivr as a fallback where configured. When moving or renaming files, update every URL that references the old path in the same change.

Example raw URL:

```text
https://raw.githubusercontent.com/dhisjwhd-svg/lumio-assets/main/assets/apps/Netflix.html
```

Keep filenames and paths case-sensitive. The HTML app files are large, self-contained modules, so keep each app together unless its code is deliberately refactored to use separate CSS, JavaScript, or data files.
