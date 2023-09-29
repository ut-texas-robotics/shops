# Prusa Mk3S+ Startup Guide

This article goes over the Prusa Mk3S+ machines in the DigiFab lab (AHG 1.106). 

## Getting Started

### I. PrusaSlicer installation

We have two desktop computers in the DigiFab lab that are available for user usage. These desktops have the required software installed on them,
but many users prefer to install the software on their own computers for ease of access. If you do not wish to go through the installation process,
proceed to Step II.

+ Install PrusaSlicer to your local machine (Supports Windows/Mac/Linux): https://www.prusa3d.com/page/prusaslicer_424/
+ Open PrusaSlicer
+ In the top right of the screen, under select the option "Original Prusa i3 MK3S & MK3S+" to configure your slicer for the printers in the lab.
<p align="center">
<img src="../img/prusa/PrusaConfig.PNG" width="400" height="300">
</p>

### II. PrusaSlicer Walkthrough

To import your model to PrusaSlicer, either drag-and-drop your file into PrusaSlicer, or select Add [Ctl+I] to select your file. File must be a .stl filetype.

If successfully imported, you will see your model on the digital printbed. From here, you may wish to use the layout options on the right side of the screen to
move/rotate your model. You may also import more than one model at a time to print.
<p align="center">
<img src="../img/prusa/modelOnBed.PNG" width="400" height="300">
</p>

Once your model(s) have been located and oriented, adjust your print settings and verify that they are appropriate for your current print. Verify that the 
filament settings matches the type of filament that you intend to print with. If you want, adjust the layer height (Print Settings) and infill. Standard layer height
is between 0.15-0.2mm with 15% infill. 
<p align="center">
<img src="../img/prusa/Settings.PNG" width="700" height="250">
</p>

If you want more in-depth settings, you can access the full print settings by selecting "Print Settings" at the top.
<p align="center">
<img src="../img/prusa/PrintSettings.PNG" width="400" height="280">
</p>

When you are ready to print, select "Slice Now" in the bottom right of the screen. This will slice your model and prepare the g-code for printing.
You can scrub through print layers using the orange slider to the side and bottom of the view screen. If everything looks correct, select "Export g-code"
to save the g-code for the print. This is the file that you will transfer to the printer itself.
<p align="center">
<img src="../img/prusa/SliceNow.PNG" width="400" height="300">
</p>

### III. Starting a Print

