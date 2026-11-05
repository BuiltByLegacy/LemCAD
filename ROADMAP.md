# LemCAD Release Roadmap
**Updated:** November 4, 2026 · **Status:** proposed roadmap, subject to engineering validation and approval.

[**Download / product page**](https://lemerydesigns.com/lemcad) · [**Published Releases**](https://github.com/BuiltByLegacy/LemCAD/releases) · [**About LemCAD**](README.md)

> **What is shipping today?** The [published Releases page](https://github.com/BuiltByLegacy/LemCAD/releases) is the source for actual version numbers, downloadable installers, fixes and checksums. The version numbers and features below are **targets, not released features or promised dates**. LemCAD is an early preview and is not yet production-qualified.

## How version numbers work

| Example | Meaning |
| --- | --- |
| `0.1.0` | Initial preview build (historically withdrawn) |
| `0.1.1` | First working preview/fix in the initial 0.1 line |
| `0.2.0` | Next planned feature release |
| `0.2.1` | Maintenance and bug fix to 0.2.0 |
| `1.0.0` | First qualified stable professional release, once approved |
| `2.0.0` | Future major platform generation, possibly including intentional compatibility changes |

A patch version can be released between feature releases when tested fixes are ready. Previews can use suffixes such as `0.5.0-beta.1` or `1.0.0-rc.1`; these are **not** final releases.

## Planned releases (illustrative targets, no dates)

| Version / stage | What we're aiming to introduce | Status |
| --- | --- | --- |
| **0.1.x — Foundation** | Windows preview, first sketch and parametric modeling tools, part editing, document save/open and basic exports; ongoing reliability fixes | Early preview history and continued qualification |
| **0.2.0 — Alpha 0.2** | More dependable modeling and first controlled engineering automation/optional AI review, subject to testing | Proposed |
| **0.3.0 — Alpha 0.3** | First assembly and drawing foundations, component navigation and editable relationships | Proposed |
| **0.4.0 — Modeling experience** | Better sketching, regeneration, model navigation and recovery from failed operations | Proposed |
| **0.5.0 — Beta 0.5** | Expanded mechanical modeling and early, verified engineering annotations / PMI workflows | Proposed |
| **0.6.0 — Data integrity** | Native file compatibility, project recovery, performance and model reliability improvements | Proposed |
| **0.7.0 — Interoperability** | Better STEP/STL/3MF exchange and selected verified Print Studio/slicer workflows | Proposed |
| **0.8.0 — User experience** | Improved Windows installer/updater, onboarding, documentation and feedback tools | Proposed |
| **0.9.0 — Qualification** | Stabilization, real-world tester feedback, bug fixes and freeze for first major release | Proposed |
| **1.0.0 — Professional baseline** | A complete, externally tested and owner-approved core mechanical CAD experience with dependable editing, saving, export and qualified feature depth | Long-term release target; not scheduled |
| **1.1.0 — Manufacturing connections** | Candidate: slicer links, print recipes, design/production comparisons and printability checks | Post-1.0 candidate |
| **1.2.0 — Engineering intelligence** | Candidate: diagnostics, manufacturing-aware engineering analysis and controlled CAD migration tools | Post-1.0 candidate |
| **Later 1.x** | Candidate: richer product data, manufacturing workflows, inspection and collaboration | Research |
| **2.0.0 — Major platform** | Possible major expansion across engineering disciplines, interoperability and connected product lifecycle | Vision only |

Compatible bugs and security fixes may be shipped as `x.y.1`, `x.y.2`, etc. between stages. **We won't ship a feature just to meet a version target**, and an unfinished feature may move to a later version.

## What we're prioritizing first

1. **Modeling correctness:** reliable sketches, solids, feature edits, undo and regeneration.
2. **Document safety:** save/reopen, data integrity, recovery and backward compatibility.
3. **Windows experience:** install, launch, update and performance on real customer PCs.
4. **Engineering interchange:** STEP/STL and later 3MF, tested on real fixtures.
5. **Usability and transparency:** clear diagnostics, trustworthy demos, approachable tutorials, support and feedback.

Future **LemCAD Print Studio**, **CAD Bridge**, optional AI assistance and multi-process analysis are important directions, but their actual availability will depend on technical validation.

## How this roadmap is maintained

We review the version plan daily against active development and qualification work. **Daily review does not mean daily feature changes**: planned version commitments, release dates or feature promises require explicit approval. Public updates appear when there is a meaningful approved change. A planned feature moves to **released** only when its approved installer and release notes have actually been published.

**Current limitations:** LemCAD is in development; do not rely on the preview as the sole source of customer-production, regulated or safety-critical engineering data. Verify all geometry and exports with qualified tools.

---

LemCAD is independently developed by [Lemery Designs](https://lemerydesigns.com).
