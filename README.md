# Devmini
Pro Micro-compatible ATmega32U4 board with extra I/O pins and external power management support.

<img width="4032" height="3024" alt="IMG_9495_MOD" src="https://github.com/user-attachments/assets/ca09f34a-d305-4d68-bcc5-86e4ee76be42" />

Devmini extends the classic Pro Micro form factor by exposing additional ATmega32U4 pins not broken out on the original: pins 11, 12, 13, 22, and 23 are available via a 5-pin horizontal header on the short side, while pins 17 and 30 are accessible as SMD pads (pin 30 is also connected to an onboard LED). An external power management footprint allows clean power supply filtering for audio applications or more complex battery-powered systems. If no external power management is needed, bridging the two pads marked VCC=VUSB with a solder joint connects VCC directly to the USB supply.

Optimized for use with [Arpmini-Core](https://github.com/PaoloEstorm/Arpmini-Core) with [Nanoboot](https://github.com/PaoloEstorm/Arpmini-nanoBoot), but fully compatible with the standard Arduino Micro "caterina" bootloader.

PCB by JLCPCB https://oshwlab.com/estorm/project_ciikqkov
