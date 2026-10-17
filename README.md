# Divine Intervention Updater Tool

A Windows desktop tool for updating Divine Intervention for Crusader Kings III and generating compatibility output for other mods.

[Download the latest release](https://github.com/Lithane97/Divine-Intervention-Updater-Tool/releases/latest)

## Installation

1. Download and extract the release ZIP.
2. Run `DI-Updater-Tool-Setup-Windows-x64.exe`.
3. Launch the tool from the Start menu and follow the folder setup guide.

Choose your Base DI folder, CK3 game folder, and output folder. Select **Use Base DI folder** when updating DI itself, or choose a separate mod folder for compatibility output. CK3 and Divine Intervention must be installed separately. Back up existing mod output before updating it.

The offline installer includes the Microsoft Visual C++ prerequisite. Python is not required. Only prerequisite installation may request administrator permission. Restart Windows if Setup requests it.

## Updating and uninstalling

Close the tool and run the newer Setup in the same installation folder. Saved settings and presets are retained.

Uninstall through Windows Installed Apps or the Start menu shortcut. You can optionally remove saved settings and presets. Generated mod files and the shared Microsoft runtime are kept.

## Release contents and licenses

This repository distributes packaged releases; the application source is private. The release ZIP includes matching third-party Qt/PySide/Shiboken library sources and replacement instructions. Original license texts and notices are included in the installed application. Keep the accompanying third-party source archive available when redistributing the installer.

**0.2.0 Preview** is an unsigned preview release. Automated checks and local installation tests passed; broader clean Windows and in-game testing is still needed.
