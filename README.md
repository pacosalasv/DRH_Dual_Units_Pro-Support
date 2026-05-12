<div align="center">
  <img width="680" alt="DRH - Dual Units banner" src="docs/media/Logo.png" />
</div>

<br>

<div align="center">

# DRH - Dual Units

### Public Support Hub · Documentation · Feedback · Production Validation

**A Blender utility for switching scene units, viewing alternate measurements, and managing object display labels directly in the 3D View sidebar.**

![Status](https://img.shields.io/badge/status-production%20ready%2C%20pending%20approval-F59E0B?style=for-the-badge)
![Version](https://img.shields.io/badge/version-1.0.0-00B7FF?style=for-the-badge)
![Blender](https://img.shields.io/badge/blender-4.2%2B-0B1F4D?style=for-the-badge)
![Platforms](https://img.shields.io/badge/platforms-Windows%20%7C%20macOS%20%7C%20Linux-EAF2FF?style=for-the-badge&labelColor=0B1F4D&color=EAF2FF)

<br>

**Part of the DRH Add-ons ecosystem — Blender tools, updates, and releases.**

[![DRH Add-ons Hub](https://img.shields.io/badge/DRH%20Add--ons%20Hub-Visit%20Hub-1E5BFF?style=for-the-badge&labelColor=0B1F4D)](https://github.com/pacosalasv/DRH_Addons_Hub)

</div>

<!--
<div align="center">

[![Superhive](https://img.shields.io/badge/Superhive-Pending%20Approval-F59E0B?style=for-the-badge)](#)
[![Gumroad](https://img.shields.io/badge/Gumroad-Coming%20Soon-00B7FF?style=for-the-badge)](#)
[![BlenderKit](https://img.shields.io/badge/BlenderKit-Coming%20Soon-0B1F4D?style=for-the-badge)](#)

</div>
-->

---

<div align="center">

**DRH - Dual Units** helps Blender users switch unit presets, review alternate dimensions, location, and rotation values, and add clean object-name overlays for scale checking and viewport communication.

This repository is the public support and documentation hub for version **1.0.0** while the add-on is **production ready and pending marketplace approval**.

</div>

---

<details>
  <summary><strong>📚 Table of Contents</strong></summary>

## Menu

- [Overview](#overview)
- [Media preview](#media-preview)
- [What DRH - Dual Units does](#what-drh---dual-units-does)
- [Key features](#key-features)
- [Full feature list](#full-feature-list)
- [Who is it for?](#who-is-it-for)
- [Current status](#current-status)
- [Feedback wanted before approval](#feedback-wanted-before-approval)
- [Quick links](#quick-links)
- [Before you post](#before-you-post)
- [Use Discussions for](#use-discussions-for)
- [Use Issues for](#use-issues-for)
- [Where to post](#where-to-post)
- [Support policy](#support-policy)
- [Technical notes](#technical-notes)
- [Availability](#availability)
- [Documentation](#documentation)
- [License](#license)

</details>

---

## Overview

**DRH - Dual Units** is a Blender workflow utility designed to make unit switching, alternate measurement display, and object display review faster inside the 3D View sidebar.

It is intended for modelers, makers, 3D printing users, product visualization artists, architecture-adjacent users, asset creators, and Blender users who need to move between real-world unit systems or verify object dimensions during production.

Instead of repeatedly changing scene unit settings manually or relying on mental conversions, DRH - Dual Units provides preset-based unit workflows, alternate measurement readouts, and viewport name-label controls in one focused add-on.

Version **1.0.0** is considered **production ready** and is currently **pending approval** for public marketplace distribution.

---

## Media preview

<!--

### Demo video

Replace `YOUTUBE_VIDEO_ID` with your real YouTube video ID.

Example:
https://www.youtube.com/watch?v=YOUTUBE_VIDEO_ID

<div align="center">
  <a href="https://www.youtube.com/watch?v=YOUTUBE_VIDEO_ID" target="_blank">
    <img width="720" alt="DRH - Dual Units demo video" src="https://img.youtube.com/vi/YOUTUBE_VIDEO_ID/maxresdefault.jpg" />
  </a>
  <br>
  <sub>Click the image to watch the demo on YouTube.</sub>
</div>
-->

<!--
### Quick demo GIF

Recommended size: 1280x720 or 960x540.

<div align="center">
  <img width="720" alt="DRH - Dual Units quick demo" src="docs/media/dual-units-demo.gif" />
</div>
-->

### Screenshots

<div align="center">

| Transform Panel Alternate Units | Object Labels and Placement |
|---|---|
| <img height="420" alt="Transform Panel with Alternate Units" src="docs/media/ScreenShot_01.png" /> | <img height="420" alt="Object Labels and Placement" src="docs/media/ScreenShot_02.png" /> |

</div>

<details>
  <summary><strong>More Screenshots...</strong></summary>

<div align="center">

| Units and Panel Settings |
|---|
| <img height="420" alt="Units and Panel Settings" src="docs/media/ScreenShot_03.png" /> |

</div>

</details>

---

## What DRH - Dual Units does

DRH - Dual Units adds a dedicated Blender sidebar workflow for scene units, alternate unit display, and object display labeling.

Use it to:

- Switch between practical scene unit presets
- Show alternate dimensions, location, and rotation values
- Format alternate values with precision, brackets, and split-unit display
- Swap scene and alternate unit workflows when supported
- Show or hide rotation mode and scale controls in the panel
- Apply object display settings to selected objects
- Display object names outside object bounds with configurable anchor, position, size, color, and offset
- Reset scene and add-on settings to defaults
- Keep measurement and viewport review tools available from the 3D View UI

---

## Key features

- Scene unit presets for metric, imperial, product, architecture, site, carpentry, and 3D printing workflows
- Alternate length units for meters, centimeters, millimeters, kilometers, inches, feet, yards, and miles
- Alternate rotation-unit support
- Alternate dimensions, location, and rotation display
- Precision controls from 0 to 6 decimal places
- Optional split-unit formatting for supported alternate unit families
- Bracket style options for alternate values
- Object display tools for selected objects
- External object-name overlay controls
- Name anchor, placement, size, color, and offset settings
- Apply-to-selected workflow for object display settings
- Settings popup and reset-to-defaults workflow
- Scene and object property registration for persistent settings
- Local Blender add-on workflow with no external service requirement

---

<details>
  <summary><strong>🧩 Full feature list</strong></summary>

## Full feature list

### Unit Switching & Presets

- Scene unit preset workflow
- Alternate unit workflow
- Preset: Custom
- Preset: General Metric
- Preset: Product Metric
- Preset: Arch Imperial
- Preset: Site Imperial
- Preset: Architecture mm
- Preset: Carpentry
- Preset: 3D Printing
- Swap Scene / Alternate Units operator
- Reset all defaults operator

### Supported Alternate Length Units

- Meters
- Centimeters
- Millimeters
- Kilometers
- Inches
- Feet
- Yards
- Miles

### Preset Behavior

- General Metric: metric meters, degrees, alternate inches
- Product Metric: metric millimeters, degrees, alternate inches
- Architecture mm: metric millimeters, degrees, alternate inches
- 3D Printing: metric millimeters, degrees, alternate inches
- Arch Imperial: imperial inches, degrees, alternate millimeters
- Site Imperial: imperial feet, degrees, alternate meters
- Carpentry: imperial inches with separate units enabled, alternate millimeters

### Measurement Display

- Show alternate dimensions
- Show alternate location values
- Show alternate rotation values
- Show rotation mode controls
- Show scale controls
- Alternate precision controls
- Alternate split-unit display
- Bracket style options
- Alternate rotation-unit selection

### Object Display Tools

- Active object display-type controls
- Apply selected object display settings
- Show object name outside object bounds
- Name anchor controls
- Name placement controls
- Name size controls
- Name color controls
- Name offset controls
- Viewport overlay redraw/update handling

### Batch & UI Workflow

- Apply selected display and label settings to selected objects
- Settings popup
- Reset all defaults
- Main transform panel
- Properties subpanel
- Scene-level settings stored on the scene
- Object-level label settings stored on each object
- Local viewport draw handler for custom object-name overlays

</details>

---

## Who is it for?

DRH - Dual Units is designed for:

- Blender modelers
- 3D printing users
- Makers
- Product visualization artists
- Asset creators
- Technical artists
- Architecture-adjacent Blender users
- Users working with real-world scale
- Users who need fast unit switching
- Users who need metric and imperial references
- Users who want clearer measurement, labeling, and scale-review workflows

---

## Current status

| Item | Details |
|---|---|
| **Status** | 🟠 Production Ready, Pending Approval |
| **Current version** | 1.0.0 |
| **Minimum Blender version** | 4.2.0 |
| **Platforms** | Windows, macOS, Linux |
| **Release type** | Production-ready build pending marketplace approval |
| **Support repository** | [DRH - Dual Units Support](https://github.com/pacosalasv/DRH_Dual_Units_Pro-Support) |

The add-on is currently considered production ready. Public marketplace availability is pending approval.

Compatibility feedback, usability notes, documentation comments, and workflow suggestions are welcome during this approval stage.

---

## Feedback wanted before approval

This repository is open for public feedback while version **1.0.0** completes the marketplace approval process.

Feedback is especially welcome on:

- Installation experience
- Blender version compatibility
- Unit preset workflow
- Alternate unit display expectations
- Unit conversion expectations
- Measurement workflow needs
- Scene scale requirements
- Metric and imperial workflow expectations
- 3D printing use cases
- Modeling and asset preparation needs
- Object-name overlay usefulness
- Label placement, color, size, and offset behavior
- Viewport overlay behavior
- Documentation clarity
- Marketplace listing expectations

Useful feedback examples:

> “I would use this to switch quickly between metric and imperial units.”

> “This is useful for 3D printing scale checks.”

> “I need clearer unit conversion without changing scene settings repeatedly.”

> “This helps confirm object dimensions before export.”

> “The object-name overlay helps during viewport reviews.”

> “This makes real-world scale easier to review.”

---

## Quick links

- [Support repository](https://github.com/pacosalasv/DRH_Dual_Units_Pro-Support)
- [Ask a question in Discussions](https://github.com/pacosalasv/DRH_Dual_Units_Pro-Support/discussions)
- [Open a new issue](https://github.com/pacosalasv/DRH_Dual_Units_Pro-Support/issues/new/choose)
- [Report a bug](https://github.com/pacosalasv/DRH_Dual_Units_Pro-Support/issues/new?template=bug_report.yml)
- [Request a feature](https://github.com/pacosalasv/DRH_Dual_Units_Pro-Support/issues/new?template=feature_request.yml)
- [Report a compatibility issue](https://github.com/pacosalasv/DRH_Dual_Units_Pro-Support/issues/new?template=compatibility_issue.yml)

---

## Before you post

Please include as much of the following information as possible:

- Add-on version
- Blender version
- Operating system
- Installation method
- Clear steps to reproduce
- Expected result
- Actual result
- Error message, screenshot, or console output when available

For compatibility issues, please also include:

- Blender build type, if known
- Portable or installed Blender version
- Whether the issue happens with a clean Blender configuration
- Unit system involved, if relevant
- Measurement or conversion value involved, if relevant
- Scene scale settings, if relevant
- Alternate unit involved, if relevant
- Whether the issue involves unit presets, alternate measurement display, object labels, viewport overlays, object display settings, scale display, or export preparation

---

## Use Discussions for

- Questions
- How-to topics
- Installation help
- Compatibility checks
- FAQ
- Suggestions
- Production-readiness feedback
- Marketplace approval feedback
- Workflow ideas

---

## Use Issues for

- Confirmed bugs
- Reproducible compatibility problems
- Unit preset problems
- Unit conversion problems
- Alternate value display issues
- Measurement or display issues
- Scene scale issues
- Object label or viewport overlay issues
- Object display setting issues
- Feature requests
- Regressions
- Marketplace or listing-related problems
- Documentation errors

---

## Where to post

Open a **Discussion** for:

- General questions
- Setup help
- Workflow advice
- Suggestions
- Feedback during approval

Open an **Issue** for:

- Confirmed bugs
- Reproducible compatibility problems
- Unit switching failures
- Unit conversion failures
- Measurement or scene scale problems
- Object label display problems
- Regressions
- Feature requests
- Documentation problems

---

## Support policy

This repository is a public support hub.

Do not post:

- Private account details
- License keys
- Payment information
- Confidential production files
- Private client files
- Sensitive system information

If a private file is required to reproduce an issue, please describe the problem first and wait for further instructions.

---

## Technical notes

This add-on is source based, with:

- No obfuscation
- No binary-only content
- No external services
- No account requirements

Local system access may be used only for normal Blender workflows such as saving files, loading assets, exporting data, or using project resources when applicable.

The add-on is intended to work locally inside Blender.

---

## Availability

Version **1.0.0** is production ready and pending marketplace approval.

After approval, this add-on may be available through multiple marketplaces and storefronts.

This GitHub repository remains the central public location for:

- Support
- Documentation
- Issue tracking
- Compatibility reports
- Public feedback
- Release notes

---

## Documentation

- [User Manual](docs/manual/user-manual.pdf)
- [Changelog](CHANGELOG.md)

---

## License

This repository is distributed under **GPL-3.0-or-later**.

---

<div align="center">

### DRH Add-ons

**Blender tools, updates, and releases.**

Built for clean workflows, practical utilities, and production-friendly Blender setups.

[![DRH Add-ons Hub](https://img.shields.io/badge/DRH%20Add--ons%20Hub-Visit%20Hub-1E5BFF?style=for-the-badge&labelColor=0B1F4D)](https://github.com/pacosalasv/DRH_Addons_Hub)

</div>