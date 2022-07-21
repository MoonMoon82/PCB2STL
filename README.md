# PCB2STL
A Blender3D-File (>=V3.3a) to convert a PCB bitmap file (PNG) to STL (0,05mm height)

To exposure photo coated PCB material on a MSLA printer like the ELEGOO Mars Pro it is necessary to convert the PCB layout to a STL file with height information.
This Bender3D file converts a PCB bitmap file (PNG) to a STL file with the minimal standard height of the first print layer (0.05mm). So it is easy to set the total exposure time by setting up the first layer exposure time in Chitubox.

In PCB designer like KiCAD or Easy EDA it is possible to export a PCB layout to SVG. Open the SVG file in InkScape, export it to PNG considering the correct DPI of the MSLA printer display (Elegoo Mars Pro ~ 540 DPI).
Load this PNG file into the Blend file as follows:

![png2stl_info](https://raw.githubusercontent.com/MoonMoon82/PCB2STL/main/info/pcb2stl_info.png)
