# HT500.3 PrusaSlicer profiles

This is the latest PrusaSlicer configuration profile bundle provided by Kühling&Kühling for 
their HT500.3 3D printers. Use them as they are with Kühling&Kühling filaments
or take the configuration as a starting point for your individual needs.

All information about the machine is available at
[http://kuehlingkuehling.de](http://kuehlingkuehling.de).

## Profiles

The following profiles are included within the bundle .ini:

#### PRINT presets
* **SOLID**
a configuration for solid objects, suited for mechanically loaded and tough parts.
* **SOLID (soluble support)**
a special configuration for solid objects, prepared for printing soluble support structures in a different material with the second extruder.
* **SOLID (soluble support no raft)**
a special configuration for solid objects, prepared for printing soluble support structures in a different material with the second extruder.
* **SOLID (bicolored)**
a special configuration for dual color printing, to be used with *bicolored* dual extrusion printer profile.
* **ECO**
a lighter configuration, using 30% triangular infill to save weight and material.
* **ECO (bicolored)**
a special configuration for dual color printing, to be used with *bicolored* dual extrusion printer profile. Lighter configuration, using 30% triangular infill to save weight and material.

#### FILAMENT presets
* **Polymaker PolyLite ABS**
* **Polymaker PolyLite PC (transparent)**
* **Polymaker PolyMax PC (black or white)**
* **HIPS**
* **PVA natural**
* **igus® iglidur® 180-PF**

Refer to our manual at http://docs.kuehlingkuehling.de for further information on printing with these materials.

#### PRINTER presets
* **LEFT EXTRUDER ONLY (nozzle 0.35)**
for using left extruder only in single extruder print, right extruder unused, nozzle 0.35 mm
* **LEFT EXTRUDER ONLY (nozzle 0.5)**
for using left extruder only in single extruder print, right extruder unused, nozzle 0.5 mm
* **RIGHT EXTRUDER ONLY (nozzle 0.35)**
for using right extruder only in single extruder print, left extruder unused, nozzle 0.35 mm
* **RIGHT EXTRUDER ONLY (nozzle 0.5)**
for using right extruder only in single extruder print, left extruder unused, nozzle 0.5 mm
* **DUAL EXTRUDER (nozzles 0.35+0.35)**
a dual extruder setup for printing bicolored models or soluble support structures using a different filament in each extruder. Nozzles 0.35 mm on each extruder.
* **DUAL EXTRUDER (nozzles 0.5+0.5)**
a dual extruder setup for printing bicolored models or soluble support structures using a different filament in each extruder. Nozzles 0.5 mm on each extruder.

## Installation

**Attention:** When importing this profile bundle into PrusaSlicer, existing presets may be overwritten. It is recommended to backup your custom/modified presets by exporting them as a bundle first (*File > Export Config Bundle*)

**Compatibility:** PrusaSlicer 2.2.0-beta or higher

To install the provided configuration bundle to your PrusaSlicer installation, load the .ini file through the Menu *File > Import > Import Config Bundle*.


## Current Version

The latest release of the profile bundle, conveniently packaged as a downloadable archive file 
can be found at [https://github.com/kuehlingkuehling/KuehlingKuehling-Slic3r-profiles/releases](https://github.com/kuehlingkuehling/KuehlingKuehling-Slic3r-profiles/releases)
Always check for compatibility with your specific model and machine revision as well as software/firmware and PrusaSlicer versions in the release notes to each bundle!

## Author

These profiles are developed by Kühling&Kühling GmbH, Christianspries 30, 24159 Kiel (Germany)

## License

This work is licensed under the Creative Commons
Attribution-ShareAlike 4.0 International License. 
To view a copy of this license, visit 
[http://creativecommons.org/licenses/by-sa/4.0/](http://creativecommons.org/licenses/by-sa/4.0/) or 
send a letter to Creative Commons, 444 Castro Street,
Suite 900, Mountain View, California, 94041, USA.
