sailing-robot-cape
==================

BeagleBone Black cape for the autonomous sailing robot

Issues in v1 that need to be corrected:
- Capacitors for linear regulator need to be added;
        ca. 100nF on both sides 
        and additional ca. 100uF on Vin 
        to protect batteries from high current peaks
- attention with wires that go through pin headers, if the pcb is etched
- Avoid the eMMC and HDMI (LCD) pins
- consider choosing other PWM pins? (see boat servo sail logs, PWM1A and PWM2A
  are probably the safer bets for functioning servo control
- GPS1 and SDA signal overlap near the solder jumper!!
- power supply should be switched to a switching power supply,
  since linear regulators heat up too much (and loose a high amount of energy in the process)
- power supply needs a bit wider/better spacing
