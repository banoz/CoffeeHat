# Gaggiuino board

Next-gen Gaggiuino hardware controller board - WIP

[3D model](https://github.com/banoz/banoz.github.io/blob/main/repository/stl/GaggiaBoard_V2.stl)

```
J14 - steam boiler heater element
J11 - steam boiler supply valve
J16 - 3-way valve
J17 - pump
J19, J20 - AC input

J1 - UART2 (PA2/PA3)
J2, J3 - I2Cs
J4 - thermocouple
J6 - Pressure sensor (ADS101X/ADS111X on I2C1)
J7 - Brew (PC14) / Steam (PC15) switch
J8 - Scales (PB0 -> CLK, PB8 -> D1, PB9 -> D2)
J9 - 5V SSR control (PA15 -> SSR1, PA8 -> SSR2)

AC zero-cross sense on PA0
Pump control on PA1
Buzzer on PB14
Steam boiler heater element relay on PB13
Steam boiler supply valve relay on PB12
3-Way valve control on PC13

SPI1 is used by thermocouple amplifier on PA5(SPI1_SCK)/PB4(SPI1_MISO), and CS on PA6

Two I2C ports on PB6(I2C1_SCL)/PB7(I2C1_SDA) and PB10(I2C2_SCL)/PB3(I2C2_SDA)

J27 - USART1 (PA9/10) with NRST and BOOT1
```
![GaggiaBoard_V2_s1](https://github.com/banoz/CoffeeHat/blob/main/Hardware/GaggiaBoard_V2/EAGLE/Exports/GaggiaBoard_V2_s1.png)
![GaggiaBoard_V2_s2](https://github.com/banoz/CoffeeHat/blob/main/Hardware/GaggiaBoard_V2/EAGLE/Exports/GaggiaBoard_V2_s2.png)
![GaggiaBoard_V2_top](https://github.com/banoz/CoffeeHat/blob/main/Hardware/GaggiaBoard_V2/EAGLE/Exports/GaggiaBoard_V2_top.png)
