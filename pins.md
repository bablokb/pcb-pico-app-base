Pins
====


Pins on Raspberry Pi Pico
-------------------------



|                     | Pin  | Pin  |                         |
|---------------------|------|------|-------------------------|
|                     | GP0  | VBUS |
|                     | GP1  | VSYS |
|                     | GND  | GND  |
| I2C1-SDA (RTC)      | GP2  | EN   |
| I2C1-SCL (RTC)      | GP3  | 3V3  |
| DONE (Flip-Flop)    | GP4  | VREF |
|                     | GP5  | GP28 | 
|                     | GND  | GND  |
|                     | GP6  | GP27 |
|                     | GP7  | GP26 | Display Busy (EYESPI)
|                     | GP8  | RUN  | RUN
| LCD-BL (EYESPI)     | GP9  | GP22 | SD-CS (SD-Card)
|                     | GND  | GND  |
|                     | GP10 | GP21 | Display Reset (EYESPI)
| MEM-CS (EYESPI)     | GP11 | GP20 | Display D/C (EYESPI)
| GPIO1 (EYESPI)      | GP12 | GP19 | MOSI0 (EYESPI, SD-Card)
| GPIO2 (EYESPI)      | GP13 | GP18 | SCLK0 (EYESPI, SD-Card)
|                     | GND  | GND  |
| TS-CS (EYESPI)      | GP14 | GP17 | Display CS (EYESPI)
| INT (EYESPI)        | GP15 | GP16 | MISO0 (EYESPI, SD-Card)


Pins on EYESPI
--------------

| Pin | Func    | Mapped to
|-----|---------|-------------------------|
|   1 | GPIO2   | GP13
|   2 | GPIO1   | GP12
|   3 | BUSY    | GP26
|   4 | INT     | GP15
|   5 | SDA     | GP2
|   6 | SCL     | GP3
|   7 | TS_CS   | GP14
|   8 | MEM_CS  | GP11
|   9 | SD_CS   | n.c.
|  10 | DISP_CS | GP17
|  11 | RESET   | GP21
|  12 | DC      | GP20
|  13 | MISO    | GP16
|  14 | MOSI    | GP19
|  15 | SCK     | GP18
|  16 | GND     | GND
|  17 | BLITE   | GP9
|  18 | VCC     | 3V3

