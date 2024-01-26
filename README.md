# Color Profiles: ECI

This repository provides an organized collection of color profiles from the European Color Initiative (ECI). It’s intended to be installed for Adobe Creative Cloud, but can be adapted for any other workflow. The set contains all current profiles as well as ECI Offset 2009 for legacy reasons.

## Table of Contents

- [Color Profiles: ECI](#user-content-color-profiles-eci)
  - [Details](#user-content-details)
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

## Details

### Exchange
Exchange contains 1 ICC profile (2020):
- eciCMYK v2

### Finishing
Finishing contains 2 ICC profiles (2020):
- PSO Coated v3 Glossy laminate
- PSO Coated v3 Matte laminate

### Gravure
Gravure contains 5 ICC profiles (2020):
- PSR LWC PLUS V2 M1 v2
- PSR LWC STD V2 M1
- PSR MF V2 M1
- PSR SC PLUS V2 M1
- PSR SC STD V2 M1

### Legacy
Legacy contains 11 ICC profiles based on ECI Offset (2009):
- ISO Coated v2 (ECI)
- ISO Coated v2 300% (ECI)
- PSO LWC Improved (ECI)
- PSO LWC Standard (ECI)
- PSO Uncoated ISO12647 (ECI)
- ISO Uncoated Yellowish
- SC Paper (ECI)
- PSO MFC Paper (ECI)
- PSO SNP Paper (ECI)
- PSO Coated NPscreen ISO12647 (ECI)
- PSO Coated 300% NPscreen ISO12647 (ECI)
- PSO Uncoated NPscreen ISO12647 (ECI)


### Metal
Metal contains 1 ICC profile (2022)
- Metal Printing MPC1 FOGRA60


Offset contains 5 ICC profiles (2015–2017):
- PSO Coated v3
- PSO Uncoated v3 (FOGRA52)
- ISO Coated v2 to PSO Coated v3 (DeviceLink)
- PSO Coated v3 to ISO Coated v2 (DeviceLink)
- PSO SC-B Paper v3

### RGB
RGB contains 2 ICC profiles (2007) and 1 license
- eciRGB v2 ICCv4
- eciRGB v2

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
