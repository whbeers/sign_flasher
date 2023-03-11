# Transistor-driven 555 LED flasher

This is a simple LED driver circuit using two 555s and a pair of NPN/PNP transistors to drive several LEDs meant to outline a small sign. Designed with my son for a St Patrick's Day project, in [KiCAD](https://www.kicad.org). 

![Front render](renders/front.png)
![Back render](renders/back.png)
![Schematic SVG](schematics/sign_flasher-latest.svg)
[Schematic PDF](schematics/sign_flasher-latest.pdf)

## Credit
The underlying circuit is based on [a 555 schematic](https://mechatrofice.com/circuits/555/led-flasher-circuit) I found when searching for circuits that would fulfill the design requirements given to me by my son.

Trimpot symbol, footprin, and 3D model courtesy of [SnapEDA](https://www.snapeda.com/parts/3306F-1-103/Bourns/view-part/). [Additional license details](hardware/TRIM_3306F.txt)

## Versioning

My pcb designs utilize the following versioning scheme (I'll add to this as I produce more revisions):
 - v0.0XX: A candidate design that has not yet been produced and tested.
 - v0.XX: A design that has been produced, tested, and any initial errors addressed.
