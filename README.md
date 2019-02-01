# iot-course
This folder houses software materials for the Waziup IoT and Big Data Cloud Platform.

---------------------------------------Arduino Folder-----------------------------------------

The Arduino folder contains three sub folders namely:

1. *Installations & Softwares* - this folder contains driver software for all Waziup related hardware.

		For the NanoLora and Wazidev v1.2 boards to work properly on windows, simply download and install "CH341SER.EXE".

2. *examples* - this folder contains code examples for various prototyping use cases with Waziup.

		To have all Waziup code examples showing up inside your Arduino examples list.

		-First close your Arduino IDE and all related processes.
		-Copy "12.Waziup" and paste inside the examples folder at "..\Program Files (x86)\Arduino\examples".
		-Open your Arduino IDE and navigate to "Files->Examples->Waziup" to find all examples.

	*NOTE*: The file path above is dependent your primary drive letter. Just find the "Arduino" folder inside your.
	"Program Files (x86)" on you primary drive and locate the "examples" folder.

3. *libraries* - this folder contains libraries needed to enable code examples to work properply with sensors and related hardware.

		-First close your Arduino IDE and all related processes.
		-Copy all the content of the libraries folder.
		-Navigate to "..\Documents\Arduino\libraries" and paste.
		-Open your Arduino IDE and navigate to "Sketch->Inlude Library".

----------------------------------------------------------------------------------------------