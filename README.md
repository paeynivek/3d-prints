# 3D Prints 
_updated 10/10/2017_
repository for all my 3D-Prints


## 3D printing setup


### 3D Printer: _Monoprice Select Mini 3D Printer V2, White_
- **Firmware 29.42** <br />
https://www.mpselectmini.com/
- **glass bed** 
The glass is from an old picture frame. held on with binder clips on each side. I lowered the print bed to accommodate the width of the glass. bed is raised until it just barely touches the bed at each corner.
- **Gaff tape on the glass bed** 
  * Durable. 
  * good first layer adhesion. 
  * Doesn't damage the glass. 
  * Doesn't need to be cleaned. 
  * Easy to remove.


### Modeling Software: _FreeCAD_
I model the prints in FreeCAD, export to .stl, then put the .stl files through a slicing software


### Slicing Software: _Cura 2.7.0_
**IMPORTANT BUGS** _between Monoprice Select Mini V2 and Cura 2.7.0_
Two senarios resulting in the same bug. Printer nozzle will continuously move toward the top right hand corner of the the print bed. It tries to force itself out of the print bed. Very bad for the printer. 

**Senario 1**: the .gcode file is saved directly onto the removable microSD card <br>
**workaround**: is to save the .gcode to the computer then move it to the microSD card.

**Senario 2**: a print is canceled and one attempts to start a new print. <br>
**workaround**: reset the printer. turn it off then back on.

### Slicer settings
**Quality** <br>
-- Layer Height: 0.0875mm <br>
**Material** <br>
-- Build Plate temp: 50C <br>
**Speed** <br>
-- Print Speed: 40 mm/s <br>
-- TravelSpeed: 100 mm/s <br>
**Cooling** <br>
-- Regular Fan Speed: 80% <br>
**Support** <br>
-- Depends based on the print. Be sure to check the overhangs. <br>
**Build Plate Adhesion** <br>
-- Build Plate Adhesion Type: raft <br>
-- Raft Extra Margin: 2 mm <br>
-- Raft Air Gap: 0.2 mm <br>
-- Raft base thickness 0.18 <br>
**Extruder temp** <br>
-- PLA: 200C <br>

