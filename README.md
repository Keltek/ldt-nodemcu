# LDT NodeMCU Integration

This project integrates NodeMCU support in Lua Development Tools (LDT) as a new Execution Environment.

No debugging support! Only autocomplete!

LDT can be a downloaded as a standalone IDE or as a part of Eclipse IDE.

More Infos at: https://eclipse.org/ldt/

The documentation is taken from http://nodemcu.readthedocs.io/en/dev/en/ and https://github.com/nodemcu/nodemcu-firmware (source files).

##Installation
Download the zip file in the "release" directory of your desired NodeMCU Version of this repository.

Open LDT and goto Preferences. On the left side choose "Lua".

Click on "Execution Environment" and then the "Add..." button.
![Add zip](/pics/add-ee01.png?raw=true)

Select the downloaded zip file.

Now you can click on File->New->Lua Project and select the Lua NodeMCU Execution Environment.

![Create Project](/pics/create-proj01.png?raw=true)

##Autocomplete support
If your project Execution Environment is set correctly, you will get autocomplete support for NodeMCU specific functions.
![Autocomplete](/pics/autocomplete01.png?raw=true)

##Modules implemented
The following table describes the progress of integration of the NodeMCU modules.

| Module       | Integration  |
| ------------ |:------------:|
| dht          | no           |
| file         | partly       |
| gpio         | partly       |
| i2c          | no           |
| mqtt         | no           |
| net          | partly       |
| node         | partly       |
| tmr          | partly       |
| wifi         | partly       |


##Links
https://wiki.eclipse.org/LDT/User_Area/Tutorial/Create_a_simple_Execution_Environment
https://wiki.eclipse.org/LDT/User_Area/Execution_Environment_file_format