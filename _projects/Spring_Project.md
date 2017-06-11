---
layout: project
title: 3-D Printer
image: https://pabiney-msr.github.io/msr-student-template/public/images/Printer.jpg
---
<table align="right">
	<tr>
		<td>
			<img class="project-image" src="https://pabiney-msr.github.io/msr-student-template/public/images/Printer.jpg" />
		</td>
	</tr>
	<tr>
		<td>
			<img class="project-image" src="https://pabiney-msr.github.io/msr-student-template/public/images/printerCircuit.jpg" />
		</td>
	</tr>
	<tr>
		<td>
			<img class="project-image" src="https://pabiney-msr.github.io/msr-student-template/public/images/printerScreen.jpg" />
		</td>
	</tr>
	<tr>
		<td>
			<img class="project-image" src="https://pabiney-msr.github.io/msr-student-template/public/images/PowerSupply.jpg" />
		</td>
	</tr>
</table>
<h1 id="project-title">{{ page.title }}</h1>
### Mar 2017 - Jun 2017

## Overview
    This spring project is a part of the final project for Northwestern's MSR program. This first leg of the project consisted of learning the theory behind stepper motors and 3-D printers. An ANYCUBIC Pulley 3-D printer kit was ordered along with Lattice FPGAs. The kit was ordered with the intention of analyzing the 3rd party Arduino board and other components. The FPGAs will be utilized in a later quarter. 
    In addition to assembling the printer, the firmware was not natively installed and there was no documentation provided for installing the firware succesfully. As a result, a generic ArduinoMEGA toolchain was used in combination with a personnaly debugged version of the provided firmware (they shipped code that doesn't compile,a working version is found on ym GitHub). All-in-all the kit suffers from many flaws, both in production design and in the end user instructions. While the ability to reprogram and edit the source for this printer will be beneficial to the project, needing to debug code in order to get a printer to work out of the box is not ideal.
    Addionally the board was set up out of the box to not allow USB programming of the arduino-clone board. This was caused by the DC pins being connected together rather than the USB pins being connected together. The firmware also needs to be installed before anything is connected to the board. The board is capable of being powered by the USB port, making teh external power supply redundant. In fact, the external power supply came with no documentation and is for the optional heated bed. The optional heated bed is unable to be attached in the kit without ordering additional parts as the glass plate cannot be affixed attop it securely.

<b><i>Keywords: 3-D Printing, Arduino, Stepper Motors, C/C++</i></b>
<br>
<a href="https://github.com/pabiney-msr/MSR_Final_Project">GitHub</a>

### Tasks
* Research Components
* Order Components
* Research Stepper Motors
* Assemble ANYCUBIC 3-D printer
* Configure toolchain for printer
* Instal Firmware
* Debug Firware
* Instal Cura
* Learn to use Cura

### Technologies Used
* Arduino IDE
* ArduinoMEGA
* Cura
* Windows
* Linux
* C/C++
* GitHub
