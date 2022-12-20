# AuthLoc
## Early beta - code and pcb gerber files will be released @github within 2Q.

This project currently is in an early stage; a functional codebase for modular application loading, OTA updates, secure communications, 2g/3g/4g/NB-IoT, WiFi (2.4g), ISM 433/868, LoRA ISM (rregion dependent, based on texas instruments CC3xxx line of controllers).

The aim with MLS integration is to provide an extra layer to presence detection and location detection (with basic triangulation if the RF environment permits it; automatic ranging for 3 devices is under test and working well up to 75m currently, but in a very low-noise RF environment).

Currently the codebase is compiling for ARM64 (RK), Xtensa LX6 and STM's line of "connected" microcontrollers; a choice will be made when the final PCB is drawn up (currently at roughly the half-way point), the decision is based on many factors but power consumption, total board area, limiting the number of IC's and built-in AES acceleration are some of the driving factors.

A public beta (GPLv3) of the initial modular PCB's (which also runs on stand-alone development microcontrollers; providing they have enough IO ports) as well as the source code under the same license will be published within 2Q.

No commercial offerings or "add-on" or "subscription" etc services are to be implemented; however donations to the project will be accepted as well as (a clearly stated) kick-back on PCB production.

This will also allow an opt-in to provide data to MLS and OpenCellID when idle and RF interfaces are available to scan.
