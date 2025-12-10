# ing1-s1-architecture-td5

## Instructions

Instructions available in [instructions.pdf](./instructions.pdf).

## Development environment setup

### Requirements

- Windows 11
- [Keil uVision latest version](www.keil.com/demo/eval/arm.htm)
- 

### Keil uVision setup

1. Install Keil uVision
2. `Windows Security > Device Security > Core Isolation > Memory Integrity`: turn off
3. [Download driver](https://www.ti.com/tool/LM_FTDI_DRIVER)
4. `Device Manager > Update Driver`
5. [Download Add On](https://developer.arm.com/documentation/ka002280/latest), install where `Keil_5` is installed (get the path in Keil uVision `Help > About uVision`)

### Project setup

1. New project
2. In `Options for target`: 
    * `Device > Texas Instrument > LM3S Series > LM3S1xxx > LM3S1968`
    * `Target > Use microlib`
    * `Debug > Use > Stellaris ICDI`
3. In `Manage runtime environment`: 
    * `CMSIS > Core`
    * `Device > Startup`

### Development workflow

1. Code
2. Rebuild
3. Load
4. Click button `ON/RESET` on Stellaris Evalbot
