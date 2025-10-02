# Clever board

ESP32-C6 based controller board v1 - WIP

```
J10, J11 - AC input
J12 - pump
J13 - 3-way valve

J1 - UART0 (IO16/IO17)
J2 - I2C (IO6/IO7)
J3 - IO8, IO9
J5 - IO3
J6 - Pressure sensor (IO2, 10K/20K voltage divider)
J7 - Brew (IO22) / Steam (IO23) switch
J8 - IO19, IO20, IO21
J9 - 5V SSR control (IO10 -> SSR1, IO11 -> SSR2)

AC zero-cross sense on IO0
Pump control on IO18
3-Way valve control on IO15

I2C port on IO7(I2C1_SCL)/IO6(I2C1_SDA)
```

![CleverBoard_V1_s1](https://github.com/banoz/CoffeeHat/blob/main/Hardware/CleverBoard_V1/EAGLE/Exports/CleverBoard_V1_s1.png)
![CleverBoard_V1_s2](https://github.com/banoz/CoffeeHat/blob/main/Hardware/CleverBoard_V1/EAGLE/Exports/CleverBoard_V1_s2.png)

Top|Bottom
---|---
![CleverBoard_V1_top](https://github.com/banoz/CoffeeHat/blob/main/Hardware/CleverBoard_V1/EAGLE/Exports/CleverBoard_V1_top.png)|![CleverBoard_V1_top](https://github.com/banoz/CoffeeHat/blob/main/Hardware/CleverBoard_V1/EAGLE/Exports/CleverBoard_V1_bottom.png)
