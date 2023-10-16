# FormLabs Form3 and Form3BL Startup Guide

This article goes over the FormLabs SLA machines in the DigiFab lab (AHG 1.106). 

## Getting Started

### I. PreForm installation

We have two desktop computers in the DigiFab lab that are available for user usage. These desktops have the required software installed on them, but many users prefer to install the software on their own computers for ease of access. If you do not wish to go through the installation process, proceed to Step II.

+ Download PreForm: https://formlabs.com/software/preform/ (Supports Windows and Mac)


### II. Setting Up a Print in PreForm

PreForm is the slicer software for the Formlabs printers. As with other printer slicers, you will start by uploading your .STL file either by dragging it onto the PreForm screen or by selecting "Add File" on the top bar. If you are not yet connected to the printer you plan to use, make sure the correct printer (Form 3+ or Form 3BL) is selected in the top right to ensure the proper bed dimensions are imported.

**add picture: PreForm_InitialPrint**

Note the error window on the right side of the screen. As we have not added supports so far, we will likely see an error regarding the need for more support. Red shading on the part indicates regions that need more supports. Additionally, when resin printing, a raft will be added when supports are generated. This is essential as printing the model directly on the bed may cause over-adhesion meaning that you would be unable to remove your part without damaging it or the bed. 

To prepare your part for printing, you can either manually position and add supports or simply use the One Click Print(P) feature. This feature can be used by selecting the wand at the top of the side bar. This will automatically orient and support your print for ideal results. If you wish to adjust the settings, you can do this using the Orientation(O) and Supports(C) tabs.

Before starting your print, double check the Print Validation section to confirm that you don't have any errors. If you do, read the warnings on the right side and adjust accordingly. Usually these errors will come in the form of lack of support or a warning against printing directly on the build platform. If you get an error regarding cupping, you may need to reorient or redesign your model to account for this. Read more about cupping here (uncommon issue, usually only occurs with large empty volume areas on parts): https://support.formlabs.com/s/article/Cupping-Blowout?language=en_US

### III. Starting a Print

Once your print file is ready and you have no errors under Print Validation, you will need to connect to the machine via the usb cable on the back of it. If using the desktop workstation, verify that the usb cable is connected to the computer before continuing.

Once connected, you should see the printer name appear on PreForm. The Form 3+ is named "ActiveLoach" and the Form 3BL is named "OvertGharial."

Select which resin material you wish to use if you have not done so already. Do this by selecting the printer box in the top right of the Job Setup screen. Verify that the resin selected in PreForm matches both the resin loaded into the printer and the resin currently in the tank. Note that each tank can only ever support one type of resin, so for materials that do not currently have a dedicated tank, a new one will need to be purchased.

Next you will need to select the layer thickness you wish to print with. Different resin materials will have different options, but most will have an additional "Adaptive" layer thickness option. By selecting Adaptive layer thickness, the print will vary the layer thickness according to part geometry to print at a smaller layer height in more detailed areas and a larger height in less detailed areas in an effort decrease print time while maintaining part quality.

Once you are satisfied with the print settings, select "Apply" and you can send your print to the machine. Press the orange circle with a picture of the printer to open the print menu. If you are properly connected to the printer, it's name should appear at the top. To send the print to the printer, select "Print Now."

Once a print has been sent to the printer, it will pop up on the printer's screen. Press the "Print" button and follow the steps as detailed on the screen to complete the print priming process. Once complete, the printer will begin mixing the tank and adding more material if necessary.

Once the printer verifies that the tank is filled to the appropriate height, the printer will automatically begin printing. The print bed will be submerged into the tank of resin and the UV light underneath will begin printing the model(s) layer by layer. Note the circles on the screen for estimated print time. If all looks well and no error messages pop up, you are welcome to leave the printer working at this point.

### IV. Removing, Cleaning, and Curing Print

#### Removing Parts
Once the part has finished printing, it will need to be removed from the print bed. Remove the print bed by lifting the lever and carefully removing the bed, keeping in mind that the bed and parts on it are still not fully cured and very sticky. Be mindful of where you put it, making sure to clean up after if any mess is made in the lab. It is reccomended to wear gloves when working with uncured resin parts.

To remove the parts, use the scraper tool next to the printers. Do not use scrapers that are intended for FDM printers as the resin can stick and cause damaged to those machines. With the parts removed, you will now need to clean them.

#### Cleaning Parts
There are multiple methods to clean parts. Firstly, if the cleaning station in the DigiFab lab has solvent in it, you can simply put your parts in the basket and run the machine for 10 minutes. If there is no solvent in the machine, you will need to manually wash your parts.

To manually clean your parts, it is reccomended to submerge them in isopropyl alcohol (or other approved solvent) for 10 minutes, agitating the mixture occasionally. Note that the isopropyl alcohol can be used to wash multiple parts, so it may be beneficial to put it back into a sealed container to prevent waste. 

Once the part(s) have been washed, allow them to dry completely before placing them in the curing station.

#### Curing Parts
Curing resin printed parts strengthens them and locks in the ideal mechanical properties, so it is always reccomended to cure your parts. To cure, simply place the parts in the curing station and select the material they are made of on the digital screen. Finally, press "Start," and the machine will begin curing the parts. 

It will always begin with a pre-heat cycle, and then run a curing cycle. For most materials, the total curing time will be less than an hour. Upon completion, the parts will be ready to be removed and will be completed. Note that parts may still be warm immediately following completion of a curing cycle.
