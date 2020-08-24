# Duet-Maestro-Menu

A set of files to allow a Duet Maestro to present a basic menu system on a 12864 reprap graphic display.

## Changes from the original

I took out a bunch of stuff I don't need, and simplified what was left. I used the larger font here and there to break things up a bit.

* Removed support for bed probing because I use a simple Z endstop
* Removed BLTouch support because I am struggling to justify the cost
* Consolidated and simplified many settings, removed as much duplication as possible
* Changed "cancel" to "Fuck" but then thought better of it and went with "Abort"
* Added an icon for mm/s which was a pain to create with a calculator and a text editor. Does anyone know a simpler way to make RRF graphics? I'm working on a python thingo but it's not a high priority today

## Installation

Create a `/Bed` folder insude your `/macros` folder and fill it with the files in this `macros/Bed`. Edit them to make sure the bed levelling happens where you want it to - these defaults place the nozzle above the bed screws on a Creality CR10S.

Upload the rest of the files to your /menu folder. Beware, any existing files with the same name will be overwritten, so you might want to back them up first.