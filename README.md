### This is a WORK IN PROGRESS!

---

### Ownership and License
The contributors are listed in CONTRIB.TXT. 

### Overview

The MIO168+ module features multiple digital I/O, analog outputs and expansion connectors for carry various AFEs.

### Feature list

* On-board [STM32F446ZCT6](https://www.st.com/content/st_com/en/products/microcontrollers-microprocessors/stm32-32-bit-arm-cortex-mcus/stm32-high-performance-mcus/stm32f4-series/stm32f446/stm32f446zc.html) high-performance foundation line MCU, ARM Cortex-M4 with DSP and FPU, 256 KiB Flash, LQFP-144 package 
* AFE interface
* 8 x protected digital inputs (3.3/5/24 V), 2 x fast/slow, 6 x slow
* 8 x digital outputs with multiple protections, voltage clamp 24V, nom. current 330 mA (limit 2.3 A)
* 2 x PWM outputs (protected) or sensor bias power (+/-15 V, max. 10 mA)
* 2 x analog bipolar outputs (+/-5 V, +/-10 V, 0-5 V, 0-10 V). Voltage or current output with protection. 12-bit DAC, replaceable with pin compatible 14- or 16-bit version
* 2 x analog bipolar outputs +/-10 V. 12-bit DAC, replaceable with pin compatible 14- or 16-bit version
* On-board isolated power supply with +/-5.3 V outputs (with 4x multipliers), +/-15 V and +3.3 V LDO
* On-board SDRAM for measured data buffering (optional)
* USB HS PHY
* Firmware download via SPI or USB
* Optional SWD for debugging
* I2C EEPROM for storing board specific parameters
* Dimensions: TBA, 4-layer PCB

### Related topics and links

* [EEZ BB3+](https://github.com/eez-open/eez-bb3plus)
* [MIO168+ AFE3](https://github.com/eez-open/dib-mio168plus-afe3)
* [MIO168](https://github.com/eez-open/dib-mio168) for EEZ BB3 (retired)

---

This work is financed by [NLnet](https://nlnet.nl/project/BB3-CM5/) foundation

![nlnet](Images/nlnet-logo.png)