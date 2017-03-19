---
layout: project
title: FPGA-CPU Communication via an External Memory Interface
image: https://pabiney-msr.github.io/msr-student-template/public/images/result_wr.jpg
---
<table align="right">
	<tr>
		<td>
			<img class="project-image" src="https://pabiney-msr.github.io/msr-student-template/public/images/result_wr.jpg"/>
		</td>
	</tr>
	<tr>
		<td>
			<img class="project-image" src="https://pabiney-msr.github.io/msr-student-template/public/images/FPGA-ARMblockdiagram.png"/>
		</td>
	</tr>
	<tr>
		<td>
			<img class="project-image" src="https://pabiney-msr.github.io/msr-student-template/public/images/FPGA-CPU.jpg"/>
		</td>
	</tr>
</table>
<h1 id="project-title">{{ page.title }}</h1>
### Jan 2017 - Mar 2017

## Overview
Implementation of a FPGA-CPU bridge for communication between a TI AM1808 ARM CPU and an Altera FPGA over the exposed EMIFA bus on the ARM CPU, which provides an interface of synchronous & asynchronous RAM, as well as DMA channelsupport. In the end, we were able to verify successful write operations to the FPGA, however, we were unsuccessful at read operations.

<b><i>Keywords: FPGA, Embedded CPU, Micro-Processor, MPU, ARM, EMIF, C, GCC</i></b>

### Tasks
* Paired Programming.
* Debugging with teammate.
* Oscilloscope Probing of pins.
* Presentations of project.
* Team Meetings.
* Wrote Weekly Updates.
* Contributed to Paper.

### Technologies Used
* FPGA (Altera Cyclone IV)
* ARM CPU (TI AM1808)
* EMIF
* 500 Mhz Oscilloscope
* C
* GCC

### Paper
<q> Many embedded devices are designed around the concept of heterogeneous computing for both speed and power consumption reasons. Often this will lead to systems containing a primary compute unit (a CPU), and a secondary compute unit that acts as a co-processor, where the two are connected through some variant of a system bus. The most notable example of this would be the standard CPU-GPU model seen in laptop and desktop computers. In more specialized cases, such as test instrumentation, the model will often take the form of CPU-FPGA, where the primary compute unit is a low power embedded processor. In the context of test instrumentation, this model allows for real-time data streaming from sensors to be processed by the FPGA, and then presented to the user by way of the CPU. The design and implementation of such a system, however, is non-trivial, requiring custom software solutions to properly bridge the CPU-FPGA gap.</q>
<a href="https://pabiney-msr.github.io/msr-student-template/public/papers/EECS495_FPGA_MPU_Project.pdf">Read More</a>