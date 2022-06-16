# Installation

BtoA is supported on Windows, macOS, and Linux.

## System Requirements
* Blender 2.93 LTS or later
* OS 10.11 or later
* Windows 10 or later, with the Visual Studio 2015 redistributable
* Linux with at least glibc 2.12 and libstdc++ 3.4.13 (gcc 4.4.7). This is equivalent to RHEL/CentOS 6.

For more information, see the system requirements for Arnold on the [Autodesk website](https://www.autodesk.com/products/arnold/subscribe?plc=ARNOL&term=1-YEAR&support=ADVANCED&quantity=1).

!!! note
    In the past, we've asked users to install the Arnold SDK separately to configure BtoA. As of BtoA 0.5.0 beta, this is no longer necessary as all Arnold dependencies are included in the release.

## Installing in Blender
1. Download the latest release from [GitHub](https://github.com/lunadigital/btoa/releases), or pick a development branch to build and try out.
2. Open Blender and install the add-on zip file through `Edit > Preferences > Add-ons > Install`.
3. Enable the Arnold for Blender (BtoA) add-on.

## Building from source