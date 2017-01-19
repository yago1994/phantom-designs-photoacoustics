# phantom-designs-photoacoustics
This repository contains the 3D designs of the phantoms used in "The Development and Characterization of a Novel yet Simple 3D Printed-based Phantom to Validate Photoacoustic Contrast Agents"
and some of their variations that we don't mention in the paper. Please feel free to use the files and modify them to your convenience.

The files are in different formats, you may choose the one most suited for your application. As an overview: 
.stl is the file you would want to use with a "slicer" software; it is the software that prepares the files for 3D printing. Some printers have their own personalized "slicer" software that prepares the file for a specific printer, for example MakerBot. But there are many others that use .gcode format and that can be prepared by a variety of different free softwares, such as Cura or Slic3r. Cura has the easiest interface use out of the two.
.step will let you import the file into a variety of CAD editors and then make changes on top of this file. 
.f3d is the file exported directly from Autodesk Fusion 360. Importing the file will allow you to see the timeline of changes and edit any parameters. Importing the specific file for each CAD software will make it easier to modify the designs. 

The files named phantom_v2 include the phantom presented in the paper, it includes 14 insertion pockets.

The files named phantom_gradient include the depth phantom used for the depth experiment.

The files named phantom_v3 include a version of the phantom not shown in the paper. In this version we removed the separation walls in between the holes to allow tighter packing. When we tested it we managed to fit 15 tubes in the transducer's visual field.

