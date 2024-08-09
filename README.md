Generic application base PCB for the Raspberry Pi Pico(W)
=========================================================

**This is work in progress**

A generic application base PCB for the Pi Pico(W) and compatible
development boards.

Core features:

  - RTC (PCF8563)
  - integrated power-management with
    - near zero power-off current
    - time-based wake up via RTC-alarm
    - wake up via interrupt (e.g. with a button)
    - JST-PH2 LiPo connector
    - LiPo charging
    - battery fuel-gauge
  - I2C connectors (Stemma/Qt and Grove)
  - EYESPI connector
  - integrated XTSD-chip for data-storage
  - additional THT for all GPIOs
  - multiple 3V3+GND connectors


License
-------

[![CC BY-SA 4.0][cc-by-sa-shield]][cc-by-sa]

This work is licensed under a
[Creative Commons Attribution-ShareAlike 4.0 International
License][cc-by-sa].

[![CC BY-SA 4.0][cc-by-sa-image]][cc-by-sa]

[cc-by-sa]: http://creativecommons.org/licenses/by-sa/4.0/
[cc-by-sa-image]: https://licensebuttons.net/l/by-sa/4.0/88x31.png
[cc-by-sa-shield]:
https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg
