# es-de-linux-custom-systems

Custom systems and find rules file for ES-DE primarily for Linux systems and the Steam Deck. 

## How to Use

Download the `es_find_rules.xml` and `es_systems.xml` file and place the two files in `~/ES-DE/custom_systems`. On the Steam Deck, this will be `/home/deck/ES-DE/custom_systems`. 

If files exist already, you may open the two files downloaded from this repo and copy the contents to the pre-existing files. Ensure that you do not duplicate the header and closer lines. For `es_find_rules.xml`, the lines will be `<ruleList>` and `</ruleList>` respectively. For `es_systems.xml`, the lines will be `<systemList>` and `</systemList>` respectively. 

Alternatively, you may use merging software (the Meld Flatpak can be installed from Discover) to merge the pre-existing files with the files downloaded from this repository. 

If you are using EmuDeck, it is highly likely the `es_find_rules.xml` and `es_systems.xml` file will already be created. If you are struggling with merging these files with the files downloaded from this repository, reach out to EmuDeck for support. This repository **will not** provide support on merging these files. 

## Filename Conventions

**Note:** Any `*` in the table below are wildcards. Wildcards are placeholders for version numbers or system specific file names. Wildcards are also used for case sensitivity. For example, both `Citron_*-x86_64.AppImage` and `Citron_*-x86_64.AppImage` are supported. If you have a version number or a specific system name in your AppImage, you **do not** need to rename and remove these elements. 

| **System Name** | **Emulator**       | **Filename Configuration** |
|-----------------|--------------------|----------------------------|
| switch          | Citron             | \*itron_*-x86_64.AppImage   |
| switch          | Eden               | \*den-Linux-v*-*.AppImage   |
| switch          | Ryujinx or Ryubing | \*yujinx*.AppImage          |
| switch          | Sudachi            | \*udachi                    |
| switch          | Suyu               | \*uyu-Linux_x86_64.AppImage |
| switch          | Yuzu               | \*uzu*.AppImage             |


## Issues

This **is not** a support repository for these emulators. If an emulator is not working, report the issue to the emulator developers directly. If one of the downloaded files is misconfigured, you may open an issue or pull request on this repository. **Do not** link to the download page of the emulator in your GitHub issue. 

## ES-DE Documentation

Make sure that you have checked and read ES-DE's documentation if you are unclear on how to use these files. See https://gitlab.com/es-de/emulationstation-de/-/blob/master/USERGUIDE.md for ES-DE'S User Guide. 
