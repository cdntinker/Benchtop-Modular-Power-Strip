# The hardware (duh...)

Each folder here is a standalone KiCAD project for a part of this overall system.

(Tho **KiCAD Customs** is a special case, it contains custom libraries used in this project & **Retired Parts** is aptly named....)

## Backplane
This is the "daisy-chainable" backplane for the modules to plug into.

## Module - *
To create a new module... Just copy one of the **WIP - Prototyping Module** folders, do some renaming & go from there.
* Module - TPS540x
  - a fixed voltage output module based on the TPS540x family of chips.
  - Basic design has dual circuits
  - Options for USB-A/C combo footprint or Barrel/XT30 combo footprint
* Module - USB QC
  - A QC 2.0 output module
* Module - USB PD Source
  - Take a guess...
  - (I _think_ I've got this one worked out...)
* Module - Adjustable single rail PSU
  - a fixed voltage output module based on the LM2596S

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
  
