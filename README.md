# HT500/HT500.2 Slic3r profiles

This is the latest Slic3r configuration profile bundle provided by Kühling&Kühling for 
their HT500/HT500.2 3D printers. Use them as they are with Kühling&Kühling filaments
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
a lighter configuration, using 15% hexagonal infill to save weight and material.
* **ECO (bicolored)**
a special configuration for dual color printing, to be used with *bicolored* dual extrusion printer profile. Lighter configuration, using 15% hexagonal infill to save weight and material.

#### FILAMENT presets
* **Kuehling&Kuehling ABS snow-white**
* **Kuehling&Kuehling ABS red**
* **Kuehling&Kuehling ABS black**
* **Kuehling&Kuehling HIPS**
* **Kuehling&Kuehling PA natural**
* **Kuehling&Kuehling PVA natural**
* **Polymaker PC-Max**
* **Polymaker PC-Plus**
* **igus® iglidur® 180-PF**

Refer to our manual at http://docs.kuehlingkuehling.de for further information on printing with these materials.

#### PRINTER presets
* **LEFT EXTRUDER ONLY**
for using left extruder only in single extruder print, right extruder unused
* **RIGHT EXTRUDER ONLY**
for using right extruder only in single extruder print, left extruder unused
* **DUAL EXTRUDER (bicolored, nozzles 0.35+0.35)**
a dual extruder setup for printing bicolored models using a different filament in each extruder. Refer to the manual regarding further information on setting up bicolored models in Slic3r.
* **DUAL EXTRUDER (soluble support, nozzles 0.35+0.5)**
special dual extruder preset for printing parts with soluble support structures. Install a 0.35mm nozzle on the left extruder (model material) and use a 0.5mm nozzle on the right extruder (support material). Tried and tested for ABS models printed with HIPS supports. Refer to the manual regarding further information on this topic.

## Installation

**Attention:** When importing this profile bundle into Slic3r, existing presets may be overwritten. It is recommended to backup your custom/modified presets by exporting them as a bundle first (*File > Export Config Bundle*)

**Compatibility:** Slic3r Prusa Edition 1.41.0-beta or higher

To install the provided configuration bundle to your Slic3r installation, load the .ini file through the Menu *File > Load Config Bundle*.


## Current Version

The latest release of the profile bundle, conveniently packaged as a downloadable archive file 
can be found at [https://github.com/kuehlingkuehling/KuehlingKuehling-Slic3r-profiles/releases](https://github.com/kuehlingkuehling/KuehlingKuehling-Slic3r-profiles/releases)
Always check for compatibility with your specific model and machine revision as well as software/firmware and Slic3r versions in the release notes to each bundle!

## Author

These profiles are developed by Kühling&Kühling GmbH, Christianspries 30, 24159 Kiel (Germany)

## License

This work is licensed under the Creative Commons
Attribution-ShareAlike 4.0 International License. 
To view a copy of this license, visit 
[http://creativecommons.org/licenses/by-sa/4.0/](http://creativecommons.org/licenses/by-sa/4.0/) or 
send a letter to Creative Commons, 444 Castro Street,
Suite 900, Mountain View, California, 94041, USA.
