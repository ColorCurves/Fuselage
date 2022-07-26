# Changelog  
  
| modName    | DaMichel's Fuselage (DMF)                                         |
| ---------- | ----------------------------------------------------------------- |
| license    | CC-BY-SA-4.0                                                      |
| author     | DaMichel, Bezzier and zer0Kerbal                                  |
| forum      | (https://forum.kerbalspaceprogram.com/index.php?/topic/208131-*/) |
| github     | (https://github.com/zer0Kerbal/zer0Kerbal/Fuselage)               |
| curseforge | (https://www.curseforge.com/kerbal/ksp-mods/Fuselage)             |
| spacedock  | (https://spacedock.info/mod/2340)                                 |
| ckan       | DMTanks-Fuselage                                                  |

## Version 1.1.99.0-prerelease - `<Split'n'Polish: Fuselage>`

* 23 Jul 2022
* Release for Kerbal Space Program [KSP 1.12.x]

### Summary 1.1.99.0

* Initial Prerelease
* New Dependency
  * [DaMichel Ltd (agency, flag, common files)(DM/L)][DML]

[DML]: https://forum.kerbalspaceprogram.com/index.php?/topic/208107-*/ "DaMichel Ltd (DM/L)"

### License

* Updated License: CC-BY-SA-4.0
  * was: CC-BY-SA-3.0
* closes #36 - License

### Compatibility

* Add
  * [ghostparts.cfg] v1.0.0.0
    * part renamed: [DM-fuselage-intake] --> DMfuselage-intake
* Update
  * All
    * rename [B9Volume] -> [TankVolume]
  * [ActiveTextureManagement.cfg] - v 1.0.0.0
    * disabled by default
    * renamed to [ActiveTextureManagement.cfg.0]
  * [AdvancedJetEngine.cfg] v1.0.0.0
  * [B9FuelSwitch.cfg] v1.2.0.0
    * simplified patch
    * swap [SUBTYPE] name <--> title
  * [B9NodeSwitch.cfg] v1.0.0.0
  * [ModularFuelTanks.cfg] v1.1.0.0
    * simplified patch
      * one patch instead of five
    * [description]
      * correct ModuleFuelTanks --> Modular Fuel Tanks
  * [RealFuels.cfg] v1.1.0.0
    * simplified patch
      * one patch instead of five
    * added [description]

### Parts

* Add
  * header
  * [DRAG_CUBE]
* Update
  * [manufacturer] = #DML-Agency-titl
* [DM-fuselage-adapter] v1.0.1.0
  * [tags] now #autoLOC_500561 was #DMF-adapter-tags
  * [ModuleCargoPart]
    * Dimensions: x: 1.25, y: 1.88, z: 1.25
    * Bounding Box Size: 2930.072 liters
    * [packedVolume] = 3000
* [DM-fuselage-front] v1.0.1.0
  * [tags] now #autoLOC_500162 was #DMF-front-tags
  * [ModuleCargoPart]
    * [packedVolume] = 2150
    * Dimensions: x: 1.25, y: 1.88, z: 0.89
    * Bounding Box Size: 2091.797 liters
* [DM-fuselage-cone] v1.0.1.0
  * [tags] now #autoLOC_500111 was #DMF-cone-tags
  * [ModuleCargoPart]
    * Dimensions: x: 1.16, y: 1.88, z: 1.16
    * Bounding Box Size: 2524.812 liters
    * [packedVolume] = 2600
* [DM-fuselage-tailboom] v1.0.1.0
  * [tags] now #autoLOC_500165 was #DMF-tailboom-tags
  * [ModuleCargoPart]
    * Dimensions: x: 0.40, y: 3.75, z: 0.30
    * Bounding Box Size: 450 liters
    * [packedVolume] = 500
* [DM-fuselage-X1] v1.0.1.0
  * [tags] is #autoLOC_500573 was #DMF-X1-tags
  * [ModuleCargoPart]
    * Dimensions: x: 1.25, y: 1.88, z: 0.89
    * Bounding Box Size: 2091.797 liters
    * [packedVolume] = 2125
* [DM-fuselage-X2] v1.0.1.0
  * [tags] is #autoLOC_500573 was #DMF-X2-tags
  * [ModuleCargoPart]
    * Dimensions: x: 1.25, y: 3.75, z: 0.89
    * Bounding Box Size: 4183.594 liters
    * [packedVolume] = 4200
* [DM-fuselage-intake] v1.0.1.0
  * [tags] is #autoLOC_500575 was #DMF-intake-tags
  * [ModuleCargoPart]
    * Dimensions: x: 1.25, y: 2.23, z: 0.89
    * Bounding Box Size: 2487.771 liters
    * [packedVolume] = 2500
* closes #40 - Update Parts

### Asset Updates

* create Assets/ folder
* convert from mesh to MODEL
* rename
  * models to unique names
  * textures to unique names
* update
  * model pointers (.png et al to .dds)
  * model texture pointers to new names
* relocate assets to Assets/
* eliminate
  * duplicate textures
  * duplicate models
* relocate part.cfg to Parts
* closes #28 - Asset Updates

### Localization

* Update
  * [en-us.cfg] v1.1.0.0
  * [readme.md] v2.1.2.0
  * [quickstart.md] v1.0.1.1
  * Config/
    * [Fuselage.cfg] v1.0.0.0
      * adds localized tags to parts
  * Parts
    * [ModuleToggleCrossfeed]
      * #DMF-enableText --> #autoLOC_236028 // Enable Crossfeed
      * #DMF-disableText --> #autoLOC_236030 // Disable Crossfeed
      * add: #autoLOC_236032 // Toggle Crossfeed
    * [ModuleAnimateGeneric]
      * #DMF-startEventGUIName --> #autoLOC_6001425 // Toggle Intake
      * #DMF-endEventGUIName --> #autoLOC_6001426 // Close Intake
      * #DMF-actionGUIName --> #autoLOC_6001427 // Open Intake
* updates #6 - Localization - Master
* closes #7 - American English <us-en.cfg>
* closes #37 - Add localized tags to parts

### docs/

* Add/Update
  * [Attribution.md] v1.0.7.1
  * [ManualInstallation.md] v1.1.8.0
  * [404.md] v1.0.3.2
  * [LegalMumboJumbo.md] v1.0.5.1
  * [Localizations.md] v1.1.7.0
  * [Marketing.md] v1.0.1.0
  * [Notices.md] v1.0.1.0
  * [Part-Catalog.md] v1.1.4.0
  * [Why.md] v1.1.0.0
  * [_config.yml]
  * [changelog.md]
    * add header for docs/
* closes #38 - docs/

### Documentation

* Update
  * [Readme.md] v1.6.9.2
  * [ReleaseNotes.md] v1.3.1.1
  * [Fuselage.version]
    * remove
      * [KSP_VERSION_MAX]
* closes #39 - Update Documentation

### Status

* Issues
  * closes #2 - Fuselage (DMF) 1.1.99.0-prerelease `<Split'n'Polish: Fuselage>`
  * closes #3 - 1.1.99.0 Verify Legal Mumbo Jumbo
  * closes #4 - 1.1.99.0 Update Documentation
  * closes #5 - 1.1.99.0 Update Social Media

---

## Version 1.1.0.2-release - `<Superglue and Dusting>`

* Released on 2020-03-09
* Kerbal Space Program 1.9.1

* cleaned part.cfg's of extraneous // comments
* updated changelog to use updated KERBALCHANGELOG formatting.
* [B9PartSwitch.cfg]
  * Localized
  * added side nodes

### Status

* Issues
  * closes #24 - Previous Releases
  * closes #26 - 1.1.0.2-release
  * updates #28 - Asset Updates

---

## Version 1.1.0.1-prerelease - `<Spit'n'Polish`>

* Released on 2020-02-23
* Kerbal Space Program 1.9.1

### Thank You

* KottabosGames for the review and suggestions!
* BenjaminCronin
  * for pointed out decorative right brace in changelogs
    * wite-out applied.
  * Also dangling VERSION
    * superglued applied.

### Adjusted

* All Parts
  * strength
  * temperatures
  * adjusted breakingForce on all parts from 50 to 200 (except where noted)
  * adjusted breakingTorque on all parts from 50 to 200(except where noted)
  * adjusted B9fuelswitch to have LF come after Structural instead of LFO
  * [explosionPotential] = 0.5
  * [buoyancy] = 0.1

### Added

* [DM-fuselage-intake.cfg]
  * same specs like the Ram Air Intake.
  * Added
    * [thermalMassModifier] = 12.0
    * machcurve to ModuleResourceIntake on intake
  * Adjusted
    * intakeSpeed from 10 to 15
    * [RESOURCE] [IntakeAir] amount/maxAmount from 0.2 to 2.0
    * [entryCost] from 1600 to 14000
    * [cost] from 2000 to 2680
    * [maximum_drag] from 0.2 to 0.3
    * [minimum_drag] from 0.2 to 0.3
  * added
    * [ModuleAnimateHeat]
    * [stackSymmetry] = 2
* [DM-fuselage-cone]
  * basing stats on: Advanced Nose Cone - Type B (pointyNoseConeB)
  * Adjusted
    * [scale] = 0.9375, 0.9375, 0.9375 from 1.0, 0.9375, 1.0
      * noted by Kottabo
  * [entryCost] to 8000 from 1600
  * corrected typo on [maximum_drag] should have been 0.1 instead it was 0.11
  * [angularDrag] to 0.25 from 0.5
  * [maxTemp] to 2000 from 2900
  * Added
    * size2 to [bulkheadProfiles] = mk1, size2, srf
    * [explosionPotential] = 0.5
    * [CoMOffset] = 0.0, 0.0, -0.313
    * [CoPOffset] = 0.0, 0.0, -0.313
    * [CoLOffset] = 0.0, 0.0, -0.313
    * [CenterOfDisplacement] = 0.0, -0.2, 0.0
    * [thermalMassModifier] = 6.0
    * [emissiveConstant] = 0.95
    * [buoyancy] = 0.1
    * [ModuleAnimateHeat]
* [DM-fuselage-tailboom]
  * Based upon Tail Connector A (airplaneTailB)
  * Adjusted
    * [entryCost] to 2500 from 1600
    * [cost] to 500 from 200
    * [crashTolerance] to 8 from 20
    * [maxTemp] to 2200 from 2900
  * Added
    * [thermalMassModifier] = 6.0
    * [emissiveConstant] = 0.95
    * [explosionPotential] = 0.5
    * [CoMOffset] = 0.0, -1.5, 0.0
    * [CoPOffset] = 0.0, -1.5, 0.0
    * [CoLOffset] = 0.0, -1.5, 0.0
    * [CenterOfDisplacement] = 0.0, -1.5, 0.0
    * [buoyancy] = 0.1
    * [explosionPotential] = 0.5
    * [ModuleAnimateHeat]
* [DM-fuselage-X1] DMF - Flat Fuel Tank X1
  * based upon Mk2 Rocket Fuel Fuselage Short(mk2FuselageShortLFO)
  * Adjusted
    * [entryCost] to 15000 from 1600
    * [crashTolerance] to 50 from 10
    * [maxTemp] to 2500 from 2900
  * Added
    * [buoyancy] = 0.1
    * srf to [bulkheadProfiles] = mk1, srf
    * [mirrorRefAxis] = 0, 0, -1
    * [ModuleLiftingSurface]
* [DM-fuselage-X2] DMF - Flat Fuel Tank X2
  * based upon Mk2 Rocket Fuel Fuselage(mk2FuselageLongLFO)
  * Adjusted
    * [entryCost] to 18000 from 1600
    * [crashTolerance] to 50 from 10
    * [maxTemp] to 2500 from 2900
  * Added
    * [buoyancy] = 0.1
    * srf to [bulkheadProfiles] = mk1, srf
    * [mirrorRefAxis] = 0, 0, -1
    * [ModuleLiftingSurface]
* [DM-fuselage-front] DMF - Flat End
  * based upon (noseConeAdapter) NCS Adapter
    * Adjusted
      * [entryCost] to 8000 from 600
      * [mass] to 0.1 from 0.11
      * [angularDrag] from 0.25 // 0.5
      * [maxTemp] to 2400 from 2900
    * Added
      * [explosionPotential] = 0.5
      * [CenterOfDisplacement] = 0.0, -0.2, 0.0
      * [thermalMassModifier] = 6.0
      * [emissiveConstant] = 0.95
      * [buoyancy] = 0.1
      * [bulkheadProfiles] = mk1, size0
      * [ModuleAnimateHeat]
* [DM-fuselage-adapter] DMF - Flat to 1.25m Round Adapter
  * based upon (mk2SpacePlaneAdapter) Mk2 to 1.25m Adapter
    * Adjusted
      * [entryCost] to 14000 from 1600
      * [minimum_drag] to 0.1 from 0.3
      * [angularDrag] to 2 from 1
      * [crashTolerance] to 50 from 10
      * [breakingForce] to 50 from 200
      * [breakingTorque] to 50 from 200
      * [maxTemp] to 2500 from 2900
    * Added
      * srf to [bulkheadprofiles] = mk1, size1, srf
      * [buoyancy] = 0.1
      * [emissiveConstant] = 0.8
      * [explosionPotential] = 0.5
      * [ModuleLiftingSurface]

### Status

* Issues
  * updates #24 - Previous Releases
  * closes #26 - 1.1.0.1-prerelease
  * updates #28 - Asset Updates

---

## Version 1.1.0.0-adoption - `<Fresh Coat of Paint: Fuselage>`

* Released on 2020-02-17
* for Kerbal Space Program (KSP) 1.9.x

### Adopted for curation by zer0Kerbal

### Localization

* Added
  * <en-us.cfg>
  * translations welcomed through GitHub Push Request
* updates #6 - Localization - Master
* closes #7 - American English <us-en.cfg>
* closes #23 - Part Localization

### Updated

* file structure and modernization
* modernized part.cfg
* many little changes to patches/parts.

### Added Kerbal Changelog

* added
  * Readme
  
### Created

* github repo
* SpaceDock entry
* CKAN entry
* Curseforge entry
* Forum post
* .json

### Status

* Issues
  * updates #24 - Previous Releases
  * closes #25 - 1.1.0.0-adoption
  * updates #28 - Asset Updates

---

## Version - 1.0.0.0-release - colorcurves update

* May 10, 2016
* Kerbal Space Progrtam 1.0.5
* adopted by Bezzier (Color Curves)

### This brings these parts up to date by

Correcting typos

* Correcting typos
* Rebalancing to stock values
  * costs
  * masses
  * temperatures
  * drag
* Adding Core Heat
* [techRequired] to experimentalElectrics

---

## Version - 0.0.0.0-release - Original by DaMichel

* unknown version number
* Apr 18-2014
* First release

---

<!-- This File CC BY-ND 4.0 by zer0Kerbal -->
