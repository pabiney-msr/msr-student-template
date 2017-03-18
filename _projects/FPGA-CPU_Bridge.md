---
layout: project
title: FPGA-CPU Communication via an External Memory Interface
image: https://pabiney-msr.github.io/msr-student-template/_images/FPGA-CPU.jpg
---
### Jan 2017 - Mar 2017

## Overview
AbstractMany embedded devices are designed around the concept of heterogeneous computing for bothspeed and power consumption reasons.  Often this will lead to systems containing a primarycompute unit (a CPU), and a secondary compute unit that acts as a co-processor, where the twoare connected through some variant of a system bus.  The most notable example of this wouldbe the standard CPU-GPU model seen in laptop and desktop computers.  In more specializedcases, such as test instrumentation, the model will often take the form of CPU-FPGA, where theprimary compute unit is a low power embedded processor.  In the context of test instrumenta-tion, this model allows for real-time data streaming from sensors to be processed by the FPGA,and then presented to the user by way of the CPU. The design and implementation of sucha system, however, is non-trivial, requiring custom software solutions to properly bridge theCPU-FPGA gap.  For example, signal acquisition and display, as seen in bench oscilloscopesand spectrum analyzers, is an application of a CPU-FPGA. To implement a FPGA-MPU bridgedesign, we will be considering communication between a TI AM1808 ARM CPU and an Al-tera FPGA . The communication will be done over the exposed EMIFA bus on the ARM CPU,which provides an interface of synchronous and asynchronous RAM, as well as DMA channelsupport. In the end, we were able to verify successful write operations to the FPGA, however,we were unsuccessful at read operations.

## Keywords
FPGA, Embedded CPU, Micro-Processor, MPU, ARM, EMIF

### Contribution
* 

### Technologies Used
* FPGA (Altera Cyclone IV)
* ARM CPU (AM1808)
* EMIF
* 500 Mhz Oscilloscope
*

## Paper
