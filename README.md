# LUMIO Assets

A small, shared collection of HTML app modules and image files used by the LUMIO projects.

**Repository:** [dhisjwhd-svg/lumio-assets](https://github.com/dhisjwhd-svg/lumio-assets)  
**Main project:** [LUMIO-OS](https://github.com/dhisjwhd-svg/LUMIO-OS)

## Contents

| Path | What it contains |
|---|---|
| [`assets/apps/`](assets/apps/) | Standalone HTML app modules |
| [`assets/apps/directory/`](assets/apps/directory/) | Directory page and its linker page |
| [`images/apps/`](images/apps/) | App icons and artwork |
| [`images/branding/`](images/branding/) | Shared branding image |
| [`images/profiles/`](images/profiles/) | Profile pictures and banners |
| [`images/misc/`](images/misc/) | Miscellaneous image asset |

## HTML modules

| File | Purpose |
|---|---|
| [Netflix.html](assets/apps/Netflix.html) | Netflix-style app module |
| [Spotify.html](assets/apps/Spotify.html) | Spotify-style music interface |
| [Steam.html](assets/apps/Steam.html) | Steam-style gaming interface |
| [TFF.html](assets/apps/TFF.html) | The Forged Flowers profile page |
| [Directory.html](assets/apps/directory/Directory.html) | Directory interface |
| [linker.html](assets/apps/directory/linker.html) | Supporting directory-link page |

These files are web documents, not native applications. Embedded services, sign-in, playback, and other third-party behavior depend on the external service and browser restrictions.

## Image inventory

### App artwork
- [directory-icon.jpeg](images/apps/directory-icon.jpeg)
- [milkbox-icon.png](images/apps/milkbox-icon.png)
- [netflix-cover.jpg](images/apps/netflix-cover.jpg)
- [spotify-icon.jpg](images/apps/spotify-icon.jpg)

### Branding
- [kon-favicon.jpg](images/branding/kon-favicon.jpg)

### Profile and miscellaneous images
- [kirby-dvd.jpg](images/profiles/kirby-dvd.jpg)
- [moon-banner.png](images/profiles/moon-banner.png)
- [satoshiwizard-banner.jpeg](images/profiles/satoshiwizard-banner.jpeg)
- [satoshiwizard-pfp.jpeg](images/profiles/satoshiwizard-pfp.jpeg)
- [miscellaneous image](images/misc/fd0048fa0231ae5e790e8671faea2157.jpg)

## Using a file from a hosted page

Use the **raw GitHub URL** when you want a direct file response:

```text
https://raw.githubusercontent.com/dhisjwhd-svg/lumio-assets/main/images/apps/directory-icon.jpeg
```

For a CDN-style URL, use **jsDelivr**:

```text
https://cdn.jsdelivr.net/gh/dhisjwhd-svg/lumio-assets@main/images/apps/directory-icon.jpeg
```

Replace the path after `main/` with the file's path in this repository. For HTML modules, for example:

```text
https://cdn.jsdelivr.net/gh/dhisjwhd-svg/lumio-assets@main/assets/apps/Steam.html
```

The `main` branch URLs follow the latest committed version after the host's cache updates. For a stable, version-pinned URL, replace `@main` with a commit hash or release tag. CDN caching can mean a recent change is not visible immediately.

## Maintenance notes

- Keep file paths and capitalization consistent; hosted paths are case-sensitive.
- When renaming or moving an asset, update every page that references its old path.
- Keep app modules and image resources in their existing folders so current links continue to work.
- Prefer descriptive filenames for new assets instead of camera-generated names where the asset's purpose is known.

---

This repository is the asset and module source. Project-level desktop setup and usage belong in the [LUMIO-OS repository](https://github.com/dhisjwhd-svg/LUMIO-OS).
