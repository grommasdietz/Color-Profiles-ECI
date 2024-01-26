# Color Profiles: ECI

This repository provides an organized collection of color profiles from the European Color Initiative (ECI). It’s intended to be installed for Adobe Creative Cloud, but can be adapted for any other workflow. The set contains all current profiles as well as ECI Offset 2009 for legacy reasons. It’s the base for the optional available Adobe CC [color settings](https://github.com/grommasdietz/color-settings/).

## Table of Contents

- [Color Profiles: ECI](#user-content-color-profiles-eci)
  - [Collection](#user-content-collection)
    - [Exchange](#user-content-exchange)
    - [Finishing](#user-content-finishing)
    - [Gravure](#user-content-gravure)
    - [Legacy](#user-content-legacy)
    - [Metal](#user-content-metal)
    - [Offset](#user-content-offset)
    - [RGB](#user-content-rgb)
  - [Installation](#user-content-installation)
    - [MacOS](#user-content-macos)
    - [Windows](#user-content-windows)
      - [Windows XP and Vista](#user-content-windows-xp-and-vista)
      - [Windows 7, 8 and 10](#user-content-windows-7-8-and-10)
      - [Windows 10+](#user-content-windows-10)
  - [Contributions](#user-content-contributions)
  - [Further Information](#user-content-further-informations)

## Collection

### Exchange
1. eciCMYK v2 (2020)  
   *For color exchange in CMYK workflows*

### Finishing
1. PSO Coated v3 Glossy laminate (2020)  
   *For glossy laminate finishing*
2. PSO Coated v3 Matte laminate (2020)  
   *For matte laminate finishing*

### Gravure
1. PSR LWC PLUS V2 M1 v2 (2020)  
   *For gravure printing on LWC PLUS paper, M1 viewing conditions*
2. PSR LWC STD V2 M1 (2020)  
   *For standard gravure printing on LWC paper, M1 viewing conditions*
3. PSR MF V2 M1 (2020)  
   *For gravure printing on MF paper, M1 viewing conditions*
4. PSR SC PLUS V2 M1 (2020)  
   *For gravure printing on SC PLUS paper, M1 viewing conditions*
5. PSR SC STD V2 M1 (2020)  
   *For standard gravure printing on SC paper, M1 viewing conditions*

### Legacy
1. ISO Coated v2 (ECI)  
   *Legacy profile for coated paper*
2. ISO Coated v2 300% (ECI)  
   *Legacy profile for coated paper with max. 300% ink coverage*
3. PSO LWC Improved (ECI)  
   *Legacy profile for PSO LWC Improved paper*
4. PSO LWC Standard (ECI)  
   *Legacy profile for PSO LWC Standard paper*
5. PSO Uncoated ISO12647 (ECI)  
   *Legacy profile for PSO Uncoated ISO12647 paper*
6. ISO Uncoated Yellowish (ECI)  
   *Legacy profile for ISO Uncoated Yellowish paper*
7. SC Paper (ECI)  
   *Legacy profile for SC paper*
8. PSO MFC Paper (ECI)  
   *Legacy profile for PSO MFC (Machine Finished Coated) paper*
9. PSO SNP Paper (ECI)  
   *Legacy profile for PSO SNP (Super News Print) paper*
10. PSO Coated NPscreen ISO12647 (ECI)  
    *Legacy profile for PSO Coated NPscreen ISO12647*
11. PSO Coated 300% NPscreen ISO12647 (ECI)  
    *Legacy profile for PSO Coated 300% NPscreen ISO12647*
12. PSO Uncoated NPscreen ISO12647 (ECI)  
    *Legacy profile for PSO Uncoated NPscreen ISO12647*

### Metal
1. Metal Printing MPC1 FOGRA60 (2022)  
   *For metal printing on FOGRA60 complant substrates*

### Offset
1. PSO Coated v3 (2015)  
   *For offset printing with coated substrates*
2. PSO Uncoated v3 (FOGRA52) (2015)  
   *For offset printing on uncoated substrates, FOGRA52 standards*
3. ISO Coated v2 to PSO Coated v3 (DeviceLink) (2015)  
   *DeviceLink profile for converting from ISO Coated v2 to PSO Coated v3*
4. PSO Coated v3 to ISO Coated v2 (DeviceLink) (2015)  
   *DeviceLink profile for converting from PSO Coated v3 to ISO Coated v2*
5. PSO SC-B Paper v3 (2017)  
   *For offset printing on supercalendered bulky paper*

### RGB
1. eciRGB v2 ICCv4 (2007)  
   *For accurate color representation in RGB workflows, ICC version 4 standards*
2. eciRGB v2 (2007)  
   *For color accuracy and consistency in RGB workflows*

## Installation

Copy all folders and files to the corresponding paths:

### MacOS
```
/Library/ColorSync/Profiles
```

1. Copy the path and use `⇧ Shift + ⌘ Command + G` on finder for "Go to folder…". Then paste and enter to open Profiles folder.
2. Copy the folders from the downloaded repository, go to the Profiles folder and use `⌥ Option/Alt + ⌘ Command + V` to merge.

### Windows

#### Windows XP and Vista
```
C:\Windows\System32\Spool\Drivers\Color
```

#### Windows 7, 8 and 10
```
C:\Windows\System32\spool\drivers\color
```

#### Windows 10+
Starting from Windows 10, you can manage color profiles through the Settings app:
1. Open Settings
2. Go to System
3. Select Display from the left sidebar
4. Scroll down and click on Advanced display settings
5. Under Color settings, you'll find a link to Color management

## Contributions

Contributions are welcome! If you encounter problems or have suggestions for improvements, feel free to create an issue.

## Further informations
For more detailed information and documentation, visit [European Color Initiative (ECI)](http://www.eci.org).
