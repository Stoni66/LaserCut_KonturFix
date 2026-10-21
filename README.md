# LaserCut KonturFix v3.1.0

LaserCut KonturFix is a multilingual Windows application that converts bitmap images and AI-generated artwork into clean, validated SVG and DXF files for laser cutting and engraving workflows.

## Download

[Download LaserCut_KonturFix_v3_1_0_multilingual_Setup.exe](https://github.com/Stoni66/LaserCut_KonturFix-Releases/releases/download/v3.1.0/LaserCut_KonturFix_v3_1_0_multilingual_Setup.exe)

[Release notes and details](https://github.com/Stoni66/LaserCut_KonturFix-Releases/releases/tag/v3.1.0)

Windows 10 or Windows 11, 64 bit. The application includes a 30-day trial.

## Documentation

- [Deutsch](README_de.md)
- [English](README_en.md)
- [Product website](https://stoni66.github.io/LaserCut_KonturFix/)

## New in v3.1.0

- Seven main groups: From image through mask and bridges to export; NC remains a placeholder.
- Tolerance-limited Bezier paths: Protected mode up to 0.1 mm; optional stronger smoothing with a targeted second pass.
- Measurement and original comparison: Maximum contour deviation, node statistics and a cyan preview reference.
- Optional original contour in DXF: Separate reference layer; explicitly exclude it from laser output.
- Illustrated quick start: The handball example and updated help in five languages.
- Familiar tools remain: Motif generators, manual bridges, projects, undo and offline licensing.

## Core features

- Cutting and **Engraving + outer cut** workflows
- Intelligent hierarchy for outer contours, holes and nested shapes
- Automatic and manually editable bridges
- Automatic per-contour smoothing and three export-quality levels
- Export validation with repair suggestions
- PNG, SVG and DXF export
- Undo/redo and reusable `.lkfproj` project files
- German, English, French, Italian and Spanish interface and offline help
- Ed25519-signed offline licensing

The application processes imported images locally. Internet access is only required when the optional ChatGPT links are used. Always verify contours, bridges and machine parameters in the target laser software before production.

Developed by Oswald Steiner.

## Current help

[Help & quick start](https://stoni66.github.io/LaserCut_KonturFix/help/en/index.html#worked-example)
