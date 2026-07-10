# Loopa Assets

Static screenshot assets for **Loopa** — a curated archive of useful websites, tools, and digital resources.

This repository stores optimized website preview images used inside the Loopa interface. Assets are served through jsDelivr CDN and referenced in the Loopa CMS.

## Structure

```txt
screenshots/
  thumbnails/
    example-thumbnail.webp
  fullpages/
    example-fullpage.webp
```

## CDN URL Format

Thumbnail:

```txt
https://cdn.jsdelivr.net/gh/thisisbremlo/loopa-assets@main/screenshots/thumbnails/example-thumbnail.webp
```

Fullpage screenshot:

```txt
https://cdn.jsdelivr.net/gh/thisisbremlo/loopa-assets@main/screenshots/fullpages/example-fullpage.webp
```

## Asset Guidelines

* Use `.webp` format.
* Keep filenames lowercase and slug-based.
* Use `-thumbnail.webp` for card previews.
* Use `-fullpage.webp` for long page screenshots.
* Do not upload raw or unoptimized screenshots.
* Do not upload private, restricted, or login-only pages.

## Example

```txt
screenshots/thumbnails/tally-thumbnail.webp
screenshots/fullpages/tally-fullpage.webp
```

## Usage

These files are intended to be used only as visual previews inside Loopa.

The screenshots may contain third-party website designs, logos, text, trademarks, or brand assets. All rights to the original websites and brand materials remain with their respective owners.
