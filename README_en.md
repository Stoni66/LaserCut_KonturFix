# LaserCut KonturFix v2.8.0

**LaserCut KonturFix** is a multilingual Windows desktop application for preparing bitmap images and AI-generated artwork for laser cutters. It creates clean, smoothed and validated SVG or DXF contours, connects loose islands with bridges when required, and supports engraving images with a separate cuttable outer contour.

## Download

[Download LaserCut_KonturFix_v2_8_0_multilingual_Setup.exe](https://github.com/Stoni66/LaserCut_KonturFix-Releases/releases/download/v2.8.0/LaserCut_KonturFix_v2_8_0_multilingual_Setup.exe)

[Release notes and details for v2.8.0](https://github.com/Stoni66/LaserCut_KonturFix-Releases/releases/tag/v2.8.0)

The installer includes a 30-day trial, desktop shortcut, complete offline help and an uninstaller.

## New in v2.8.0

- Local cut-motif prompt generator with material, thickness, dimensions, detail level and optional outer frame
- Automatic ImageGen guidance for pure black-and-white artwork, minimum feature sizes, fewer islands and bridge-friendly contours
- Local engraving-motif prompt generator with engraving style, detail level and selectable cut-out shape
- Material-specific grayscale and contrast guidance for acrylic, wood/MDF, slate, glass, metal and leather
- Copy-ready prompts for use in the matching specialized ChatGPT assistant
- Extended HTML help and automated tests for both prompt generators

The prompt generators do not create images inside the application. They turn the selected technical requirements into an optimized prompt. The motif can optionally be generated in ChatGPT, saved and then loaded back into LaserCut KonturFix.

## Main features

- Load PNG, JPG, BMP and TIFF files
- Create cutting motifs from black-and-white masks
- **Engraving + outer cut** with embedded raster artwork and a separate cut contour
- Intelligent hierarchy for outer contours, holes and nested shapes
- Three contour modes: outer only, outer plus holes, or all contours
- Automatic collision-checked bridges with optional automatic width calculation
- Place bridges manually and remove individual bridges directly in the preview
- Automatic per-contour smoothing with configurable limits
- Three export-quality levels: fast, high up to 3000 pixels, or original resolution
- Automatic export validation with clear warnings and repair suggestions
- PNG, SVG and DXF export
- Undo/redo with up to 20 editing states
- Save and reopen complete `.lkfproj` project files
- Interface and offline help in German, English, French, Italian and Spanish
- Ed25519-signed offline licensing

## Typical workflow

1. Load an image or use one of the local prompt generators to create a suitable ImageGen prompt.
2. Select **Cut motif** or **Engraving + outer cut**.
3. Adjust threshold, inversion, smoothing and small-part cleanup.
4. Generate the mask and contours.
5. Connect islands automatically and correct bridges manually if necessary.
6. Set the final width and export quality.
7. Check the preview and export validation.
8. Export PNG, SVG or DXF.

## Contour colors

- Green: inner cut contours, cut first
- Red: outer cut contour, cut last
- Blue: engraving or engraving preview
- Gray: ignored helper contours
- Yellow: placed bridges in the preview

These colors assist verification. Laser power, speed, focus and the final processing order must still be configured in the target laser software.

## Privacy and internet access

Image processing, contour generation, project handling and license validation operate locally. Images and license data are not automatically transmitted to ChatGPT or any other online service. An internet connection and, where required, a ChatGPT login are only needed when an optional ChatGPT link is opened.

## Licensing

The application can be evaluated for 30 days. A license is required for continued use. Activation works entirely offline and is tied to the installation ID. The customer application contains only the public Ed25519 verification key; private key material is not included in the installer.

## Compatibility and system requirements

- Windows 10 or Windows 11
- 64-bit system
- Typical target applications: Trotec Ruby, LightBurn, RDWorks, Epilog, xTool and other software supporting SVG or DXF import
- Internet access only for the optional ChatGPT functions

Laser systems may interpret colors, line widths and geometry differently. Always inspect every exported file in the target software and perform an initial test using safe machine settings.

## Author

Developed by Oswald Steiner.
