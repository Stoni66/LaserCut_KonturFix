# LaserCut KonturFix v2.5.0

**LaserCut KonturFix** is a Windows desktop application for preparing images and AI-generated motifs for laser cutters. It creates clean SVG or DXF output from bitmap files, can connect loose islands with bridges, and since v2.5.0 can also export engraving images with a separate cuttable outer contour.

## Main Features

- Load PNG, JPG, BMP and TIFF images
- Create cut motifs from black-and-white masks
- Engraving mode with embedded raster image and red outer cut contour
- SVG and DXF export for laser software
- Save optimized PNG control images
- Black threshold, inversion, smoothing and small-part cleanup
- Automatically connect islands with bridges
- Adjustable bridge width and maximum bridge length
- Set final motif width in millimeters
- Smooth and simplify SVG paths
- Multilingual interface in German, English, French, Italian and Spanish
- Selected language is saved and restored on the next start
- License workflow with installation ID, request and activation
- Installer with desktop shortcut and uninstaller
- Integrated help and tooltips for the most important controls

## New in v2.5.0

- New **Engraving + outer cut** output mode
- Engraving remains embedded as a raster image inside the SVG
- Only the largest closed outer contour is generated as red cut line
- Second GPT button for engraving motifs with a cuttable frame
- Renamed **Create cut motif** GPT button for classic cutting motifs
- Dynamic tooltips for mask creation and SVG export depending on output mode
- Updated in-app help
- Nuitka-based application build prepared

## Custom GPT Buttons

**Create cut motif** opens a specialized GPT for laser-cuttable cut-out motifs:

https://chatgpt.com/g/g-689b206008608191843591bc9d8eec44-laser-cutter-designs-cutting

**Create engraving motif** opens a specialized GPT for engraving images with a cuttable frame:

https://chatgpt.com/g/g-6a220529bf9c81918c19433cccca2c31-create-engraving-motifs

Both features require at least a free ChatGPT account and an active browser login.

## Workflow for Cut Motifs

1. Load an image or create a cut motif with the GPT button
2. Select **Cut motif** output mode
3. Adjust black threshold, smoothing and small-part cleanup
4. Create the mask
5. Connect islands if needed
6. Check the SVG preview
7. Set the motif width
8. Save SVG or DXF

## Workflow for Engraving Motifs

1. Create an engraving motif with the GPT button or load your own image
2. Select **Engraving + outer cut**
3. Create the mask
4. Check the outer contour in the preview
5. Save SVG
6. The SVG can then be opened and nested in NestCheck

## Export Colors

- Red: cut contour
- Blue: engraving / engraving preview
- Gray: ignored helper contours

In engraving mode, the SVG contains an embedded raster image for engraving and a red outer contour for cutting.

## Compatibility

LaserCut KonturFix is designed for common laser workflows, including Trotec Ruby, LightBurn, RDWorks, Epilog, xTool and other software that can import SVG or DXF. Because machines may interpret colors and line widths differently, always check the final file in your target laser software before cutting.

## Installation

The Windows installer is named:

```text
LaserCut_KonturFix_v2_5_0_multilingual_Setup.exe
```

Direct download:

https://github.com/Stoni66/LaserCut_KonturFix/releases/download/v2_5_0/LaserCut_KonturFix_v2_5_0_multilingual_Setup.exe

After installation, the app can be launched from the desktop shortcut or Start menu. An uninstaller is included.

## Licensing

The software can be used during a trial period. A license is required for permanent use. The license area includes name/company, email address, installation ID and license code. The license request can be prepared directly from the app.

## System Requirements

- Windows 10 or newer
- 64-bit system recommended
- Internet connection for the GPT buttons
- ChatGPT account for the motif GPTs

## Author

Designed by Oswald Steiner
