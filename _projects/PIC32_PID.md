---
layout: project
title: LED-Photoresistor PID Controller with the PIC32
image: https://pabiney-msr.github.io/msr-student-template/public/images/NU32.png
---
<table align="right">
	<tr>
		<td>
			<img class="project-image" src="https://pabiney-msr.github.io/msr-student-template/public/images/NU32.png"/>
		</td>
	</tr>
	<tr>
		<td>
			<img class="project-image" src="https://pabiney-msr.github.io/msr-student-template/public/images/LEDGains.png"/>
		</td>
	</tr>
</table>
<h1 id="project-title">{{ page.title }}</h1>
### Feb 2017

## Overview
Implement a Position-Integral-Differential (PID) Controller with a LED, a Photoresister, and a NU32. The NU32 interfaces with python on a host machine via usb cable to plot out the sampled ADC values.
<b><i>Keywords: C, Python, PID, Mechatronics, PIC32, Microcontroller, Circuits</i></b>

### Tasks
* Configure ADC Register.
* Configure Timer Register.
* Wrote Interupt Service Request.
* Sample ADC values.
* Tune PID Gain Values.

### Technologies Used
* C
* Python
* PIC32
* nScope