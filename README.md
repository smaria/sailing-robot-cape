sailing-robot-cape
==================

BeagleBone Black cape for the autonomous sailing robot

Issues in v1 that need to be corrected:
- Capacitors for linear regulator need to be added;
        ca. 100nF on both sides 
        and additional ca. 1kF on Vin 
        to protect batteries from high current peaks
- attention with wires that go through pin headers, if the pcb is etched
