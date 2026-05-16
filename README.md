# Mocon
A dev board with an upgraded LDO compared to other traditional devboards, which will allow for using devices that need higher current draw. 

I made this to allow for easier prototyping as it gives extra breathing space when prototyping with many components connected at once to a dev board.

# Features
	RP2040 chip
	29 GPIO pins
	12Mhz Crystal
	High current LDO

# Schematic
<img width="1497" height="1033" alt="image" src="https://github.com/user-attachments/assets/d44dbfbc-3254-464c-8599-619ff1269264" />

# PCB	
<img width="347" alt="image" src="https://github.com/user-attachments/assets/0af21b30-20e2-47ef-b381-497589be78c4" />
<img width="341" alt="image" src="https://github.com/user-attachments/assets/b065c431-f6f1-46ab-8798-143af90ca58e" />

# Ordering
Upload the zipped Prod folder to JLCPCB and go through their steps for a PCBA.

# BOM if u want to solder it on your own (might be more expensive than PCBA)
| Id | Designator | Footprint | Quantity | Comment |
| --- | --- | --- | --- | --- |
| 1 | C6,C12,C3,C17,C8,C5,C4,C7,C11,C2,C9 | C_0402_1005Metric | 11 | .1uF |
| 2 | C1,C10 | C_0402_1005Metric | 2 | 1uF |
| 3 | R7,R5 | C_0402_1005Metric | 2 | 1k |
| 4 | U2 | SOT-23-5 | 1 | AP2112K-3.3 |
| 5 | C13,C14 | C_0603_1608Metric | 2 | 10uF |
| 6 | C16,C15 | C_0402_1005Metric | 2 | 33pF |
| 7 | R2,R1 | C_0402_1005Metric | 2 | 5.1k |
| 8 | J1 | USB_C_Receptacle_HRO_TYPE-C-31-M-12 | 1 | USB_C_Receptacle_USB2.0_14P |
| 9 | SW1 | SW_Push_SPST_NO_Alps_SKRK | 1 | SW_Push |
| 10 | Y1 | Crystal_SMD_3225-4Pin_3.2x2.5mm | 1 | 12 MHz |
| 11 | R3,R4 | C_0402_1005Metric | 2 | 27 |
| 12 | U1 | QFN-56-1EP_7x7mm_P0.4mm_EP3.2x3.2mm | 1 | RP2040 |
| 13 | R6 | C_0402_1005Metric | 1 | 10k |
| 14 | J4 | PinHeader_1x03_P2.54mm_Vertical | 1 | Conn_01x03 |
| 15 | U3 | Winbond_USON-8-1EP_3x2mm_P0.5mm_EP0.2x1.6mm | 1 | W25Q16JVZPIQ TR |
| 16 | J2,J3 | PinHeader_1x20_P2.54mm_Vertical | 2 | Conn_01x20 |

# Silk Screen Sneak Peeks ;)

<img width="1450" alt="image" src="https://github.com/user-attachments/assets/cc319af6-d1ca-4cfd-ae5e-6dd0e4402ff4" />
<img width="1450" alt="image" src="https://github.com/user-attachments/assets/c02b9b6c-b4e7-4a12-aaf5-394302a7f3af" />



