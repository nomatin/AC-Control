# IR AC control on ESPHome
An IR-based air consicioner countroller with ESPHome and ESP32C6
>[!Info] A small weekend project for my smart home.
## Case
The case was created in T-FLEX CAD 17. STL and STEP files are located in the folders STL_CASE and STEP_CASE.
![image](img/case_render.png)
The case is designed for 3 mm LEDs. If you have 5 mm LEDs, there is an IR LED diameter parameter(D_led) in the source files of the case. I recommend adding 0.2-0.4mm when printing the case.
![image](img/case_resize.gif)
#### Printing

#### I used these parameters for 3D printing:
 - Layer height - 0.2mm
 - Default line width - 0.4mm
 - Inner line width - 0.6mm
 - Wall loops - 3
 - Fruzzy skine type - Ridged
 - Fruzzy skine thinckness - 0.1mm

### Sheet
![image](img/sheet.png)
### Componet list
| Component | Qty | Link |
|-----------|-----|------|
|Seeed Studio XIAO ESP32C6|1| [Getting Started](https://wiki.seeedstudio.com/xiao_esp32c6_getting_started/) |
|GY-BMP280-3.3 Pressure Sensor Module|1|[Datasheet](https://5.imimg.com/data5/SELLER/Doc/2022/1/WG/FV/GY/1833510/gy-bmp280-3-3-high-precision-atmospheric-pressure-sensor.pdf)|
|NPN trinsistor 2N5551|1|[Datasheet](https://www.onsemi.com/download/data-sheet/pdf/2n5551t-d.pdf)|
|3mm IR led 940nm|3|[Datasheet](https://www.everlighteurope.com/custom/files/datasheets/DIR-0000248.pdf)|
|Resistor 15ohm|1||
|Resistor 470ohm|1||
