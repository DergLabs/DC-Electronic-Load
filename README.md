# DC-Electronic-Load

This is my 2nd revision of a custom DC electronic load. This repo will contain all the PCB and schematic files. Unfortunately, all of the firmware and code to this project was lost due to a hard drive corruption and it will need to be re-written. I will attempt to re-start this project once I have more available time. 

The design is comprised of 3 main parts, the controller board, the mainboard, and the front panel board. The controller board contains the analog sense and setting circuitry, fan control, temperature sensing, display and button IO, and the microcontroller. Currently, a ATMega2560 is being used however, this might be replaced with either a Teensy 4.1 or STM32 for more advanced capabilities. 

The mainboard contains the two high-power linear MOSFETs, the reverse polarity protection diode and the sense resistors. It also includes the AC-DC power supply and DC-DC linear power supply for the analog circuitry. 

Finally, the front panel IO board will house the vacuum fluorescent display, soft-touch push buttons, LED's, and rotary encoder.

Future plans for this project include a revamped, fully isolated analog section, a new MCU with improved software, and a MOSFET-based reverse polarity protection circuit.

Project Progress: 

Initial test Perf boards: 

![IMG_2087](https://user-images.githubusercontent.com/11001357/168873162-a770f7fc-e190-459c-ba97-7c15927525d5.jpeg)

![IMG_2088](https://user-images.githubusercontent.com/11001357/168873222-10be59ba-3d28-4e7b-a442-4783fe7d613c.jpeg)

Current PCB Assembly with custom controller: 

![IMG_2207](https://user-images.githubusercontent.com/11001357/168873283-be232a22-0ec8-4f3f-add3-230e766d1f71.jpeg)

