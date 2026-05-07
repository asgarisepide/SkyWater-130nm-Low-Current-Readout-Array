# Low-Current Readout Array for NIST Nanotechnology Accelerator Project

Custom integrated circuit developed for ultra-low current sensing applications in the NIST Nanotechnology Accelerator Project.

## SkyWater 130nm Tapeout Completed

![Low Current Readout Array](Low_Current_Readout.png)

## Project Overview

Designed a multi-channel low-current readout array in SkyWater 130-nm CMOS technology for precision current measurement and nanoscale sensing applications.
This design contains a mixed-signal readout array and a Bioinformatics Processing Unit that:

- Amplifies the pico-ampere-range current signals
- Filters high frequency contents
- Samples the analog input
- Digitizes the samples with SAR ADCs
- Stores the digital data in a memory
- Read the memory and analyse the data to identify the DNA sequence

- ## Description

This project introduces a system on chip (SOC) including a high-speed, low-power mixed-signal readout array (the DROIC), and a RISC-V microprocessor (the BPU) for analyzing the readout data. The proposed DROIC system consists of an array of channels, capable of simultaneous amplification, filtering, and digitization of pico-ampere range current signals with sufficient accuracy and speed.

Figure 1 depicts the general manner of operation of nanopore-based sequencing (i.e., DNA moves through a nanopore protein and thus induces a small current signature indicative of the DNA’s make-up) and the key DROIC and BPU blocks that enable it.

The novelty of this design is the use of a new readout method in each channel to reduce power consumption compared to the previous works [1], [2], [3] as well as an in-pixel ADC, shown in Figure 2, to overcome substrate and switching noise.


In order to test an on-chip circuits will be defined to generate the pico-ampere currents. Also, a timing technique will be used to separate the digital and analog circuitry operating times.
## Key Highlights

- Multi-channel readout array architecture
- Ultra-low current sensing capability
- Analog front-end circuit design
- Custom IC implementation
- Full physical layout
- Tapeout completed

## Responsibilities

- System architecture
- Schematic design
- Layout implementation
- Verification
- Tapeout preparation

## Technology

SkyWater 130nm CMOS

## Tools

Open source tools: Xscheme | Magic | Ngspice | Klayout
