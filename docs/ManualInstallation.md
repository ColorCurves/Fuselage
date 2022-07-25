---
permalink: /ManualInstallation.html
title: Manual Installation
description: the flat-pack Kiea instructions, written in Kerbalese, unusally present
tags: installation,directions,page,kerbal,ksp,zer0Kerbal,zedK
---

<!-- ManualInstallation.md v1.1.8.0
Fuselage (DMF)
created: 01 Oct 2019
updated: 21 Jul 2022 -->

<!-- based upon work by Lisias -->

# Fuselage (DMF)

[Home](./index.md)

Adds seven (7) stock-a-like flat fuselage parts. These parts are rectangular fuselage pieces meant to be radially attached.

## Installation Instructions

### Using CurseForge/OverWolf app or CKAN

You should be all good! (check for latest version on CurseForge)

### If Downloaded from CurseForge/OverWolf manual download

To install, place the `DaMichel` folder inside your Kerbal Space Program's GameData folder:

* **REMOVE ANY OLD VERSIONS OF THE PRODUCT BEFORE INSTALLING**
  * Delete `<KSP_ROOT>/GameData/DaMichel/Fuselage`
* Extract the package's `DaMichel` folder into your KSP's GameData folder as follows:
  * `<PACKAGE>/DaMichel` --> `<KSP_ROOT>/GameData/`
    * Overwrite any preexisting folder/file(s).
  * you should end up with `<KSP_ROOT>/GameData/DaMichel/Fuselage`

### If Downloaded from SpaceDock / GitHub / other

To install, place the `GameData` folder inside your Kerbal Space Program folder:

* **REMOVE ANY OLD VERSIONS OF THE PRODUCT BEFORE INSTALLING**
  * Delete `<KSP_ROOT>/GameData/DaMichel/Fuselage`
* Extract the package's `GameData` folder into your KSP's root folder as follows:
  * `<PACKAGE>/GameData` --> `<KSP_ROOT>`
    * Overwrite any preexisting file.
  * you should end up with `<KSP_ROOT>/GameData/DaMichel/Fuselage`

## The following file layout must be present after installation

```markdown
<KSP_ROOT>
  + [GameData]
    + [DaMichel]
      + [Fuselage]
        + [Assets]
          ...
        + [Compatibility]
          ...
        + [Config]
          ...
        + [Localization]
          ...
        + [Parts]
          ...
        * #.#.#.#.htm
        * Attributions.htm
        * CC-BY-SA-3.0.txt
        * changelog.md
        * FuselageLtd.version
        * ManualInstallation.htm
        * readme.htm
    ...
  * KSP.log
  ...
```

### Dependencies

* [DaMichel Ltd (DM/L)][DML]

[DML]: https://forum.kerbalspaceprogram.com/index.php?/topic/208107-*/ "DaMichel Ltd (DM/L)"
