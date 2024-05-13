# The hardware (duh...)

Each folder here is a standalone KiCAD project for a part of this overall system.

(Tho **KiCAD Customs** is a special case, it contains custom libraries used in this project & **Retired Parts** is aptly named....)

## Backplane
This is the "daisy-chainable" backplane for the modules to plug into.

## Module - *
To create a new module... Just copy one of the **WIP - Prototyping Module** folders, do some renaming & go from there.
* Module - TPS540x
  - a fixed voltage output module based on the TPS540x family of chips.
  - Can be populated with either the 3v3 or 5v0 version (possibly others if they exist)
  - Basic design has dual circuits
  - Options for USB-A/C or XT30 combo footprint
* Module - LM2596S
  - a fixed voltage output module based on the LM2596S
  - Output voltage(s) set via resistors R502/R503 & R602/603
  - Basic design has dual circuits
  - Options for USB-A/C or XT30 combo footprint
* Module - USB QC
  - A QC 2.0 output module
* Module - USB PD Source
  - Take a guess...
  - (I _think_ I've got this one worked out...)

## Master Control Modules
* Controller - ATTiny
  - So far, this is the default.
  - (Seeing as it's basically the same controller as all the modules with USB added...)
* Controller - ESP32
  - WIP
* Controller - ESP8266
  - WIP
* Controller - RP2040
  - WIP

## Testing & Prototyping Modules
* WIP - Prototyping Module
  - Another option as a new module starting point...
* WIP - **Sumpin Random**
  - Could be anything I'm still working through...
* Module - ATTiny Breakout
  - Sort of a module for messing about with the ATTiny...
* Tool - ATTiny Module Flasher
  - A UPDI Module flashing tool
* Tool - ESP Module Flasher
  - An offshoot of the ATTiny Module Flasher
  
