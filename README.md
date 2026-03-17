# STM32 Microcontroller USB Development Board

This project is a custom STM32 microcontroller based USB development board designed using KiCad.  
The board includes LDO based 3.3V power regulation, USB interface for communication and power, 
external crystal oscillator for stable clock operation and GPIO expansion headers.

The PCB is designed as a 2-layer board with a dedicated ground plane for improved signal integrity 
and stable power distribution.

---

## Features

- STM32 microcontroller based development board
- USB interface for programming and communication
- 3.3V LDO voltage regulator
- External crystal oscillator for accurate clock
- Decoupling capacitors for power stability
- GPIO expansion headers
- 2-layer PCB with ground plane

---

## Design Workflow

Schematic Design  
↓  
Component Selection  
↓  
PCB Layout and Routing  
↓  
Design Rule Check (DRC)  
↓  
Gerber File Generation  
↓  
PCB Manufacturing

---

## PCB Preview

### Schematic
<img width="953" height="567" alt="STM 32 PCB SCH" src="https://github.com/user-attachments/assets/13b19c18-86f5-4224-a72f-76d5e4fcf0ac" />

### PCB Layout
<img width="719" height="543" alt="STM32 PCB LAYOUT" src="https://github.com/user-attachments/assets/c4843e52-6dd3-4242-be60-a0409878b2c0" />

### 3D View (Top)
<img width="812" height="602" alt="STM32 TOP LAYER 3D VIEW" src="https://github.com/user-attachments/assets/424adc79-c237-4a39-88b7-e249e442f293" />

### 3D View (Bottom)
<img width="696" height="536" alt="STM32 BOTTOM LAYER 3D VIEW" src="https://github.com/user-attachments/assets/a5d93ec8-a0fb-4e8b-8711-36ca1aeeb96b" />





---

## Project Files

- **Schematic** – KiCad schematic design files  
- **PCB Layout** – Complete PCB layout and routing files  
- **Gerber Files** – Manufacturing files used for PCB fabrication 

---

## Tools Used

- KiCad

---
## Project Structure

STM32-MICROCONTROLLER-USB-DEVELOPMENT-BOARD

│
├── Schematic
│   └── stm32_usb_board.kicad_sch
│
├── PCB
│   └── stm32_usb_board.kicad_pcb
│
├── Gerber
│   └── gerber_files.zip
│
├── Images
│   ├── pcb_top.png
│   ├── pcb_bottom.png
│   └── pcb_3d.png
│
└── README.md

## Author

**Pragya Shrivastav**  
Electronics & Communication Engineer  
PCB Design | Embedded Hardware
