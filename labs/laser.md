#The Epilog Fusion Pro Laser

This article goes over the Epilog Laser in the RPL. Since the station currently does not yet have a dedicated workstation, you must use your own laptop to command the laser. 
Connecting your device to the laser is part of the *Getting Started* section.

Prior to using the Epilog Laser, please familiarize yourself with the locations of the:

+ Fire extinguisher
+ Exhaust fan control
+ Emergency stop (on the laser itself)
+ Safety glasses

and read all safety material that may be present at the Laser work area.

The `Exhaust Fan Control` is next to the south door and can be set between 1 and 10.
Please remember to turn this off before leaving, once you're finished with the laser cutter.

## Gettings Started

Connecting to the Machine

+ Install the driver to your local machine: https://www.epiloglaser.com/tech-support/fusion-pro-drivers.htm
+ Connect ethernet
	- Set manual IP address
	- IP 192.168.1.11
	- MASK 255.255.0.0
	- Gateway 192.168.0.254

Note that the IP address of the machine is 192.168.1.10, your IP should not be set the same as the machine.

### Windows Adapter Settings
In order to set the IP address successfully, you must modify the IPv4 adapter settings. This process is summarized by the images below, but note that it contains incorrect IPs. You should use the IP set above.

![](../img/laser/adapter/1.JPG)
![](../img/laser/adapter/2.JPG)



### Running the machine

+ Turn on exhaust air supply to 10
+ Turn the key to ON
+ Release E-STOP

### Shut down procedures

+ Engage E-STOP
+ Turn the key to OFF
+ Turn off exhaust supply (to 0)

# Warnings
** LEAVE THE DOOR CLOSED for 10 seconds after a job finishes to clear the smoke **

*Exhaust Fan Control* MUST be turned on prior to running jobs. It clears toxic fumes that result from the laser cutting process.

## Machine Interface
A brief description of the components of the Laser's Ui is explained below:

![](../img/laser/touch_interface.JPG)

## Procedures
The printing procedures are, briefly: 

+ Submitting a job
+ Aligning the material
+ Pushing the job to the laser
+ Jogging & Focusing the laser
+ Running the job

###    Submitting jobs
To load a job, you must 'print' to the laser cutting driver, like you would an actual printer. Typically this is as simple as File > Print.

Generally, though, you should be printing from a vector graphics program like Inkscape or Illustrator.

Once on the Dashboard you can select 'Engrave' or 'Vector cut' and select a profile for the material and thickness that you're working with. 

### Aligning materials 
Materal alignment is done through a combination of moving the material and adjusting the placement of the design in the Epliog Dashboard

After printing, it should open in the Epilog Dashboard where you can see your document and the inside of the printer. You can move your design onto the material you placed inside the bed.

### Pushing the job 
Now you can 'Print' the job from the Dashboard, submitting it to the cutter. After this is done, it will be selectable on the File Explorer section of the touchscreen. 

###    Jogging the head
On the touchscreen of the cutter, select the 'Joystick' tab, which will allow you to control the head with the actual joystick. Move the head over to your material. Now you can autofocus the machine.

###    Focus for the material
On the same screen, select the 'Auto Focus' button. The bed will move up towards the head until it engages the sensor.

### Running the Job
Now you're ready to run the job. Go to the File Explorer section and select your the job that you pushed earlier. If you're ready to continue, press the physical 'Play/Pause' button. This will start the job. 



## Table choice
There are different types of tables available for different types of jobs. 

### Vector
If you're going to be vector cutting, or engraving then cutting out the outline, you ** MUST ** use the grid shaped bed. Using the other bed types will lead to scarring of the bed, and worse yet, release of unwanted chemicals. 

### Engrave
If you _only_ want to engrave, you can use the engraving bed, which is mostly a solid and very flat. If you want to Vector cut the outline of the engraving, you will need to move it over to the grid type bed first, or start the engraving on the grid bed and cut it afterwards.

# Materials
Any material that contains chlorine (e.g. PVC, vinyl) will *DESTROY* the laser. Please *ONLY* use the materials listed below, which are listed as acceptable from the manufacturer.

If requested, you may need to prove that the material you’re using is on the allow-list. Please bring a copy of your purchase order or MSDS for the materials you bring in.

![](../img/laser/materials.JPG)


In text form, the materials list from the above image are reproduced below.

## Acceptable, Cut and Engrave
  + Wood
  + Acrylic
  + Fabric
  + Delrin
  + Leather
  + Matte Board
  + Melamine
  + Mother of Pearl
  + Paper
  + Mylar
  + Pressboard
  + Rubber
  + Wood Veneer
  + Fiberglass
  + Cork
  + Corian


## Acceptable, Engrave

  + Anodized Aluminum
  + Stainless Steel*
  + Brass*
  + Titanium*

(*)Note: bare metals are only markable if coated with a metal marking solution.

