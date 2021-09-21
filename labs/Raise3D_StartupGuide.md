# Raise3D Pro-2 Plus

This article goes over the Raise3D Pro-2 Plus 3D printer in the RPL. Since the station does not yet have a dedicated workstation, you must use your own laptop to begin a print.

## Getting Started

### I. ideaMaker installation

+ Install ideaMaker to your local machine: https://www.raise3d.com/downloads/
+ When launching ideaMaker for the first time, you will need to select your printer model and filament diameters for this device.
  - Printer Type: Raise3D Pro2 Plus
  - Left Extruder Filament: PLA 1.75 mm
  - Right Extruder Filament: PLA 1.75 mm

Note that all Pro-2 Series printers use 1.75 mm filaments.

### II. Importing a Model

+ Select `Import Model` and select your .STL file. 
  - To export .STL files from SOLIDWORKS: https://www.cati.com/blog/2016/06/exporting-stl-files-from-solidworks-for-3d-printing/
+ If successfully imported, your model should be seen in the ideaMaker workspace. Select which extruder you plan to print with. Default is left extruder. 
+ From here, you can rotate or translate your model as needed using the tools located on the top toolbar.
  - It may be beneficial to rotate your model to decrease printing time and required supports.
+ If you are importing multiple models, ensure that they are not touching.
  - When spacing models, it is reccomended to provide at least 10 mm of space in between each model.
  - Verify that all models are placed correctly on the build plate. This can be done by setting the *Z* position of each model to 0.

### III. Slicing a Model

Once your model is setup and ready to print, select `Start Slicing`

From here, you will be presented a variety of standard slicing templates. Note that the higher the quality of print, the longer the print will take. Additionally, verify the type of filament is correct for each extruder. Proceed with the following instructions to setup print for chosen template.

![PrintGuide1](https://user-images.githubusercontent.com/87148770/134209686-c060927a-1234-4537-8033-d27104fe2304.jpg)
![PrintGuide2](https://user-images.githubusercontent.com/87148770/134209697-2ea44c09-4b9a-4d44-a641-cf6eb73d6fc4.jpg)
![PrintGuide3](https://user-images.githubusercontent.com/87148770/134209699-617aeaa2-6555-40da-92c3-345d54362bce.jpg)


*Note: Verify these settings every time you print.*



Once you have validated your print settings, select `Slice`

### IV. Exporting a Model

Upon slice completion, an estimated time, cost, and filament usage will be provided.
+ Click `Preview`
  - From here, you can scrub through the print layers to validate your print.
+ Take note of the estimated filament usage. Each spool on the Pro2-Plus can hold 1kg of filament when new. To prevent possible print failure, ensure that there is enough filament left on the spool to complete your print.
+ Once ready to export, select 'Export to Local Disk' and save to external USB storage device.
  - Name file as `LastName-ModelName.gcode`

### V. Printing your Model

With the .gcode and .data files exported to your USB storage device, insert the USB device into the USB slot on the Pro2-Plus located on the side of the touchscreen.
+ Select `Print`
+ Select `USB Storage`
+ Select your model
  - Check printing parameters and settings
+ Select `Print` to start printing the model

*Note: When viewing your model, verify that only the chosen extruder will be consuming filament.*

Once a print has begun, the print bed and corresponding extruders will begin to heat up. *Verify that only the desired extruder is being heated. Otherwise, review print settings.*
After both the print bed and extruder(s) are at temperature, the print will begin. 

*IMPORTANT: Watch printer until at least the first print layer has gone down before leaving the Digifab lab*

### VI. Removing a completed print

+ Upon completion of print, use touchscreen to indicate success or failure of print.
+ Allow print bed to cool down and unscrew the two red screws holding the bed in place.
+ Carefully remove the print bed from the printer and place on a workstation to remove model.
+ After carefully removing print taking precaution to not damage the print bed, place the print bed back and retighten the screws. Do not overtighten.


## Additional Resources

Below are additional details which may be beneficial in addition to the information provided in the `Getting Started` section above.

### Platform Addition

When setting up your print, you may want to use a platform to ensure a clean first print layer, to provide a solid base for taller prints, and/or to ensure proper bed adhesion. In order to modify the platform addition settings, select `Platform Additions` in the Advanced Settings menu when slicing your model.

![PlatformAdditions](https://user-images.githubusercontent.com/87148770/134209618-1f79026e-d506-4398-8cf4-ffeb83d88d14.jpg)


### Dual Extruder Printing

The Raise3D Pro2-Plus is capable of dual extruder printing. To setup a series of models for dual-extruder printing, follow the instructions below:

![DualExtrude1](https://user-images.githubusercontent.com/87148770/134209544-8c6ddaba-d701-4a97-9d0d-b311a53b9598.jpg)
![DualExtrude2](https://user-images.githubusercontent.com/87148770/134209559-34f16259-77ff-427b-beee-27ebd34b71ca.jpg)
![DualExtrude3](https://user-images.githubusercontent.com/87148770/134209568-3f73712f-e20b-451f-84ce-00eee745e36d.jpg)
![DualExtrude4](https://user-images.githubusercontent.com/87148770/134209571-15fb3e29-a92e-485f-9163-f2dfc1c27257.jpg)

Once you have set up your models, proceed following the instructions as stated in `III. Slicing a Model`.

Additionally, if you wish to print your infill, support, or platform in a different filament from the base model(s), select the corresponding extruder in the Advanced Settings menu when slicing your model. See `III. Slicing a Model` for information on where to adjust these settings.

*Note: As always, verify that the intended extruder is selected for each application before printing*

### Changing Printer Filament

Before changing the filament on the printer, ensure that the Pro2-Plus is not actively printing and there are no models on the print bed. Confirm which extruder you want to replace the filament of before you begin.

#### Unloading the Filament

+ Using the touchscreen on the Pro2-Plus, press `Utilities`.
+ Verify which extruder you want to replace the filament of, and press `Unload` to begin unloading the filament currently in the extruder.
  - The extruder will begin to head up and will initially extrude some filament before unloading it, this is expected.
+ Once the filament has been unloaded, you should be able to remove it from the filament feeder. 
+ When unloading filament, keep the spool wound tightly with your second hand while removing the filament from the guide tube.
  - *FAILURE TO HOLD FILAMENT SECURELY MAY RESULT IN FILAMENT UNRAVELLING CAUSING IT TO FAIL IN SUBSEQUENT PRINTS*
+ Upon expulsion of the filament, the end section will be imperfect as it has been run through the machine. Use the cutters in the lab to cut off the damaged filament.
+ Once removed and trimmed, secure the loose end of the filament by feeding it through the two holes on the filament spool.
+ Store the spool in a sealable bag to prevent damage from air moisture.

#### Loading new Filament

+ Before loading new filament, verify that the new spool is of the desired filament type. Take note of the required printing temperature as this will likely need to change with different filament types.
+ Place the new spool of filament on the empty spool holder.
+ Carefully remove the loose end of the filament, taking care to not let the spool unravel.
  - *FAILURE TO HOLD FILAMENT SECURELY MAY RESULT IN FILAMENT UNRAVELLING CAUSING IT TO FAIL IN SUBSEQUENT PRINTS*
+ Place the loose end of the filament into the feed tube and feed through to the print head.
  - Once the filament is through the feed tube, you may remove pressure from the spool as the tube holds it in tension.
+ Using the touchscreen on the Pro2-Plus, press `Utilities`.
+ If needed, change the nozzle temperature to match the requirement of the filament that you are using.
+ Press `Load` to begin loading the filament.
  - Lightly hold the new filament in the empty hole on the print head until it begins pulling the filament through.
+ Follow the feeding operation according to the instruction on the screen.
  - Note that the extruder will purge filament when loading. Allow at least 10-15 seconds of purging, potentially longer if changing type of filament.

Note: when slicing with a new type of filament, select the newly installed filament as shown below.
![FilamentSetting](https://user-images.githubusercontent.com/87148770/134211027-8d18bb89-304f-417a-8428-cdb25fef3c40.jpg)

