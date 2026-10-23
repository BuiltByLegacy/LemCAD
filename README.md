<div align="center">

![LemCAD interim brand wordmark](assets/lemcad-brand-placeholder.svg)

# LemCAD

**Professional CAD, redesigned for people who build things.**

**Precise modeling. Thoughtful workflows. Built for real engineering.**

[Website](https://lemerydesigns.com/lemcad) · [Windows downloads](https://lemerydesigns.com/lemcad/download) · [Public releases](https://github.com/BuiltByLegacy/LemCAD/releases)

</div>

> **EARLY DEVELOPMENT · No approved public installer yet.** A Windows installer candidate has passed an automated GitHub Actions run in the private development repository, but independent installation and CAD-workflow qualification remain release gates. The links above will offer an installer when the owner explicitly publishes a verified stable release.

## What is LemCAD?

LemCAD is an independent, Windows-focused parametric 3D CAD application in development by **BuiltByLegacy / Lemery Designs**. It aims to make serious mechanical design feel clear, approachable and responsive while retaining editable model history and engineering accuracy.

Our direction is a modern light/dark desktop modeling workspace with a feature navigator, contextual sketch tools, floating command dialogs and predictable selection/edit behavior. **Reliable geometry and file handling come before feature count.** LemCAD is not affiliated with or endorsed by Siemens, PTC, Autodesk or Dassault Systèmes.

## What works today, and what is planned?

The private codebase includes a functional **prototype**, not a qualified public product.

| Area | Current status |
| --- | --- |
| Windows desktop GUI, 3D viewport and Part Navigator | Prototype |
| Sketch, basic feature modeling and Extrude | Prototype; undergoing workflow validation |
| Editable history, selected feature commands and undo | Early implementation / tests continuing |
| Prototype project save and reopen | Available in development; not production-qualified |
| STEP/STL export paths | In development; independently verify geometry |
| Windows installer and desktop shortcut | Candidate build pipeline; clean-machine validation required |
| Light/dark workspace and polished floating dialogs | Design approved; implementation in progress |
| In-app bug/suggestion reporting | Local prototype; sending and recording not yet released |
| In-app update prompt, release notes and relaunch | Planned, not active |
| Assembly depth, drawings, GD&T/PMI, simulation, CAM and optional AI | Roadmap; not promised for current builds |

**Engineering safety:** Do not rely on this prototype as the sole record for released production designs, regulated/safety-critical geometry, or customer manufacturing deliverables. Validate exported geometry in qualified software.

## Install LemCAD on Windows

**When an approved installer is available:**

1. Visit **[lemerydesigns.com/lemcad](https://lemerydesigns.com/lemcad)**.
2. Select **Download for Windows** to retrieve the latest approved stable installer from this repository's GitHub Releases. No GitHub account, Git checkout, Python or command prompt will be needed by end users.
3. Run the versioned `LemCAD-Setup-x64-<version>.exe` (early candidates may retain the name `LemeryCAD-Setup-x64-<version>.exe`).
4. Launch from the desktop shortcut or Windows Start menu.

**At present, no public installer is published.** Only download from the official website or this repository's verified Releases page. An unsigned early build may trigger a Windows reputation warning; code signing is a planned public-release gate. Never turn off device security to install an untrusted build.

## System requirements (provisional)

Hardware targets have **not** yet been established by a full benchmark matrix. The current prototype targets **64-bit Windows with supported GPU/OpenGL drivers**.

| Component | Early research target — not a verified minimum |
| --- | --- |
| OS | Windows 10/11 x64; final supported builds to be confirmed |
| CPU | Modern 4-core or better |
| RAM | 8 GB exploratory entry target; 16–32 GB preferred for testing |
| Graphics | Working OpenGL-capable integrated/discrete GPU and current driver |
| Storage | SSD recommended; final installer footprint under measurement |
| Display | 1920 × 1080 recommended for current workspace |

The future **System Advisor** is intended to check PC capabilities and recommend reversible viewport settings without changing geometry accuracy. These numbers are planning targets, **not compatibility guarantees**.

## Version numbers and releases

Every approved release will have an immutable version tag, named installer, checksum and human-readable release notes.

| Version example | Meaning | Availability |
| --- | --- | --- |
| `v0.1.0` | Initial alpha milestone / current internal package version | **Not publicly released** |
| `v0.1.1` | Compatible bug-fix release | Example only |
| `v0.2.0` | Compatible feature release | Example only |
| `v0.2.0-beta.1` | Test preview, intentionally excluded from stable downloads | Example only |
| `v1.0.0` | Future major stable milestone | Not announced |

- **Public releases require explicit owner approval.** Passing CI, pushing code, or creating a private installer does **not** publish a public release.
- **Stable website downloads** select the latest approved published stable release, not alpha/beta previews.
- **What's new** appears in the GitHub Release description, with highlights, fixes, known issues, and compatibility notes.
- Planned **in-app update notifications** will present version changes and release notes before users choose **Update & Relaunch**. **The updater is not implemented yet.**
- Each approved installer will include SHA-256 verification information. Production-wide distribution also requires signing and upgrade testing.

### Release notes format

```text
LemCAD vX.Y.Z — YYYY-MM-DD
Channel: Stable / Beta / Alpha
Highlights:
- ...
Fixes:
- ...
Known issues:
- ...
Compatibility / migration notes:
- ...
Windows installer: LemCAD-Setup-x64-X.Y.Z.exe
SHA-256: <published digest>
```

See the [Releases page](https://github.com/BuiltByLegacy/LemCAD/releases) for **actual shipped versions**. If it is empty, no public version has been released.

## Product direction

1. **Foundation** — sketch → solid → edit → save/reopen → export, repeatably tested.
2. **Professional workspace** — polished contextual UI, navigators, selection, floating dialogs and dual themes.
3. **Parametric depth** — more robust constraints, geometry regeneration, expressions and error recovery.
4. **Engineering workflows** — assemblies, drawings, PMI/GD&T and manufacturability.
5. **Extensibility** — optional manufacturing integrations and AI assistance **after** core CAD reliability.

Roadmap items are goals, not contractual features or release-date promises.

## Support, bugs and suggestions

Feedback tools are in development. Please do **not** post proprietary models, customer CAD files, sensitive screenshots, passwords, license information, or confidential engineering work in public GitHub issues.

For general public questions, use the [Lemery Designs website](https://lemerydesigns.com/lemcad). An in-app **Feedback** flow is planned with opt-in, sanitized diagnostics and user-controlled attachments; continuous video recording and uploads are **not currently enabled**.

## Privacy and security

LemCAD is being built around a **local-first** CAD workflow. A future update check may access approved public release metadata, but optional diagnostics and content sharing must require clear consent. CAD projects should never be silently uploaded as part of feedback or update checks.

The public repository contains **release documentation and owner-approved distributable binaries only**. Private source code, signing credentials, internal issue trackers, private engineering work and customer diagnostic reports are **not published here**.

## Branding

The current README banner is an **interim identity**, using the approved **Precision Coral** (`#EF634F`) and **Midnight Navy** (`#17212B`) brand direction. The final LemCAD logo and naming clearance have **not** been signed off. Final branding may replace this graphic.

---

<div align="center">

**LemCAD** · Built by Legacy · [Lemery Designs](https://lemerydesigns.com)

*Custom Built. Engineered Right.*

</div>
