# Farnsworth_Fusor_PowerSystem
## Overview
Here we present a design for a 400W 120VrmsAC 60Hz -> 33kVDC Power Converter; to power an automated Farnsworth Fusor. Relevant Power Converter control I/Os are configured to be digitally accessible by a host computer to enable remote control & monitoring. 

The power converter has four stages: a passive rectifier, an inverter (18kHz) driven by complementary PWM, a ferrite UU core 1:30 transformer, and an 8x voltage multiplier. So far, we have achieved 1kVDC output with 8.5VpAC input using the transformer and multiplier stages, while we wait on the inverter-rectifier PCB. There are four PCBs in the design, described below:

## PCB1: Passive Rectifier & 18kHz Inverter

## PCB2: 8x Voltage Multiplier, V&I Sense
