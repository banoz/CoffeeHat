# Gaggiuino board

Gaggiuino hardware controller board v4 - WIP

```
J10, J11 - AC input
J12 - pump
J13 - 3-way valve

J1 - UART2 (PA2/PA3)
J2 - I2C
J4 - thermocouple
J5 - PA12, PB15, GND
J6 - Pressure sensor (ADS101X/ADS111X on I2C1)
J7 - Brew (PC14) / Steam (PC15) switch
J8 - Scales (PB0 -> CLK, PB8 -> D1, PB9 -> D2)
J9 - 5V SSR control (PA15 -> SSR1, PA8 -> SSR2)

AC zero-cross sense on PA0
Pump control on PA1
3-Way valve control on PC13

SPI1 is used by thermocouple amplifier on PA5(SPI1_SCK)/PB4(SPI1_MISO), and CS on PA6

I2C port on PB6(I2C1_SCL)/PB7(I2C1_SDA)

J15 - USB-C

J27 - SWD, USART1 (PA9/10), NRST and BOOT1
```

![GaggiaBoard_V4_s1](https://github.com/banoz/CoffeeHat/blob/main/Hardware/GaggiaBoard_V4/EAGLE/Exports/GaggiaBoard_V4_s1.png)
![GaggiaBoard_V4_s2](https://github.com/banoz/CoffeeHat/blob/main/Hardware/GaggiaBoard_V4/EAGLE/Exports/GaggiaBoard_V4_s2.png)
