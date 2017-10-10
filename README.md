# 3D Prints 
_updated 10/10/2017_
repository for all my 3D-Prints


## 3D printing setup


### 3D Printer: _Monoprice Select Mini 3D Printer V2, White_
- **Firmware 29.42** <br />
https://www.mpselectmini.com/
- **glass bed** 
The glass is from an old picture frame. held on with binder clips on one side and 3d printer clips on the other side. I lowered the print bed to accommodate the width of the glass. The amount of space between the nozzle and the gaff tape is the width of a paper. It should barely fit under with a bit of force.
- **Gaff tape on the glass bed** 
  * Durable. 
  * prints will stick to it. 
  * Doesn't damage the glass. 
  * Doesn't need to be cleaned. 
  * Easy to remove.
- **custom 3d printed glass bed clips**


### Modeling Software: _FreeCAD_
I model the prints in here, export to .stl, then put the .stl files through a slicing software


### Slicing Software: _Cura 2.7.0_
**IMPORTANT BUG** _between Monoprice Select Mini V2 and Cura 2.7.0_
If the .gcode file is saved directly to the removable microSD card then it will cause the printer to continuously move toward the top right hand corner of the the print bed. It tries to force itself out of the print bed. Very bad for the printer.

The **workaround** is to save the .gcode to the computer then move it to the microSD card. Don't know how that works but it just does.


### Slicer settings
**Quality** <br />
-- Layer Height: 0.0875mm <br />
**Material** <br />
-- Build Plate temp: 50C <br />
**Speed** <br />
-- Print Speed: 40 mm/s <br />
-- TravelSpeed: 100 mm/s <br />
-- Enable Jerk Control: True <br />
**Cooling** <br />
-- Regular Fan Speed: 80% <br />
**Support** <br />
Depends based on the print. Be sure to check the overhangs. <br />
**Build Plate Adhesion** <br />
-- Build Plate Adhesion Type: raft <br />
-- Raft Extra Margin: 3 mm <br />
-- Raft Air Gap: 0.2 mm <br />
**Extruder temp** <br />
-- PLA: 200C <br />




















