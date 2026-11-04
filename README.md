<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/lemcad-logo-on-dark.svg">
  <img alt="LemCAD by Lemery Designs" src="assets/lemcad-logo.svg" width="520">
</picture>

**Professional parametric CAD, redesigned for people who build things.**

[Download for Windows](https://lemerydesigns.com/lemcad) · [Releases](https://github.com/BuiltByLegacy/LemCAD/releases) · [Lemery Designs](https://lemerydesigns.com)

</div>

> **Early preview.** LemCAD is in active development. The current Windows release is a preview, not a production-qualified CAD system. Check exported geometry in qualified software before using it for manufacturing.

## What is LemCAD?

LemCAD is a Windows desktop parametric 3D CAD application from **Lemery Designs**. It aims to make serious mechanical design feel clear and approachable while keeping an editable feature history and engineering accuracy. Reliable geometry and file handling come before feature count.

LemCAD is not affiliated with or endorsed by Siemens, PTC, Autodesk or Dassault Systèmes.

## What you can do in the current preview

| Area | What works |
| --- | --- |
| Sketching | Lines, arcs, rectangles, circles and points on datum planes or flat faces; automatic horizontal/vertical constraints; dimensions; snapping to the sketch origin and existing points |
| Features | Extrude, Revolve, Hole, Edge Blend and Pattern, with live preview |
| Editing | Part Navigator with double-click to edit, suppress, roll back, rename and delete; undo and redo |
| Files | Save and reopen LemCAD part files (`.lcad`) |
| Export | STEP and STL |
| Navigation | Mouse (middle button) and laptop touchpad controls, below |

Assemblies, drawings, GD&T/PMI, simulation and CAM are on the roadmap and are not in current builds.

## Install on Windows

1. Go to **[lemerydesigns.com/lemcad](https://lemerydesigns.com/lemcad)** and choose **Download for Windows**. It always gives you the newest stable release from this repository.
2. Run `LemCAD-Setup-x64-<version>.exe`.
3. The installer is not code-signed yet, so Windows may show **"Windows protected your PC"**. Choose **More info**, then **Run anyway**. Only do this for installers downloaded from the website or this repository's Releases page.
4. Start LemCAD from the Start menu or the desktop shortcut.

Each release includes `SHA256SUMS.txt`. To check your download, run this in PowerShell from your Downloads folder and compare the result:

```powershell
(Get-FileHash .\LemCAD-Setup-x64-<version>.exe).Hash
```

To update, download and run the newest installer; it replaces the installed version and keeps your part files.

**Requirements:** 64-bit Windows 10 or 11 with a working OpenGL graphics driver. These are early targets, not a tested compatibility list.

## Moving around the 3D view

| With a mouse | With a laptop touchpad | Does |
| --- | --- | --- |
| Middle-button drag | Left-drag | Rotate around the point under the cursor |
| Shift + middle-drag | Shift + left-drag | Pan |
| Scroll wheel, or Ctrl + middle-drag | Two-finger scroll, pinch, or Ctrl + left-drag | Zoom |
| Middle-button double-click | View → Fit | Fit the part in the view |

A left click selects. In sketch mode the view stays flat on the sketch; rotating comes back when you choose **Finish**.

## Releases

See the [Releases page](https://github.com/BuiltByLegacy/LemCAD/releases) for every version, its release notes and checksums. The website download always points to the newest stable release; previews marked "Pre-release" are never offered there.

| Version | Highlights |
| --- | --- |
| **0.1.3** | Touchpad navigation: left-drag rotates, Shift pans, Ctrl zooms |
| 0.1.2 | View framing after sketches and edits, exact origin snap, file dialogs open in your part's folder, Hole and Part Navigator fixes |
| 0.1.1 | First working public preview |
| 0.1.0 | Withdrawn: the installer could fail to start |

## Support and feedback

For questions, use the [Lemery Designs website](https://lemerydesigns.com/lemcad). Please do not post proprietary models, customer files, passwords or other confidential information in public GitHub issues.

## Privacy

LemCAD works locally: your parts stay on your computer and are never uploaded. From version 0.1.4, LemCAD reads this repository's public release list at startup to tell you when a newer version is available; it sends nothing about you or your parts. This repository contains release notes and approved installers only.

---

<div align="center">

**LemCAD** by [Lemery Designs](https://lemerydesigns.com) · *Custom Built. Engineered Right.*

</div>
