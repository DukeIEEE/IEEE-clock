Analog LED clock

This is a project to create a programmable clock using LEDs to represent numbers and hand movements.


Contents:

AnalogClock - Arduino code
Designs - Clock designs for laser cutting
Schematics - PCB schematics and boards
Proposal - Contains a timeline for this workshop
Documents - Contains BOM and datasheets


Programming using arduino-1.0.1 and Arduino UNO programmer:

Place atmega into programmer
Connect all wires except reset to PCB
Upload ArduinoISP -- UNO, Arduino as ISP
Burn bootloader -- Arduino328, Arduino as ISP

Remove atmega from programmer
Connect reset wire
Run a sketch -- Arduino328, AVRISP mkII
