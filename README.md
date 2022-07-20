# PCB2STL
A Blender3D-File (>=V3.3a) to convert a PCB bitmap file (png) to STL (0,05mm hight)

To exposure Photo Coated PCB Material on a MSLA printer like ELEGOO Mars 2 Pro it is necessary to convert the PCB layout to a STL file with hight information.
This Bender3D file can convert a PCB bitmap file to a STL file with the minimal standard height of the first print layer (0.05mm height). So it is easily possible to set the total exposure time by setting up the first layer exposure time in chitubox.

In PCB designer like KiCAD or Easy EDA it is possible to export a PCB layout to SVG. Open the SVG file in InkScape, export it to PNG considering the correct DPI of the MSLA printer display (Elegoo Mars 2 Pro = 540 DPI).
Load this PNG file into the Blend file as follows:

![png2stl_info](https://raw.githubusercontent.com/MoonMoon82/PCB2STL/main/info/pcb2stl_info.png)
