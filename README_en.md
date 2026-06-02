# LaserCut KonturFix v2.4.0

**LaserCut KonturFix** is a Windows desktop application for preparing images and designs for laser cutting. The software converts bitmap images into optimized cutting contours, can connect loose islands with bridges, and exports the result as SVG or DXF.

It is designed for users who want to turn graphics, silhouettes, drawings, or AI-generated motifs into clean laser-ready files.

## Main Features

- Load images and convert them into laser-ready masks
- Export SVG and DXF files for laser cutters
- Adjust black threshold for mask generation
- Optional image inversion
- Smooth the generated mask
- Remove small unwanted details
- Connect islands and loose design parts with bridges
- Adjust bridge width
- Smooth SVG contours
- Set final motif width in millimeters
- Export as PNG, SVG, and DXF
- Multilingual user interface
- Selected language is saved and restored on the next start
- License system with installation ID and activation code
- Installer with desktop shortcut and uninstaller
- Direct button for creating new laser motifs through a dedicated Custom GPT

## Supported Languages

- German
- English
- French
- Italian
- Spanish

## Typical Workflow

1. Load an image
2. Adjust the black threshold
3. Create the mask
4. Remove small parts and adjust smoothing
5. Connect islands with bridges if needed
6. Check the SVG preview
7. Set the motif width
8. Save SVG or DXF
9. Continue in your laser software

## Export Formats

### SVG

The SVG export creates vector-based contours for laser cutting. The cutting line is saved as a colored stroke without fill.

### DXF

The DXF export creates a simple contour file for applications and machines that prefer DXF.

### PNG

The PNG export saves the optimized mask as an image file.

## Laser Cutter Compatibility

LaserCut KonturFix is designed for common laser workflows and can prepare files for software such as Trotec Ruby, LightBurn, RDWorks, Epilog software, xTool software, or other SVG/DXF-compatible laser applications.

Colors, line widths, and import behavior may differ between machines and software packages. Always check the final file and laser settings inside your target laser software before cutting.

## Create Motif

Version 2.4.0 adds the **Create motif** button. It opens a dedicated Custom GPT for laser cutter designs:

https://chatgpt.com/g/g-689b206008608191843591bc9d8eec44-laser-cutter-designs-cutting

At least a free ChatGPT account is required. The user must be logged in through the browser.

## Licensing

The software can be used during a trial period. A license is required for permanent activation.

The license section includes:

- Name / company
- Email address
- Installation ID
- License code

The installation ID can be copied and used when requesting a license.

## Installation

A Windows installer is available:

```text
LaserCut_KonturFix_v2_4_0_multilingual_Setup.exe
```

After installation, the app can be launched from the desktop shortcut or from the Start menu.

## Uninstallation

The installed version includes an uninstaller. The software can be removed through Windows app management or through the uninstaller in the installation folder.

## System Requirements

- Windows 10 or newer
- 64-bit system recommended
- For the "Create motif" button: internet connection and ChatGPT account

## Usage Notes

- Always check exported files in the target laser software before cutting.
- For complex images, it may be useful to adjust threshold, smoothing, and small-part removal several times.
- Loose islands should be connected with bridges wide enough for the selected material and design size.
- Very fine details may be lost depending on material, laser power, and kerf width.

## Version

Current version:

```text
LaserCut KonturFix v2.4.0 multilingual
```

## Author

Designed by Oswald Steiner
