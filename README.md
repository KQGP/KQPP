# KQPP — Plotter Toolchain

A **collection of tools, installers, and notes** for running a GRBL-based pen plotter (4xiDraw / KM-Laser style). Contains Universal G-Code Sender (UGS), Inkscape (with extensions), GRBL plotter, xLoader, and a PowerPoint overview.

## 📁 Contents

- `GRBL-Plotter_Setup_1710c.exe` — GRBL Plotter installer
- `4xiDraw & km laser.zip`, `KQGGRBL.zip` — firmware/hardware bundles
- `MI-GRBL-Z-AXIS-Servo-Controller-master.zip`, `MI-Inkscape-Extension.zip`, `xLoader-master.zip` — extensions/loaders
- `KQPP.pptx` — project presentation
- `Versions Used.txt` — software versions

## 🧰 Software Versions

See `Versions Used.txt` (UGS 2.1.0, Inkscape 0.48.5 / 0.92.5 / 1.3.2).

## 🚀 Getting Started

1. Install Inkscape (listed version).
2. Install GRBL Plotter (`GRBL-Plotter_Setup_1710c.exe`).
3. Flash GRBL firmware to your Arduino/plotter controller using `xLoader`.
4. Use Inkscape + extension to generate G-code; send via UGS/GRBL Plotter.
