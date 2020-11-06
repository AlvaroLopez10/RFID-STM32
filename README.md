# RFID with STM32F103C8T6

**Connection Pins**
- VCC ---------- 3.3V
- GND ---------- GND
- RST ----------- 3.3V
- CS (SDA) ------- PA4
- SCK ----------- PA5
- MISO ---------- PA6
- MOSI ---------- PA7
- IRQ ------------ ---

![](https://os.mbed.com/media/uploads/hudakz/stm32f103c8t6_pinout_voltage01.png)

**Software Development Tools**
- STM32CubeMx
- Keil uVision
- STM Studio

**How to Flash STM32F103C8T6**
1. Connect STM with ST-Link
2. Open MDK-ARM/RFID_Lib1.uvprojx **(Keil Project)**
3. Click on "Options for Target"

![Image1](https://github.com/AlvaroLopez10/RFID-STM32/blob/master/doc/images/image1.png?raw=true)

4. Click on "Debug" tab
5. Click on "Settings". Make sure you are using ST-Link Debugger
6. Click on "Flash Download" tab
7. Make sure "Reset and Run" is checked and click OK
8. Click on "Build" to compile and create target files
9. Click on Load
10. Reset STM32F103C8T6 with the button on the board