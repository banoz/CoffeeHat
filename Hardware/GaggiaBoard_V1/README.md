# Gaggiuino board

Next-gen Gaggiuino hardware controller board - WIP
```
J22, J23 - AC input
J10, J11 - 3-way valve
J12, J13 - boiler 1 (J14, J15 - SSR for boiler 1)
J16, J17 - boiler 2 (J18, J19 - SSR for boiler 2)
J20, J21 - pump

J1 - UART1 (PA9/10)
J2, J3 - I2Cs
J4, J5 - thermocouples
J6 - Pressure sensor (ADS1015 on I2C2)
J7 - Brew (PB1) / Steam (PB0) switch
J8 - Scales (PA1 -> CLK, PA2 -> D1, PA3 -> D2)
J9 - SSR control (PA6 -> SSR1, PA8 -> SSR2)

AC zero-cross sense on PA0
Buzzer on PB5
Pump control on PB8
Heater 1 relay on PC14
Heater 2 relay on PC13

SPI1 on PA4/5/7/PB4 pins is used by FLASH on board or MicroSD card

SPI2 is used for thermocouples on PB12(SPI2_NSS)/PB13(SPI2_SCK)/PB14(SPI2_MISO), and CS for second chip will be PB9(SPI2_NSS)

Two I2C ports on PB6(I2C1_SCL)/PB7(I2C1_SDA) and PB10(I2C2_SCL)/PB3(I2C2_SDA)

