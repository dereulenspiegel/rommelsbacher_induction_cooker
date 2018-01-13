# Rommelsbacher CT2000/IN induction cooker

This repo contains information on the process of reverse engineering parts of the control electronics of the Rommelsbacher
CT2000/IN induction cooker. The target here is to control it via a micro controler at some point.

The induction cooker contains two PCBs connected by 4 wires. The control PCB 
<img src="images/control_pcb_front.jpg" width="200" height="200" /> seems to control most of the logic. 
So theoretically it should be possible
to replace the control PCB with a microcontroller once we have figured out the two wire bus protocol.