<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/lemcad-logo-on-dark.svg">
  <img alt="LemCAD by Lemery Designs" src="assets/lemcad-logo.svg" width="520">
</picture>

# Professional CAD. Rethought.

**Modern, local-first parametric 3D design for engineers, makers, and manufacturers.**

[**Download for Windows**](https://lemerydesigns.com/lemcad) · [Releases & checksums](https://github.com/BuiltByLegacy/LemCAD/releases) · [Give feedback](https://lemerydesigns.com/lemcad)

**Windows · Early preview · Local-first**

</div>

> [!IMPORTANT]
> **LemCAD is an early preview, not production-qualified CAD.** Some tools are experimental and may produce incomplete or incorrect results. Independently validate geometry and exports in qualified software before using them for customer, safety-critical, or released manufacturing work. Release availability and exact features depend on the installer version; consult the published release notes.

## See LemCAD in action

LemCAD is built around an editable parametric model, a graphical modeling workspace, and an engineering-oriented feature history.

**Actual application screenshots and a Sketch → Extrude → Edit demonstration are being prepared.** We will add real captures from a verified Windows build, rather than mockups that imply unfinished features already work.

## Why LemCAD?

**Professional workflows, less friction.** Our goal is to make everyday mechanical design clear and precise, with discoverable commands and straightforward feature editing.

**One editable engineering model.** Work with sketches, dimensional constraints, and parametric features rather than making every change as a disconnected mesh operation.

**Designed to grow with making things.** The roadmap connects design to 3D printing, machining, fabrication, revisions, manufacturing instructions, and inspection.

**Local-first, engineer-controlled.** The desktop application is designed to keep CAD work under your control. Optional future integrations and AI features must respect permissions and confidentiality.

**Reliability before feature count.** A smaller collection of dependable commands is more valuable than a large collection of features that silently break designs.

## What can you do in the current preview?

These are **preview capabilities**, not independently certified production workflows. Verify behavior against the specific release you install.

| Area | Available in preview / known limitations |
| --- | --- |
| **3D modeling workspace** | Windows desktop viewport and Part Navigator; interaction and selection are still being refined |
| **Sketching** | Basic sketch geometry, dimensions, and early constraint workflows; not a complete professional sketch solver |
| **Parametric features** | Early Extrude, Revolve, Hole, Edge Blend, and Pattern workflows; test edits and downstream regeneration carefully |
| **Feature editing** | Feature-tree editing and selected undo/redo, suppression or rollback workflows; robustness is being qualified |
| **Native files** | LemCAD part save/reopen in development; retain separate backups of important work |
| **Interchange** | STEP and STL export paths; independently inspect exported dimensions, topology, and units |
| **Assemblies, drawings, GD&T/PMI, simulation, CAM, PLM** | Not qualified as current production capabilities; on the roadmap |
| **Live OrcaSlicer / Bambu Studio connection** | Planned, not part of the verified preview |
| **AI-assisted engineering and CAD Bridge** | Planned/research, not part of the verified preview |

For shipped fixes and exact version-specific behavior, see the [release notes](https://github.com/BuiltByLegacy/LemCAD/releases).

## Get started on Windows

1. Visit [**lemerydesigns.com/lemcad**](https://lemerydesigns.com/lemcad) or the [public Releases page](https://github.com/BuiltByLegacy/LemCAD/releases).
2. Choose the release appropriate for you. Check whether it is tagged **Pre-release** and read its limitations.
3. Download the Windows installer and its release checksum file where provided. Confirm the source, filename, version, and SHA-256 before running it.
4. Install and launch **LemCAD**. If Windows warns that a publisher is unverified, verify the file's origin and checksum and proceed only if you trust the installer; do not disable security protections indiscriminately.
5. Begin with a disposable test part rather than proprietary or production geometry.

**Windows target:** 64-bit Windows 10/11 with a functional OpenGL graphics driver. Hardware and operating-system compatibility are still being qualified.

### Your first five-minute model

1. Create a new part and open a sketch.
2. Draw a rectangle and apply dimensions.
3. Finish the sketch and try **Extrude**.
4. Edit a driving dimension and inspect whether the solid regenerates correctly.
5. Save, close, reopen, and test STEP or STL export.

If something fails, record the exact version, steps, expected outcome, and observed behavior. Do not assume an operation succeeded solely because the viewport displays a solid.

## Where we're going

| Pillar | Direction | Status |
| --- | --- | --- |
| **Professional parametric CAD** | Better constraints, robust topology, assemblies, drawings, and trustworthy regeneration | Active foundation + phased roadmap |
| **Engineering usability** | Selection, Part Navigator, live modeling handles, diagnostic recovery, NX-familiar workflows | Active design and phased implementation |
| **Connected manufacturing** | Print Studio, slicer links, process-specific manufacturability and engineering analysis | Planned |
| **Engineering intelligence** | Feature Doctor, optional AI, CAD migration, design intent and revision intelligence | Planned/research |

This is a **direction**, not a commitment to ship specific features by a particular date. Features graduate only after engineering and Windows validation.

### A future manufacturing workflow

Our goal is to connect an editable CAD design to a versioned manufacturing recipe, verified slicer output, and eventually inspection/production feedback. OrcaSlicer and Bambu Studio integration, load-path analysis across manufacturing methods, and revision-aware print comparisons are in the development backlog—not currently qualified capabilities.

## Engineering trust and privacy

LemCAD is being developed around a simple rule: **an engineering feature is not complete just because a command runs**. The validation target is creation, parameter editing, downstream regeneration, undo/redo, save/reopen, and equivalent results through desktop and headless workflows.

Your CAD geometry should remain local unless you explicitly choose a supported sharing or external service. The application may check published release information for updates; consult your installed version's release notes for the precise network and privacy behavior. Avoid placing confidential customer models in public bug reports.

## Feedback

LemCAD is especially interested in practical feedback from professional CAD users, makers, and small manufacturers. Tell us what you attempted, which version you used, what you expected, and what happened.

[**Lemery Designs / LemCAD**](https://lemerydesigns.com/lemcad) · [**Releases and release notes**](https://github.com/BuiltByLegacy/LemCAD/releases)

Please do not share private engineering drawings, export-controlled data, confidential customer CAD, credentials, or personal information in public reports.

---

<div align="center">

**LemCAD** by [Lemery Designs](https://lemerydesigns.com) · *Custom Built. Engineered Right.*

<sub>LemCAD is independently developed and is not affiliated with Siemens, Autodesk, PTC, Dassault Systèmes, Bambu Lab, or OrcaSlicer.</sub>

</div>
