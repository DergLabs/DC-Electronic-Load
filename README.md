# DC-Electronic-Load

This is my 2nd revision of a custom DC electronic load. This repo will contain all the PCB and schematic files. Unfortunately, all of the firmware and code to this project was lost due to a hard drive corruption and it will need to be re-written. I will attempt to re-start this project once I have more available time. 

The design is comprised of 3 main parts, the controller board, the mainboard, and the front panel board. The controller board contains the analog sense and setting circuitry, fan control, temperature sensing, display and button IO, and the microcontroller. Currently, a ATMega2560 is being used however, this might be replaced with either a Teensy 4.1 or STM32 for more advanced capabilities. 

The mainboard contains the two high-power linear MOSFETs, the reverse polarity protection diode and the sense resistors. It also includes the AC-DC power supply and DC-DC linear power supply for the analog circuitry. 

Finally, the front panel IO board will house the vacuum fluorescent display, soft-touch push buttons, LED's, and rotary encoder.

Future plans for this project include a revamped, fully isolated analog section, a new MCU with improved software, and a MOSFET-based reverse polarity protection circuit.
