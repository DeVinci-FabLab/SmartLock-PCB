# SmartLock-PCB



\# SmartLock-PCB



PCB design for the SmartLock project — an electronically controlled lock system developed at the DeVinci FabLab.



Designed with \*\*KiCad\*\*.



\---



\## Project Structure



SmartLock-PCB/

├── SmartLock.kicad\_pro       # KiCad project file

├── SmartLock.kicad\_sch       # Schematic

├── SmartLock.kicad\_pcb       # PCB layout

├── gerbers/                  # Fabrication files (Gerber + drill)

├── bom/                      # Bill of Materials

└── README.md



\## Description



This board handles the control logic for the SmartLock system. It interfaces with:

\- An electronic locking mechanism (solenoid / servo)

\- An access control module (badge reader / keypad / BLE)

\- A microcontroller for logic and communication



>  This section should be updated with the actual components once the schematic is finalized.



\---



\## How to Open the Project



1\. Install \[KiCad](https://www.kicad.org/) (version 7 or later recommended)

2\. Clone this repository:

```

&#x20;  git clone https://github.com/DeVinci-FabLab/SmartLock-PCB.git

```

3\. Open `SmartLock.kicad\_pro` in KiCad



\---



\## Ordering the PCB



Gerber files for fabrication are located in the `gerbers/` folder.  

They can be sent directly to a PCB manufacturer (JLCPCB, PCBWay, etc.).



