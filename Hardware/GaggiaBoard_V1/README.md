# Gaggiuino board

Next-gen Gaggiuino hardware controller board - WIP

X1 - AC input
X2 - 3-way valve
X3 - boiler 1 (X6 - SSR for boiler 1)
X4 - boiler 2 (X7 - SSR for boiler 2)
X5 - pump

J1 - UART
J2, J3 - I2Cs
J4, J5 - thermocouples
J6 - J9 - GPIO

PA4/5/7/PB4 pins are used by FLASH on board
SPI for thermocouples on PB12(SPI2_NSS)/PB13(SPI2_SCK)/PB14(SPI2_MISO), and CS for second chip will be PB9(SPI2_NSS)
Two I2C ports on PB6(I2C1_SCL)/PB7(I2C1_SDA) and PB10(I2C2_SCL)/PB3(I2C2_SDA)
UART on PA9/10(USART1_TX/RX)